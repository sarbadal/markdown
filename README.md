# Advanced Markdown

## Table of Contents
<!-- AUTO-GENERATED-CONTENT:START (TOC:collapse=true&collapseText="Click to expand") -->
<details>
<summary>Click to expand</summary>

- [Why markdown?](#why-markdown)
- [Markdown basics](#markdown-basics)
- [Advanced Formatting tips](#advanced-formatting-tips)
  * [`left` alignment](#left-alignment)
  * [`right` alignment](#right-alignment)
  * [`center` alignment example](#center-alignment-example)
  * [`collapse` Sections](#collapse-sections)
  * [`additional links`](#additional-links)
  * [Badges](#badges)
- [Useful packages](#useful-packages)
- [Useful utilities](#useful-utilities)
- [How Serverless uses markdown](#how-serverless-uses-markdown)
  * [DEMO](#demo)
- [Other Markdown Resources](#other-markdown-resources)

</details>
<!-- AUTO-GENERATED-CONTENT:END -->



## Why markdown?

Markdown is a universal doc format that is easy to write and easy to add to a version control system.

- **Open** - Anyone can submit content, fix typos & update anything via pull requests
- **Version control** - Roll back & see the history of any given post
- **No CMS lock in** - We can easily port to any static site generator
- **It's just simple** - No user accounts to manage, no CMS software to upgrade, no plugins to install.

---

## Markdown basics

The basics of markdown can be found [here](https://guides.github.com/features/mastering-markdown/) & [here](https://daringfireball.net/projects/markdown/). Super easy!

## Advanced Formatting tips

### `left` alignment

<img align="left" width="100" height="100" style="padding-left:0px; padding-right:10px" src="./img/4AiXzf8.jpg">

This is the code you need to align images to the left. This image is in img folder.
```
<img align="left" width="100" height="100" src="./img/4AiXzf8.jpg">

```
---

### `right` alignment

<img align="right" width="100" height="100" style="padding-left:10px" src="./img/4AiXzf8.jpg">

This is the code you need to align images to the right:
```
<img align="right" width="100" height="100" style="padding-left:10px" src="./img/4AiXzf8.jpg">
```
---

### `center` alignment example

<img align="center" width="200" height="200" style="padding-button:10px" src="./img/4AiXzf8.jpg">

```
<img align="center" width="200" height="200" style="padding-button:10px" src="./img/4AiXzf8.jpg">
```
---

### `collapse` Sections

Collapsing large blocks of text can make your markdown much easier to digest

<details>
<summary>"Click to expand"</summary>
this is hidden block
</details>

```
<details>
<summary>"Click to expand"</summary>
this is hidden
</details>
```

Collapsing large blocks of Markdown text

<details>
<summary>To make sure markdown is rendered correctly in the collapsed section...</summary>

 1. Put an **empty line** after the `<summary>` block.
 2. *Insert your markdown syntax*
 3. Put an **empty line** before the `</details>` tag
 
</details>

```
<details>
<summary>To make sure markdown is rendered correctly in the collapsed section...</summary>

 1. Put an **empty line** after the `<summary>` block.
 2. *Insert your markdown syntax*
 3. Put an **empty line** before the `</details>` tag
 
</details>
```
---

### `additional links`

• [YouTube](https://www.youtube.com/channel/UC7-1qj3Z56z7mS4boZAzz7g) • [Facebook](https://www.facebook.com/bongcodesdjango)

```
• [YouTube](https://www.youtube.com/channel/UC7-1qj3Z56z7mS4boZAzz7g) • [Facebook](https://www.facebook.com/bongcodesdjango)
```
---

### Badges

I hate them so. Don't use badges.

---