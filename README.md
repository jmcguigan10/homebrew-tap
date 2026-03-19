# homebrew-tap

This is the local tap repo for Machinate.

## Layout

```text
Formula/
  machinate.rb
```

## Local Test Install

With a locally-built Machinate release tarball in place:

```bash
brew install --build-from-source /Users/johnny/Projects/homebrew-tap/Formula/machinate.rb
```

Then verify:

```bash
$(brew --prefix)/bin/macht --help
```

## Public GitHub Tap Shape

When you publish this repo to GitHub, the expected model is:

```bash
brew tap yourname/tap
brew install machinate
```

That implies a GitHub repository named `homebrew-tap` and a formula in `Formula/machinate.rb`.

