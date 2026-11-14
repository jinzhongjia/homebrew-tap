# jinzhongjia/homebrew-tap

Homebrew formulae of [zig-analyzer](https://github.com/jinzhongjia/zig-analyzer), a Zig language server.

```sh
brew install jinzhongjia/tap/zig-analyzer
brew upgrade zig-analyzer
```

The formula installs the ReleaseSafe build of the latest release on macOS and Linux (x86_64 and aarch64). zig-analyzer needs Zig 0.17.0 or 0.17.1 in `PATH`.

`Formula/zig-analyzer.rb` is written by `zig build homebrew-formula` (`tools/homebrew_formula.zig`) in the zig-analyzer repository, and the release workflow there commits it for each release. Change the tool, not the formula.
