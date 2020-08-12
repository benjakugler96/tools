# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > 18`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "jsx/basic/18/input.jsx"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array ["jsx"]
	loc: Object {
		filename: "jsx/basic/18/input.jsx"
		end: Object {
			column: 35
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "jsx/basic/18/input.jsx"
				end: Object {
					column: 35
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSXElement {
				name: JSXIdentifier {
					name: "div"
					loc: Object {
						filename: "jsx/basic/18/input.jsx"
						end: Object {
							column: 4
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
				}
				children: Array []
				selfClosing: true
				typeArguments: undefined
				loc: Object {
					filename: "jsx/basic/18/input.jsx"
					end: Object {
						column: 35
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				attributes: Array [
					JSXSpreadAttribute {
						loc: Object {
							filename: "jsx/basic/18/input.jsx"
							end: Object {
								column: 15
								line: 1
							}
							start: Object {
								column: 5
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "props"
							loc: Object {
								filename: "jsx/basic/18/input.jsx"
								identifierName: "props"
								end: Object {
									column: 14
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
					}
					JSXAttribute {
						name: JSXIdentifier {
							name: "post"
							loc: Object {
								filename: "jsx/basic/18/input.jsx"
								end: Object {
									column: 20
									line: 1
								}
								start: Object {
									column: 16
									line: 1
								}
							}
						}
						value: JSStringLiteral {
							value: "attribute"
							loc: Object {
								filename: "jsx/basic/18/input.jsx"
								end: Object {
									column: 32
									line: 1
								}
								start: Object {
									column: 21
									line: 1
								}
							}
						}
						loc: Object {
							filename: "jsx/basic/18/input.jsx"
							end: Object {
								column: 32
								line: 1
							}
							start: Object {
								column: 16
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```