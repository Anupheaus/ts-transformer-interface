## 1.0.0

- output interface change:
  - type reference from `'User'` to `{ referenceName: 'User' }`
- (for other transformers) export buildInterface(ts.Type, ts.typeChecker)

## 0.1.0

- type supports
  - primitive types
  - array
  - type reference
  - NOT supporting union types as intended for now