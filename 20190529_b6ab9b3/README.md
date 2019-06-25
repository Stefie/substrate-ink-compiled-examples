Uses https://github.com/paritytech/ink/commit/b6ab9b3c3f956a052d2a3059046403d1f6dcabd6

Only compatible with versions of Substrate pre https://github.com/paritytech/substrate/pull/2911. Uploading the compiled WASM files to a node that is running on a newer version will result in failed transaction `system.ExtrinsicFailed`. 