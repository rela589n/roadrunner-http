Simple RoadRunner HTTP server
---

This repository contains very basic RoadRunner configuration that implements
a minimal POC of http server managed by rr process manager.

Install roadrunner:

```shell
./vendor/bin/rr get-binary
```

Run roadrunner server:

```shell
./rr serve
```

Visit `http://0.0.0.0:8008/?name=Yevhen` and see your name there.

