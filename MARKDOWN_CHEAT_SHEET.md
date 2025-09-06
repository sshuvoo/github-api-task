Markdown Cheat Sheet for Developers

# 🚀 Markdown Cheat Sheet for Developers

---

## 📊 Tables

A table showing npm vs yarn commands:

| Action         | npm Command         | yarn Command      |
| -------------- | ------------------- | ----------------- |
| Install deps   | `npm install`       | `yarn install`    |
| Add a package  | `npm install pkg`   | `yarn add pkg`    |
| Remove package | `npm uninstall pkg` | `yarn remove pkg` |

---

## 💻 Code Blocks

Inline code: `console.log("Hello, Markdown!")`

```typescript
// Example: Utility function
function isEven(n: number): boolean {
  return n % 2 === 0
}

console.log(isEven(4)) // true
console.log(isEven(7)) // false
```

---

## 💡 Tips

* Use `README.md` to guide contributors.
* Add **badges** for build status, license, and npm downloads.
* Keep sections like *Installation*, *Usage*, and *Contributing*.