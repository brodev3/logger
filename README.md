# logger


<p>
      <img src="https://i.ibb.co/3sHQCSp/av.jpg" >
</p>

<p >
   <img src="https://img.shields.io/badge/build-v_1.0-brightgreen?label=Version" alt="Version">
</p>





## About

A simple logger by bro.dev. Supports message types: **info**, **debug**, **warn**, **success**, **fail**, **error**. The log entry is also duplicated in the txt logs file. Each entry contains the time, the type of message and the corresponding color, the text of the message. Messages with the debug type are output only to a file.

```javascript
const log = require("./logger")

log.success("hello")
log.info("hello")
log.warn("hello")
log.fail("hello")
log.debug("hello")
log.error("hello")
```


<p align="center">
      <img src="https://i.ibb.co/f9jRRhf/photo-2024-05-05-04-55-52.jpg" >
</p>


## License

Project **brodev3**/logger is distributed under the MIT license.
