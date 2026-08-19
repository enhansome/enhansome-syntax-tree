<!--lint disable no-html maximum-line-length-->

# awesome syntax-tree with stars

[<img align="right" alt src="https://raw.githubusercontent.com/syntax-tree/unist/1310d30/logo-square.svg?sanitize=true" width="200">](https://unifiedjs.com)

> A curated list of awesome syntax-tree,
> **[unist][]**,
> **[mdast][]** (markdown),
> **[hast][]** (HTML),
> **[xast][]** (XML),
> **[esast][]** (JS),
> and **[nlcst][]** (prose) resources.

**syntax-tree** is an organization housing **[unist][]** and its main
implementations **[mdast][]**,
**[hast][]**,
**[xast][]**,
**[esast][]**,
and **[nlcst][]**.
**[unist][]** is a specification for syntax trees that comes with a big
ecosystem of utilities in JavaScript for working with those trees.
On top of **[unist][]** and its implementations sits the rest of
**[unified][]** that does all kinds of things to process content.

## Contents

* [Official](#official)
* [unist utilities](#unist-utilities)
* [mdast utilities](#mdast-utilities)
* [hast utilities](#hast-utilities)
* [xast utilities](#xast-utilities)
* [esast utilities](#esast-utilities)
* [nlcst utilities](#nlcst-utilities)
* [Related lists](#related-lists)
* [License](#license)

## Official

* [unified](https://github.com/unifiedjs/unified) ⭐ 5,021 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-29 - Ecosystem.
* [mdast](https://github.com/syntax-tree/mdast) ⭐ 1,465 | 🐛 0 | 📅 2026-02-04 - **mdast** (markdown) specification.
* [unist](https://github.com/syntax-tree/unist) ⭐ 1,010 | 🐛 0 | 📅 2026-06-01 - **unist** specification.
* [hast](https://github.com/syntax-tree/hast) ⭐ 905 | 🐛 0 | 📅 2025-02-17 - **hast** (HTML) specification.
* [nlcst](https://github.com/syntax-tree/nlcst) ⭐ 233 | 🐛 0 | 📅 2024-10-04 - **nlcst** (prose) specification.
* [xast](https://github.com/syntax-tree/xast) ⭐ 93 | 🐛 0 | 📅 2024-10-04 - **xast** (XML) specification.
* [esast](https://github.com/syntax-tree/esast) ⭐ 58 | 🐛 0 | 📅 2024-10-04 - **esast** (JS) specification.
* [syntax-tree](https://github.com/syntax-tree) - Organization.
* [unifiedjs.com](https://unifiedjs.com) - Ecosystem website.

## unist utilities

* [unist-util-visit](https://github.com/syntax-tree/unist-util-visit) ⭐ 353 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-22 - Visit nodes.
* [unist-builder](https://github.com/syntax-tree/unist-builder) ⭐ 81 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-07 - Create trees with a nice syntax.
* [unist-util-select](https://github.com/syntax-tree/unist-util-select) ⭐ 70 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-09 - Select nodes with CSS-like selectors.
* [unist-util-is](https://github.com/syntax-tree/unist-util-is) ⭐ 45 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-22 - Check if a node passes a test.
* [unist-util-map](https://github.com/syntax-tree/unist-util-map) ⭐ 35 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-07 - Create a new tree by mapping all nodes.
* [unist-util-inspect](https://github.com/syntax-tree/unist-util-inspect) ⭐ 32 | 🐛 0 | 🌐 JavaScript | 📅 2024-12-05 - Inspect nodes.
* [unist-util-remove](https://github.com/syntax-tree/unist-util-remove) ⭐ 25 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-07 - Remove nodes from a tree.
* [unist-util-filter](https://github.com/syntax-tree/unist-util-filter) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-26 - Create a new tree with nodes that pass a filter.
* [unist-util-assert](https://github.com/syntax-tree/unist-util-assert) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-07 - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/unist#list-of-utilities) ⭐ 1,010 | 🐛 0 | 📅 2026-06-01

## mdast utilities

* [mdast-util-to-hast](https://github.com/syntax-tree/mdast-util-to-hast) ⭐ 123 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-23 - Transform to hast.
* [mdast-util-toc](https://github.com/syntax-tree/mdast-util-toc) ⭐ 88 | 🐛 0 | 🌐 JavaScript | 📅 2024-06-02 - Generate a Table of Contents.
* [mdast-util-to-string](https://github.com/syntax-tree/mdast-util-to-string) ⭐ 46 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-30 - Get the plain text content of a node.
* [mdast-zone](https://github.com/syntax-tree/mdast-zone) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2024-09-05 - Use comments as ranges and markers.
* [mdast-util-definitions](https://github.com/syntax-tree/mdast-util-definitions) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-08 - Find definitions.
* [mdast-util-heading-range](https://github.com/syntax-tree/mdast-util-heading-range) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-07 - Use heading as ranges.
* [mdast-util-to-nlcst](https://github.com/syntax-tree/mdast-util-to-nlcst) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-30 - Transform to nlcst.
* [mdast-normalize-headings](https://github.com/syntax-tree/mdast-normalize-headings) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-07 - Fix heading depths.
* [mdast-util-assert](https://github.com/syntax-tree/mdast-util-assert) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-08 - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/mdast#list-of-utilities) ⭐ 1,465 | 🐛 0 | 📅 2026-02-04

## hast utilities

* [hastscript](https://github.com/syntax-tree/hastscript) ⭐ 200 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-19 - Create trees with a nice syntax.
* [hast-util-to-html](https://github.com/syntax-tree/hast-util-to-html) ⭐ 118 | 🐛 1 | 🌐 JavaScript | 📅 2025-02-19 - Transform to an HTML string.
* [hast-util-to-jsx-runtime](https://github.com/syntax-tree/hast-util-to-jsx-runtime) ⭐ 88 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-05 - Transform to preact, react, solid, svelte, vue, etc.
* [hast-util-sanitize](https://github.com/syntax-tree/hast-util-sanitize) ⭐ 59 | 🐛 2 | 🌐 JavaScript | 📅 2024-10-25 - Sanitize a tree.
* [hast-util-to-mdast](https://github.com/syntax-tree/hast-util-to-mdast) ⭐ 44 | 🐛 0 | 🌐 JavaScript | 📅 2025-01-28 - Transform to mdast.
* [hast-util-select](https://github.com/syntax-tree/hast-util-select) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-19 - `querySelector`, `querySelectorAll`, and `matches`.
* [hast-util-to-text](https://github.com/syntax-tree/hast-util-to-text) ⭐ 25 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-16 - Get plain-text content.
* [hast-util-from-dom](https://github.com/syntax-tree/hast-util-from-dom) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-19 - Transform from a DOM tree.
* [hast-util-to-dom](https://github.com/syntax-tree/hast-util-to-dom) ⭐ 21 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-09 - Transform to a DOM tree.
* [hast-util-is-element](https://github.com/syntax-tree/hast-util-is-element) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-31 - Check if a node is a (certain) element.
* [hast-util-find-and-replace](https://github.com/syntax-tree/hast-util-find-and-replace) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2023-09-21 - Find and replace text in a tree.
* [hast-util-to-nlcst](https://github.com/syntax-tree/hast-util-to-nlcst) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-08 - Transform to nlcst.
* [hast-util-to-xast](https://github.com/syntax-tree/hast-util-to-xast) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-19 - Transform to xast.
* [hast-util-from-text](https://github.com/syntax-tree/hast-util-from-text) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-02 - Set plain-text content.
* [hast-util-has-property](https://github.com/syntax-tree/hast-util-has-property) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-01 - Check if a node has a property.
* [hast-util-assert](https://github.com/syntax-tree/hast-util-assert) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2023-08-01 - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/hast#list-of-utilities) ⭐ 905 | 🐛 0 | 📅 2025-02-17

## xast utilities

* [xast-util-from-xml](https://github.com/syntax-tree/xast-util-from-xml) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-18 - Transform from an XML string.
* [xastscript](https://github.com/syntax-tree/xastscript) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-31 - Create xast trees.
* [xast-util-feed](https://github.com/syntax-tree/xast-util-feed) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-19 - Build a feed (RSS, Atom).
* [xast-util-sitemap](https://github.com/syntax-tree/xast-util-sitemap) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-18 - Build a sitemap.
* [xast-util-to-xml](https://github.com/syntax-tree/xast-util-to-xml) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-18 - Transform to an XML string.

[Find more utilities »](https://github.com/syntax-tree/xast#list-of-utilities) ⭐ 93 | 🐛 0 | 📅 2024-10-04

## esast utilities

* [estree-util-value-to-estree](https://github.com/remcohaszing/estree-util-value-to-estree) ⭐ 25 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-18 - Turn a JavaScript value into an estree expression
* [estree-util-build-jsx](https://github.com/syntax-tree/estree-util-build-jsx) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2024-08-23 - Turn JSX into function calls.
* [estree-util-to-js](https://github.com/syntax-tree/estree-util-to-js) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-31 - Transform to a JavaScript string.
* [esast-util-from-js](https://github.com/syntax-tree/esast-util-from-js) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-31 - Transform from a JavaScript string.
* [estree-util-attach-comments](https://github.com/syntax-tree/estree-util-attach-comments) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-31 - Attach comments to the tree.

[Find more utilities »](https://github.com/syntax-tree/esast#list-of-utilities) ⭐ 58 | 🐛 0 | 📅 2024-10-04

## nlcst utilities

* [nlcst-to-string](https://github.com/syntax-tree/nlcst-to-string) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2024-04-30 - Transform to a string.
* [nlcst-search](https://github.com/syntax-tree/nlcst-search) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-17 - Search for patterns in a tree.
* [nlcst-is-literal](https://github.com/syntax-tree/nlcst-is-literal) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2025-01-03 - Check if a node is meant literally.
* [nlcst-normalize](https://github.com/syntax-tree/nlcst-normalize) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-17 - Normalize a word for easier comparison.
* [nlcst-test](https://github.com/syntax-tree/nlcst-test) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-17 - Assert nodes.

[Find more utilities »](https://github.com/syntax-tree/nlcst#list-of-utilities) ⭐ 233 | 🐛 0 | 📅 2024-10-04

## Related lists

* [awesome remark](https://github.com/remarkjs/awesome-remark) ⭐ 493 | 🐛 2 | 📅 2024-10-03
* [awesome mdx](https://github.com/mdx-js/awesome) ⭐ 334 | 🐛 0 | 📅 2024-10-07
* [awesome rehype](https://github.com/rehypejs/awesome-rehype) ⭐ 237 | 🐛 0 | 📅 2024-10-10
* [awesome unified](https://github.com/unifiedjs/awesome-unified) ⭐ 148 | 🐛 0 | 📅 2024-10-03
* [awesome retext](https://github.com/retextjs/awesome-retext) ⭐ 131 | 🐛 0 | 📅 2024-10-03

## License

[![CC-BY][license-badge]][license] © [Titus Wormer][author]

<!-- Definitions. -->

[author]: https://wooorm.com

[awesome-badge]: https://awesome.re/badge.svg

[esast]: https://github.com/syntax-tree/esast

[hast]: https://github.com/syntax-tree/hast

[license-badge]: https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by.svg

[license]: https://creativecommons.org/licenses/by/4.0/

[mdast]: https://github.com/syntax-tree/mdast

[nlcst]: https://github.com/syntax-tree/nlcst

[self]: https://github.com/remarkjs/awesome-remark

[unified]: https://github.com/unifiedjs/unified

[unist]: https://github.com/syntax-tree/unist

[xast]: https://github.com/syntax-tree/xast

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
