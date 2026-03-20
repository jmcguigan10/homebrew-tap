# homebrew-tap

This is the local tap repo for Machinator.

## Layout

```text
Formula/
  machinator.rb
```

## Local Test Install

With a locally-built Machinator release tarball in place:

```bash
brew tap jmcguigan10/tap /Users/johnny/Projects/homebrew-tap
brew install jmcguigan10/tap/machinator
```

Then verify:

```bash
$(brew --prefix)/bin/macht --help
```

## Public GitHub Tap Shape

When you publish this repo to GitHub, the expected model is:

```bash
brew tap jmcguigan10/tap
brew install machinator
```

That implies a GitHub repository named `homebrew-tap` and a formula in `Formula/machinator.rb`.
