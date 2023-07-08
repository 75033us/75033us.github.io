# 75033us.github.io

This is the source repo for [https://75033us.github.io](https://75033us.github.io).

# Setup on MacOS

```
# install toolchain
brew install ruby@3.1

# fix .zshrc for the PATH
echo 'export PATH="/opt/homebrew/opt/node@18/bin:$PATH"' >> ~/.zshrc

# install dependencies
make install
```

# Build and View

The static pages will be published under _site/

```
# build only
make build
```

Display the website locally at [http://127.0.0.1:4000](http://127.0.0.1:4000)
```
make serve
```