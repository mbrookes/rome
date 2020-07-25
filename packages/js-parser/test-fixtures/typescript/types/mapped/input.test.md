# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > mapped`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/types/mapped/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/types/mapped/input.ts"
		end: Object {
			column: 0
			index: 185
			line: 5
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/mapped/input.ts"
				end: Object {
					column: 37
					index: 37
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/mapped/input.ts"
					end: Object {
						column: 37
						index: 37
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "map1"
							loc: Object {
								filename: "typescript/types/mapped/input.ts"
								end: Object {
									column: 36
									index: 36
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/mapped/input.ts"
									end: Object {
										column: 36
										index: 36
										line: 1
									}
									start: Object {
										column: 4
										index: 4
										line: 1
									}
								}
								typeAnnotation: TSMappedType {
									optional: undefined
									readonly: undefined
									loc: Object {
										filename: "typescript/types/mapped/input.ts"
										end: Object {
											column: 36
											index: 36
											line: 1
										}
										start: Object {
											column: 10
											index: 10
											line: 1
										}
									}
									typeAnnotation: TSNumberKeywordTypeAnnotation {
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 33
												index: 33
												line: 1
											}
											start: Object {
												column: 27
												index: 27
												line: 1
											}
										}
									}
									typeParameter: TSTypeParameter {
										name: "P"
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 24
												index: 24
												line: 1
											}
											start: Object {
												column: 13
												index: 13
												line: 1
											}
										}
										constraint: TSStringKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/types/mapped/input.ts"
												end: Object {
													column: 24
													index: 24
													line: 1
												}
												start: Object {
													column: 18
													index: 18
													line: 1
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/mapped/input.ts"
							end: Object {
								column: 36
								index: 36
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/mapped/input.ts"
				end: Object {
					column: 47
					index: 85
					line: 2
				}
				start: Object {
					column: 0
					index: 38
					line: 2
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/mapped/input.ts"
					end: Object {
						column: 47
						index: 85
						line: 2
					}
					start: Object {
						column: 0
						index: 38
						line: 2
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "map2"
							loc: Object {
								filename: "typescript/types/mapped/input.ts"
								end: Object {
									column: 46
									index: 84
									line: 2
								}
								start: Object {
									column: 4
									index: 42
									line: 2
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/mapped/input.ts"
									end: Object {
										column: 46
										index: 84
										line: 2
									}
									start: Object {
										column: 4
										index: 42
										line: 2
									}
								}
								typeAnnotation: TSMappedType {
									optional: true
									readonly: true
									loc: Object {
										filename: "typescript/types/mapped/input.ts"
										end: Object {
											column: 46
											index: 84
											line: 2
										}
										start: Object {
											column: 10
											index: 48
											line: 2
										}
									}
									typeAnnotation: TSNumberKeywordTypeAnnotation {
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 43
												index: 81
												line: 2
											}
											start: Object {
												column: 37
												index: 75
												line: 2
											}
										}
									}
									typeParameter: TSTypeParameter {
										name: "P"
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 33
												index: 71
												line: 2
											}
											start: Object {
												column: 22
												index: 60
												line: 2
											}
										}
										constraint: TSStringKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/types/mapped/input.ts"
												end: Object {
													column: 33
													index: 71
													line: 2
												}
												start: Object {
													column: 27
													index: 65
													line: 2
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/mapped/input.ts"
							end: Object {
								column: 46
								index: 84
								line: 2
							}
							start: Object {
								column: 4
								index: 42
								line: 2
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/mapped/input.ts"
				end: Object {
					column: 49
					index: 135
					line: 3
				}
				start: Object {
					column: 0
					index: 86
					line: 3
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/mapped/input.ts"
					end: Object {
						column: 49
						index: 135
						line: 3
					}
					start: Object {
						column: 0
						index: 86
						line: 3
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "map3"
							loc: Object {
								filename: "typescript/types/mapped/input.ts"
								end: Object {
									column: 48
									index: 134
									line: 3
								}
								start: Object {
									column: 4
									index: 90
									line: 3
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/mapped/input.ts"
									end: Object {
										column: 48
										index: 134
										line: 3
									}
									start: Object {
										column: 4
										index: 90
										line: 3
									}
								}
								typeAnnotation: TSMappedType {
									optional: "+"
									readonly: "+"
									loc: Object {
										filename: "typescript/types/mapped/input.ts"
										end: Object {
											column: 48
											index: 134
											line: 3
										}
										start: Object {
											column: 10
											index: 96
											line: 3
										}
									}
									typeAnnotation: TSNumberKeywordTypeAnnotation {
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 45
												index: 131
												line: 3
											}
											start: Object {
												column: 39
												index: 125
												line: 3
											}
										}
									}
									typeParameter: TSTypeParameter {
										name: "P"
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 34
												index: 120
												line: 3
											}
											start: Object {
												column: 23
												index: 109
												line: 3
											}
										}
										constraint: TSStringKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/types/mapped/input.ts"
												end: Object {
													column: 34
													index: 120
													line: 3
												}
												start: Object {
													column: 28
													index: 114
													line: 3
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/mapped/input.ts"
							end: Object {
								column: 48
								index: 134
								line: 3
							}
							start: Object {
								column: 4
								index: 90
								line: 3
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/mapped/input.ts"
				end: Object {
					column: 48
					index: 184
					line: 4
				}
				start: Object {
					column: 0
					index: 136
					line: 4
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/mapped/input.ts"
					end: Object {
						column: 48
						index: 184
						line: 4
					}
					start: Object {
						column: 0
						index: 136
						line: 4
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "map4"
							loc: Object {
								filename: "typescript/types/mapped/input.ts"
								end: Object {
									column: 47
									index: 183
									line: 4
								}
								start: Object {
									column: 4
									index: 140
									line: 4
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/mapped/input.ts"
									end: Object {
										column: 47
										index: 183
										line: 4
									}
									start: Object {
										column: 4
										index: 140
										line: 4
									}
								}
								typeAnnotation: TSMappedType {
									optional: "-"
									readonly: "-"
									loc: Object {
										filename: "typescript/types/mapped/input.ts"
										end: Object {
											column: 47
											index: 183
											line: 4
										}
										start: Object {
											column: 10
											index: 146
											line: 4
										}
									}
									typeAnnotation: TSNumberKeywordTypeAnnotation {
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 45
												index: 181
												line: 4
											}
											start: Object {
												column: 39
												index: 175
												line: 4
											}
										}
									}
									typeParameter: TSTypeParameter {
										name: "P"
										loc: Object {
											filename: "typescript/types/mapped/input.ts"
											end: Object {
												column: 34
												index: 170
												line: 4
											}
											start: Object {
												column: 23
												index: 159
												line: 4
											}
										}
										constraint: TSStringKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/types/mapped/input.ts"
												end: Object {
													column: 34
													index: 170
													line: 4
												}
												start: Object {
													column: 28
													index: 164
													line: 4
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/mapped/input.ts"
							end: Object {
								column: 47
								index: 183
								line: 4
							}
							start: Object {
								column: 4
								index: 140
								line: 4
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