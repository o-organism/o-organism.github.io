# O-Organism

## How to local

```txt
hugo server --buildDrafts
```

## How to add content

```txt
hugo new content content/posts/YYYY-MM-DD.md
```

Then read [this](https://gohugo.io/getting-started/quick-start/) documentation by hugo.

Then build the drafts start local server.

```txt
hugo server --buildDrafts
```

Happy? => change the draft property in the '.md' files to `false` and publish the site.

```sh
# create static site in public dir
hugo
```

Then push to GitHub.

## How to deploy

[Hugo docs](https://gohugo.io/hosting-and-deployment/hosting-on-github/) on how to set this up.

```sh
# just push to GitHub after completing the deployment setup according to Hugo's docs ^^
```

## How to update

- [hugo](https://gohugo.io/getting-started/quick-start/)

- [papermod INSTALL](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-installation/)

- [papermod FEATURES](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/)

- [papermod FAQ](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-faq/)
