# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2019 > optional-catch-binding > no-binding-finally`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
		end: Object {
			column: 0
			index: 35
			line: 10
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSTryStatement {
			loc: Object {
				filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
				end: Object {
					column: 1
					index: 34
					line: 9
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			block: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
					end: Object {
						column: 1
						index: 8
						line: 3
					}
					start: Object {
						column: 4
						index: 4
						line: 1
					}
				}
			}
			finalizer: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
					end: Object {
						column: 1
						index: 34
						line: 9
					}
					start: Object {
						column: 8
						index: 28
						line: 7
					}
				}
			}
			handler: JSCatchClause {
				param: undefined
				loc: Object {
					filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
					end: Object {
						column: 1
						index: 19
						line: 6
					}
					start: Object {
						column: 0
						index: 9
						line: 4
					}
				}
				body: JSBlockStatement {
					body: Array []
					directives: Array []
					loc: Object {
						filename: "es2019/optional-catch-binding/no-binding-finally/input.js"
						end: Object {
							column: 1
							index: 19
							line: 6
						}
						start: Object {
							column: 6
							index: 15
							line: 4
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```