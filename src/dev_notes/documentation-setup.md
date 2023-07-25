# Documentation setup

Install md-book, mdbook-admonish

```
yay -S mdbook
cargo install mdbook-admonish
cd /path/to/Doc
mdbook-admonish install .
```

Run the server

```
mdbook serve --open
```