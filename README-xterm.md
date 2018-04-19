# reveal.js + xterm.js

This is reveal.js, with support for bundled xterms!

Run it with:

```
npm install
npm run start
```

Basic usage is in [index.html](./index.html).

Other notes:

- the startup shell /program used is hard-coded in [app.js](./app.js), in the `entrypoint` and
  `args` variables.
- livereload is enabled by default; this can be turned off in [the grunt file](./Gruntfile.js).
- the ESC key **can not** be captured in full-screen mode! Use CTRL-[ if you need to press escape in
  e.g. vim.

Any other basic reveal.js usage can refer to [the main README](./README.md).
