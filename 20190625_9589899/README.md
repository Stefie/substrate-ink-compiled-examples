### Uses https://github.com/paritytech/ink/commit/9589899b5630c42870de24b0fdb9e67587531f70

### Major Change
The major change that required a new folder with compiled contract files was the switch from using scratch buffer instead of input buffer.

See https://github.com/paritytech/ink/pull/129.

That is why the compiled code is only compatible with versions of Substrate post https://github.com/paritytech/substrate/pull/2911. Uploading the compiled WASM files to a node that is running on an older version can cause problems. 