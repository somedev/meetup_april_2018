footer: **iOS projects code formatting** - Eduard Panasiuk - https://github.com/somedev

#iOS projects code formattings
### Eduard Panasiuk

---

#Tools

* [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html)

* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat)

---

#ClangFormat

---

#ClangFormat

[https://clang.llvm.org/docs/ClangFormat.html](https://clang.llvm.org/docs/ClangFormat.html)
<br>
**Instalation:**

```bash
brew install clang-format
```
**Usage:**

```bash
clang-format -style=file ./MyClass.m
```

---

#ClangFormat options

[https://clang.llvm.org/docs/ClangFormatStyleOptions.html](https://clang.llvm.org/docs/ClangFormatStyleOptions.html)   

![inline](img/format-sample.png)

---

#ClangFormat predefined styles

<br>

**LLVM**, **Google**, **Chromium**, **Mozilla**, **WebKit**

<br>

**Dump predefined style:**

```bash
clang-format -style=llvm -dump-config > .clang-format
```

---

#ClangFormat options

[https://clangformat.com/](https://clangformat.com/)

![inline](img/clangformat.com.png)

---

#SwiftFormat

---