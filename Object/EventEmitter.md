
# EventEmitter

Object

## Class: EventEmitter

```js

// const EventEmitter = require('events').EventEmitter;
const EventEmitter = require('events');

class MyEmitter extends EventEmitter {}

const myEmitter = new MyEmitter();
```

### member

|       method        |                   Node.js v7             |               fibjs               |
|---------------------|------------------------------------------|-----------------------------------|
| addListener         | addListener(eventName, listener)         | Object addListener(ev, func)      |
| addListener         |                                          | Object addListener(map={})        |
| emit                | emit(eventName[, ...args])               | Boolean emit(ev,...)              |
| eventNames          | eventNames()                             | Array eventNames()                |
| getMaxListeners     | getMaxListeners()                        | Integer getMaxListeners()         |
| listeners           | listeners(eventName)                     | Array listeners(ev)               |
| on                  | on(eventName, listener)                  | Object on( ev, func)              |
| on                  |                                          | Object on(map={})                 |
| once                | once(eventName, listener)                | Object once(ev, func)             |
| once                |                                          | Object once(Object map)           |
| prependListener     | prependListener(eventName, listener)     | Object prependListener(ev, func)  |
| prependListener     |                                          | Object prependListener(map = {})  |
| prependOnceListener | prependOnceListener(eventName, listener) | Object prependOnceListener(ev, func) |
| prependOnceListener |                                          | Object prependOnceListener(map = {}) |
| removeAllListeners  | removeAllListeners([eventName])          | Object removeAllListeners(evs=[]) |
| removeListener      | removeListener(eventName, listener)      | Object removeListener(ev, func)   |
| removeListener      |                                          | Object removeListener(ev)         |
| removeListener      |                                          | Object removeListener(map={})     |
| setMaxListeners     | setMaxListeners(n)                       | setMaxListeners(Integer n)        |
| off                 |                                          | Object off(ev, func)              |
| off                 |                                          | Object off(ev)                    |
| off                 |                                          | Object off(map={})                |
| listenerCount       | listenerCount(eventName)                 | Integer listenerCount(String ev)  |

### static

|     property       |      Node.js v7     |          fibjs      |
|--------------------|---------------------|---------------------|
|defaultMaxListeners | defaultMaxListeners | defaultMaxListeners |

### Event

|       Event   |   Node.js v7   |      fibjs     |
|---------------|----------------|----------------|
|newListener    | newListener    | newListener    |
|removeListener | removeListener | removeListener |
