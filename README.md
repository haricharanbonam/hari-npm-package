

---

````markdown
# 📦 can-build-string

Check if a target string can be built from the letters of a source string, with optional case-insensitivity.

Perfect for anagram games, word puzzles, or validating character availability in text processing.

---

## ✨ Features

- Tiny utility function: **just one simple export**
- Checks if a string can be formed from letters of another
- Optional case-insensitive mode
- Zero dependencies

---

## 🚀 Installation

```bash
npm install can-build-string
````

or

```bash
yarn add can-build-string
```

---

## 🔧 Usage

```js
import canBuildString from "can-build-string";

console.log(canBuildString("apple", "ppale"));       // true
console.log(canBuildString("apple", "pale"));        // false (missing one 'p')
console.log(canBuildString("Hello", "oLleh"));       // false (case-sensitive by default)
console.log(canBuildString("Hello", "oLleh", true)); // true (ignoreCase: true)
```

---

## 📖 API

### `canBuildString(str, chars, ignoreCase = false)`

| Param        | Type      | Description                              |
| ------------ | --------- | ---------------------------------------- |
| `str`        | `string`  | The string you want to build             |
| `chars`      | `string`  | The source letters you can use           |
| `ignoreCase` | `boolean` | Optional. If true, matches ignoring case |

✅ Returns `true` if `str` can be built from `chars`, else `false`.

---

## 📦 License

MIT

```

---


```
