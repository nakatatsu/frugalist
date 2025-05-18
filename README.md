# frugalist

## What is?

> **Status: Work in Progress**  
> This is an unfinished Hugo theme.  
> Feel free to use or modify it under the MIT License, but be aware that its structure, features, and file names may change rapidly as development continues.


## install

```
cd /path/to/your-hugo-site
git submodule add https://github.com/nakatatsu/frugalist.git themes/frugalist

# if neccesary
echo "" >> hugo.toml
echo "theme = 'frugalist'" >> hugo.toml

```

ref: https://gohugo.io/getting-started/quick-start/


## Update

⚠️ WARNING:

Updating the theme can introduce breaking changes. Always backup your site before proceeding.

Never apply updates directly to your production environment without thorough testing.

```
git submodule update --remote --merge
git add themes/frugalist
git commit -m "Update frugalist theme to latest commit"
```
