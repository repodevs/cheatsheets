:)

---

## Notes

`h2` supports these:

    {: .-two-column}
    {: .-three-column}
    {: .-left-reference}

`h3` supports these:

    {: .-prime}

`table` supports these:

    {: .-shortcuts}
    {: .-left-align}
    {: .-headers}

`pre` supports these:

    {: .-setup}

`ul` supports these:

    {: .-also-see}
    {: .-four-column}
    {: .-six-column}

Each sheet supports these metadata:

```yml
---
title: React.js
category: React
layout: 2017/sheet   # 'default' | '2017/sheet'
ads: false           # Add this to disable ads
updated: 201708      # To show in the updated list (update _config.yml)
---
```

## Setting up redirects

This example sets up a redirect from `es2015` to `es6`:

```yml
# /es2015.md
---
title: ES2015
category: Hidden
redirect_to: /es6
---
```
