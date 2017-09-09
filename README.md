# Steem White Paper

Welcome to the Steem White Paper repository!
This repository used for translation of Steem White Paper and connected to GitBook, all changes automatically build into: https://www.gitbook.com/book/bookchain/steem-whitepaper

# Compiling Steem White Paper Guide

Original source of **Steem White Paper** located here: https://github.com/steemit/whitepaper
In order to compile it from **LaTeX** use [**Pandoc 1.19.2.1**](https://pandoc.org) or latter and folowing command:
```
pandoc -s src/whitepaper.tex --to=markdown_mmd --atx-headers --wrap=none -o SteemWhitePaper.md
```

# Translation Guide

[![Crowdin](https://d322cqt584bo4o.cloudfront.net/steem-whitepaper/localized.svg)](https://crowdin.com/project/steem-whitepaper)

If you want to add new language, review/update existing translation or help to finish specific translations, you can join and do that by following link:
https://crowdin.com/project/steem-whitepaper
