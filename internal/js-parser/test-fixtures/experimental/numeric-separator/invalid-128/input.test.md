# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > numeric-separator > invalid-128`

### `ast`

```javascript
JSRoot {
	body: [
		JSBlockStatement {
			body: [
				JSExpressionStatement {
					expression: JSNumericLiteral {
						value: 11.11
						loc: SourceLocation experimental/numeric-separator/invalid-128/input.js 1:1-1:9
					}
					loc: SourceLocation experimental/numeric-separator/invalid-128/input.js 1:1-1:9
				}
			]
			directives: []
			loc: SourceLocation experimental/numeric-separator/invalid-128/input.js 1:0-1:10
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Invalid or unexpected int token"}
			}
			location: {
				language: "js"
				path: UIDPath<experimental/numeric-separator/invalid-128/input.js>
				end: Position 1:1
				start: Position 1:1
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<experimental/numeric-separator/invalid-128/input.js>
	loc: SourceLocation experimental/numeric-separator/invalid-128/input.js 1:0-2:0
}
```

### `diagnostics`

```

 experimental/numeric-separator/invalid-128/input.js:1:1 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid or unexpected int token

    {1_1_.1_1}
     ^


```
