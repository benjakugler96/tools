# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > statement-iteration > migrated_0018`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/statement-iteration/migrated_0018/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/statement-iteration/migrated_0018/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSForInStatement {
			loc: Object {
				filename: "esprima/statement-iteration/migrated_0018/input.js"
				end: Object {
					column: 31
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			right: JSReferenceIdentifier {
				name: "list"
				loc: Object {
					filename: "esprima/statement-iteration/migrated_0018/input.js"
					identifierName: "list"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 14
						line: 1
					}
				}
			}
			left: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "esprima/statement-iteration/migrated_0018/input.js"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 5
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/statement-iteration/migrated_0018/input.js"
								identifierName: "x"
								end: Object {
									column: 10
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "esprima/statement-iteration/migrated_0018/input.js"
							end: Object {
								column: 10
								line: 1
							}
							start: Object {
								column: 9
								line: 1
							}
						}
					}
				]
			}
			body: JSExpressionStatement {
				loc: Object {
					filename: "esprima/statement-iteration/migrated_0018/input.js"
					end: Object {
						column: 31
						line: 1
					}
					start: Object {
						column: 20
						line: 1
					}
				}
				expression: JSCallExpression {
					loc: Object {
						filename: "esprima/statement-iteration/migrated_0018/input.js"
						end: Object {
							column: 30
							line: 1
						}
						start: Object {
							column: 20
							line: 1
						}
					}
					callee: JSReferenceIdentifier {
						name: "process"
						loc: Object {
							filename: "esprima/statement-iteration/migrated_0018/input.js"
							identifierName: "process"
							end: Object {
								column: 27
								line: 1
							}
							start: Object {
								column: 20
								line: 1
							}
						}
					}
					arguments: Array [
						JSReferenceIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/statement-iteration/migrated_0018/input.js"
								identifierName: "x"
								end: Object {
									column: 29
									line: 1
								}
								start: Object {
									column: 28
									line: 1
								}
							}
						}
					]
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