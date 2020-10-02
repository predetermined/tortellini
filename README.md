# Tortellini 🥟
Tortellini is a minimal code editor written in TypeScript.

## Features
- Syntax highlighting
- Code completion

## Example Usage
```typescript
import { Tortellini } from "tortellini";
                         // https://unpkg.com/tortellini/index.js

const editor = new Tortellini(
    document.querySelector("[data-editor]"),
    "javascript"
);
```

## Options
```typescript
// new Tortellini(element, language, options);
//                                   ^
const options = {
    //                  Default
    caretColor:         "#fff", // Provide a CSS color data type value
    indentionSize:      4
}
```
### Supported Languages
* JavaScript `javascript`
* HTML `html` (Experimental)
* CSS `css`

## Instance functions
```typescript
const editor = new Tortellini(/* ... */);

editor.code       // Get the written code
editor.remove();  // Reset the base element
```
