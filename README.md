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
brew tap jmcguigan10/tap /Users/johnny/Projects/homebrew-tap
brew install jmcguigan10/tap/machinate
```

Then verify:

```bash
$(brew --prefix)/bin/macht --help
```

## Public GitHub Tap Shape

When you publish this repo to GitHub, the expected model is:

```bash
brew tap jmcguigan10/tap
brew install machinate
```

That implies a GitHub repository named `homebrew-tap` and a formula in `Formula/machinate.rb`.
