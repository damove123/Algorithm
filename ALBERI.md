DFS - Visità in profondità 
'''text
  visitaDFS(Node r) 
    Stack s
    push(S, r)
    while !stackEmpty(S)
      u = POP(s)
      if u!= NIL
        ##visita il nodo u
        push(S, u.right)
        push(S, u.left)
'''
Complessità lineare questo qua scusa
