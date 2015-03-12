# Stream wrapper #

Io.js and nodejs stream wrapper stream. Good companion for coleccionista module.

### Usage ###
```js
let Wrapper = require('stream-wrapper');

let stream = new Wrapper({
    prologue: "This string will be inserted in the begining of the stream",
    epilogue: "This string will be inserted in the end of the stream",
    itemPrologue: "This string will be inserted before every item in the stream",
    itemEpilogue: "This string will be inserted after every item in the stream"
});
// now we can use it like usual stream
stream.pipe(otherStream);

```

