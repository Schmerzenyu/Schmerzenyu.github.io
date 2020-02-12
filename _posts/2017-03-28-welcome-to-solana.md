---
title: 类重写hashCode()和equals()的重要性
teaser: 未重写hashCode()和equals()，导致List的removeAll()方法未得到预期。
category: tehnique
tags: [hashCode, equals, List]
---

GitHub Pages uses a Markdown engine called <dfn>kramdown</dfn> for formatting text posts. kramdown is a superset of Markdown, meaning:

1. anything that’s valid Markdown is also valid kramdown, and
2. it provides and strictly specifies a number of features that are not available in Markdown.[^1] 

Consult the official [kramdown syntax reference][kds] for an exhaustive list of features and how to use them.

---

[^1]:
    Such as footnotes.

[kd]: http://kramdown.gettalong.org/
[rd]: https://github.com/davidfstr/rdiscount
[rc]: https://github.com/vmg/redcarpet
[kds]: https://kramdown.gettalong.org/syntax.html
