# Alden for Homebrew

Standalone builds of [Alden](https://getalden.dev), the review companion that knows what you look for. No Node needed.

```sh
brew install getalden/tap/alden
```

Then:

```sh
alden auth login
alden queue
```

The binaries and `Formula/alden.rb` are published here by Alden's release workflow; each release lists its checksums
in `SHA256SUMS`. Please don't edit the formula by hand.

Problems? Run `alden doctor`, then see [the troubleshooting guide](https://getalden.dev/docs/troubleshooting).
