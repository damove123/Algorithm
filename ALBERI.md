# DFS – Visita in profondità

```cpp
visitaDFS(Node r) {
  Stack S;
  push(S, r);
  while (!stackEmpty(S)) {
    u = pop(S);
    if (u != NIL) {
      // visita il nodo u
      push(S, u.right);
      push(S, u.left);
    }
  }
}
// Complessità lineare
```

### Versione ricorsiva
```cpp
visitDFS_rec(Node r){
  if(r!=NIL){
    //visita il nodo r
    visitaDFS_rec(r.left)
    visitaDFS_rec(r.right)
  }
}
```

# BFS - Visita in ampiezza

```cpp
visitaBFS(Node r){
  Queue C
  C  = newQueue()
  enqueue(C, r)
  while(!queueEmpty(C)){
    u = dequeue(C)
    if (u != NIL){
      visita il nodo u
      enqueue(C, u.left)
      enqueue(C, u.right)
    }
  }
}

