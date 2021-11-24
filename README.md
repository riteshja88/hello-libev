# hello-libev
```
$:~/hello-libev$gcc hello-libev.c  -lev                                                                      │host:~$nc localhost 3033
$:~/hello-libev$./a.out                                                                                      │hi from client1
message:hi from client1                                                                                                        │hi from client1
message:hi from client2                                                                                                        │how are you?
message:how are you?                                                                                                           │how are you?
message:how are you from client2?                                                                                              │bye from clent1
message:bye from client2                                                                                                       │bye from clent1
message:bye from clent1                                                                                                        │^C
peer might closing: Success                                                                                                    │host:~$
peer might closing: Success                                                                                                    │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               ├──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
                                                                                                                               │host:~$nc localhost 3033
                                                                                                                               │hi from client2
                                                                                                                               │hi from client2
                                                                                                                               │how are you from client2?
                                                                                                                               │how are you from client2?
                                                                                                                               │bye from client2
                                                                                                                               │bye from client2
                                                                                                                               │^C
                                                                                                                               │host:~$
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
                                                                                                                               │
```
