### Compare and create release notes

This extension will find all the pull requests in a comparison and output a breif release note based on the title, author and a set of predetermined labels.

`"visible", "not yet visible", "not visible", "bug", "other", "performance", "security", "dependencies"`

If the author `is_bot`, then author name is "Bot".

## Install

```bash
gh extension install DanMegaGamer/gh-pr-summary
```

## Update

```bash
gh extension upgrade DanMegaGamer/gh-pr-summary
```

## Use
In the repo you want to make the comparison.


```bash
gh pr-summary df7f9309...1d5ab425
```
