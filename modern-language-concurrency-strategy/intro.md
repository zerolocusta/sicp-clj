title: Modern Language Concurrency Strategy
speaker: zero马达
url: https://github.com/zerolocusta
transition: slide3
files: /js/demo.js, /css/demo.css

----
[slide]

# Modern Language Concurrency Strategy

## 现代语言服务器并发策略

### zero马达

----
[slide]

# 使用语言 

- C (然而讲并发并不能没有C)
- Python (3.5)
- Go
- Erlang (抢占式协程)
- Rust
- Clojure

----
[slide]

# 并发逻辑的载体

- multiprocessing
- multithreading
- coroutine

----
[slide]

# 基本并发/并行服务器

----
[slide]

##fork/0

```
#include "unp.h"
    Bind(listenfd, (SA *) &servaddr, sizeof(servaddr));
    Listen(listenfd, LISTENQ);
```

----
[slide]

```
```

----
[slide]
# 并发模型
## 用于处理并发逻辑之间的通信
#### 这次就讲三件小事


1. STM
2. Actor
3. CSP

----
[slide]



----
[slide]

##hello