# Setup

```bash
# Firstly, you need to install hugo, ref: https://gohugo.io/getting-started/installing/#quick-install

# clone with submodules
git clone --recurse-submodules -j8 https://github.com/dwlab/website.git
```


# Run

```bash
hugo server
```

# Modify Content

edit `config.toml` or update `themes/elate`.

> elate is a submodule ref to another repo https://github.com/dwlab/hugo-elate-theme which forked from `hugo-elate-theme`,
> if you changed any files in `themes/elate`, don't forget to commit and push changes to https://github.com/dwlab/hugo-elate-theme.

# deploy

```bash
sh ./deploy.sh
```