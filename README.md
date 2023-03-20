# Piarre's snippetypescript

Basic TypeScript snippetypescript for me (or you).

## Features

### Variables

Typed constant

```typescript
const MyConstant: any = null;
```

Export typed constant

```typescript
export const MyConstant: any = null;
```

Export constant

```typescript
export const MyConstant = null;
```

Typed variable

```typescript
let|var MyVariable: any = null;
```

Exported typed variable

```typescript
export let|var MyVariable: any = null;
```

Exported variable

```typescript
export let|var MyVariable = null;
```

### Interface

```typescript
interface MyInterface {}
```

### Type

```typescript
type MyType = any;
```

---

## Functions

Simple function

```typescript
function MyFunction(param: any) {}
```

Exported function

```typescript
export function MyExportedFunction(parma: any) {}
```

Default export function

```typescript
default export function MyDefaultExportedFunction(parma: any) {}
```

## Classes

Simple class

```typescript
class MyClass {}
```

Exported class #1

```typescript
export class MyExportedClass {}
```

Exported class #2

```typescript
class MyExportedClass {}

export MyExportedClass;
```

Default exported class #1

```typescript
export default class MyDefaultExportedClass {}
```

Default exported class #2

```typescript
class MyDefaultExportedClass {}

export default MyDefaultExportedClass;
```
