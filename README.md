# nanovms-demo

This is a demo of what I tried in [NanoVMs](https://nanovms.com) using [ops](https://ops.city)

```
$ curl https://ops.city/get.sh -sSfL | sh
$ ops load node_v12.13.0 -p 8083 -f -n -a hi.js
```

In another terminal, I ran

```
$ curl localhost:8083
Hello World
```

Neat!