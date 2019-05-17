# Parcel / Rust

For some reason functions returning Rust Strings show up as `undefined` on the JS side. Not sure why...

## Run

Install parcel bundler globally

```bash
npm i -g parcel-bundler
```

Run parcel in root dir

```bash
parcel index.html
```

The console logs 3 for the function that returns `i32` but `undefined` for the one that returns `String`
