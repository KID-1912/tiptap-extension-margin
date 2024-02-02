# tiptap-extension-margin

<h3 align="center">
    An extension that add margin to tiptap paragraph or more nodes.
</h3>

<br/>

<p align="center">
  <a marginef="https://www.npmjs.com/package/tiptap-extension-margin">
    <img
     alt="NPM URL"
     src="https://img.shields.io/badge/npm-tiptapExtensionMargin?logo=npm">
  </a>
  <img
     alt="version"
     src="https://img.shields.io/badge/version-1.0.0-blue">
</p>

<br>

---

## Install

```shell
npm install tiptap-extension-margin -S
```

## Usage

```js
import Margin from "tiptap-extension-margin";

const editor = new Editor({
  element: document.querySelector(".editor"),
  extensions: [StarterKit, Margin],
});

// { top, bottom, left, right }
editor.chain().focus().setMargin({ top: "10px" }).run();
```

## Relations

**tiptap:** https://tiptap.dev/

**tiptap-appmsg-editor:** https://github.com/KID-1912/tiptap-appmsg-editor
