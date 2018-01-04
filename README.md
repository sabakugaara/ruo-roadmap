# ruo-roadmap

Roadmap for ruo

## version 2

- [ ] only support node8+
- [ ] using ajv validate schema
- [ ] async bootstrap manage
- [ ] log
- [ ] security
- [ ] support both swagger@2 and swagger@3

## version 1

- [x] add benchmark
```
❯ autocannon -c 100 -d 5 -p 10 "http://localhost:8080/hello?name=abc"
Running 5s test @ http://localhost:8080/hello?name=abc
100 connections with 10 pipelining factor

Stat         Avg    Stdev   Max
Latency (ms) 110.7  332.8   1583
Req/Sec      800    400     1000
Bytes/Sec    187 kB 93.4 kB 238 kB

4k requests in 5s, 944 kB read
```

- [x] add example hello word

  https://github.com/ruojs/hello

## other frameworks

- [fastify](https://github.com/fastify/fastify) An efficient server implies a lower cost of the infrastructure, a better responsiveness under load and happy users. 
- [nestjs](https://github.com/nestjs/nest) A progressive Node.js framework for building efficient and scalable server-side applications on top of TypeScript & JavaScript (ES6 / ES7 / ES8) heavily inspired by Angular.
- [eggjs](https://github.com/eggjs/egg) Born to build better enterprise frameworks and apps with Node.js & Koa
- [totaljs](https://github.com/totaljs/framework) is a framework for Node.js platfrom written in pure JavaScript similar to PHP's Laravel or Python's Django or ASP.NET MVC. It can be used as web, desktop, service or IoT applicatio
- [ivyjs](https://github.com/ivyjs/framework) with intuitive interface, developing Ivy's nodejs applications is easy and fast.
