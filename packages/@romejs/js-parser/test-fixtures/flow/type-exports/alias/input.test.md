# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-exports > alias`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 24
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExportLocalDeclaration {
      exportKind: 'type'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 23
          index: 23
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: TypeAliasTypeAnnotation {
        id: BindingIdentifier {
          name: 'a'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 13
              index: 13
              line: 1
            }
            start: Object {
              column: 12
              index: 12
              line: 1
            }
          }
        }
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 23
            index: 23
            line: 1
          }
          start: Object {
            column: 7
            index: 7
            line: 1
          }
        }
        right: NumberKeywordTypeAnnotation {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 22
              index: 22
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
        }
      }
    }
  ]
}
```