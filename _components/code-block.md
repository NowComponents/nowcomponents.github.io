---
title:  "Code Block"
author: "Tomas Hrobarikt"
author-username: "hrobarikt"
repo-url: "https://github.com/NowComponents/code-block"
---

A code-block element that can be used for rendering code snippets inside of the HTML. It is using PrismJS for syntax highlighting. Other suggestions for improvement are welcomed 👋

```
<code-block language="javascript" label="demo.js">
import {createCustomElement} from '@servicenow/ui-core';
import snabbdom from '@servicenow/ui-renderer-snabbdom';
import styles from './styles.scss';
import view from "./view";
import codeblockActions from "./actions";

createCustomElement('code-block', {
renderer: {
type: snabbdom
},
properties: {
label: {},
language: {}
},
view,
...codeblockActions,
styles
});
</code-block>
```


![code block screenshot](./assets/images/component-code-block.png)