---
title: "Commands"
date: 2022-12-23T14:36:43+01:00
draft: false
---


```bash
sudo apt install hugo
hugo version
hugo new site hugo -f "yaml"
cd hugo/
git init
git branch -m main
git submodule add https://github.com/vantagedesign/ace-documentation.git themes/acedoc
hugo new posts/welcome.md
hugo server -D
git commit -m"first commit"
git remote add origin https://github.com/trulede/hugo.git
git push -u origin main
mkdir -p .github/workflows
touch .github/workflows/gh-pages.yaml
hugo new posts/commands.md
```