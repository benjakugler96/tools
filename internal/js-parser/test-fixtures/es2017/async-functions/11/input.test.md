# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > 11`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2017/async-functions/11/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2017/async-functions/11/input.js"
		end: Object {
			column: 17
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2017/async-functions/11/input.js"
				end: Object {
					column: 5
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "async"
				loc: Object {
					filename: "es2017/async-functions/11/input.js"
					identifierName: "async"
					end: Object {
						column: 5
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
		}
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "foo"
				loc: Object {
					filename: "es2017/async-functions/11/input.js"
					identifierName: "foo"
					end: Object {
						column: 12
						line: 2
					}
					start: Object {
						column: 9
						line: 2
					}
				}
			}
			loc: Object {
				filename: "es2017/async-functions/11/input.js"
				end: Object {
					column: 17
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2017/async-functions/11/input.js"
					end: Object {
						column: 17
						line: 2
					}
					start: Object {
						column: 15
						line: 2
					}
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2017/async-functions/11/input.js"
					end: Object {
						column: 14
						line: 2
					}
					start: Object {
						column: 12
						line: 2
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