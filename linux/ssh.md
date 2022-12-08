# `ssh`

Set up an SHH tunnel. Connections made to the local machine on port 9229 will
be forwarded to port 9230 on the remote machine (test.foovpc.com).

```
ssh -4 -L 9229:localhost:9230 test.foovpc.com
```
