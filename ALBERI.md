## DFS – Visita in profondità

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
