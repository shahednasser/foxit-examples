# Examples of PDF Manipulation Features with Foxit

This repository includes the code for some examples of PDF manipulation features that are challenging, and how they can be easily implemented with Foxit.

## Running the Examples

Before running the examples, you need to get [Foxit's Web SDK](https://developers.foxitsoftware.com/pdf-sdk). Then, move `lib` and `examples/license-key.js` to `public`.

After that, run:

```bash
npm install
npm start
```

This will start the server at `localhost:3000`.

### Example URLs

1. `http://localhost:3000/examples/reader/without-foxit/`: PDF reader without using Foxit's SDK.
2. `http://localhost:3000/examples/reader/with-foxit/`: PDF reader using Foxit's SDK.
3. `http://localhost:3000/examples/annotations/`: Annotations examples using Foxit's SDK.
4. `http://localhost:3000/examples/digital-signature/`: Digital Signature Example using Foxit's SDK.
