# NGINX

```

                          +--- >> localhost:8000 >> -------- >> https://awesome.com
                          |
                          +--- >> localhost:8001 >> -------- >> https://awesome.com/a
                          |
                          +--- >> localhost:8002 >> -------- >> https://awesome.com/b
                          |
                          +--- >> localhost:8003 >> -------- >> https://awesome.com/c
                          |
[Server] -->> [Nginx] -->>|--- >> localhost:8004 >> -------- >> https://awesome.com/d
                          |
                          +--- >> localhost:8005 >> -------- >> https://awesome.com/e
                          |
                          +--- >> localhost:8006 >> -------- >> https://awesome.com/f
                          |
                          +--- >> localhost:8007 >> -------- >> https://awesome.com/g

```
