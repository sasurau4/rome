# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0102`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "esprima/invalid-syntax/migrated_0102/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/invalid-syntax/migrated_0102/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Unexpected token, expected "}
						","
					]
				}
			}
			location: Object {
				filename: "esprima/invalid-syntax/migrated_0102/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 8
					line: 1
				}
				start: Object {
					column: 7
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/invalid-syntax/migrated_0102/input.js"
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0102/input.js"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				left: JSAssignmentIdentifier {
					name: "p"
					loc: Object {
						filename: "esprima/invalid-syntax/migrated_0102/input.js"
						identifierName: "p"
						end: Object {
							column: 1
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				right: JSBinaryExpression {
					operator: "/"
					loc: Object {
						filename: "esprima/invalid-syntax/migrated_0102/input.js"
						end: Object {
							column: 10
							line: 1
						}
						start: Object {
							column: 4
							line: 1
						}
					}
					right: JSReferenceIdentifier {
						name: "INVALID_PLACEHOLDER"
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0102/input.js"
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
					left: JSObjectExpression {
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0102/input.js"
							end: Object {
								column: 7
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						properties: Array [
							JSObjectProperty {
								key: JSStaticPropertyKey {
									value: JSIdentifier {
										name: "q"
										loc: Object {
											filename: "esprima/invalid-syntax/migrated_0102/input.js"
											identifierName: "q"
											end: Object {
												column: 7
												line: 1
											}
											start: Object {
												column: 6
												line: 1
											}
										}
									}
									loc: Object {
										filename: "esprima/invalid-syntax/migrated_0102/input.js"
										end: Object {
											column: 7
											line: 1
										}
										start: Object {
											column: 6
											line: 1
										}
									}
								}
								value: JSReferenceIdentifier {
									name: "q"
									loc: Object {
										filename: "esprima/invalid-syntax/migrated_0102/input.js"
										identifierName: "q"
										end: Object {
											column: 7
											line: 1
										}
										start: Object {
											column: 6
											line: 1
										}
									}
								}
								loc: Object {
									filename: "esprima/invalid-syntax/migrated_0102/input.js"
									end: Object {
										column: 7
										line: 1
									}
									start: Object {
										column: 6
										line: 1
									}
								}
							}
						]
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0102/input.js:1:7 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token, expected ,

    p = { q/ }
           ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
