# dekobon/homebrew-tap

Homebrew tap for tools maintained by [@dekobon](https://github.com/dekobon).

## Usage

```sh
brew tap dekobon/tap
brew install <formula>
```

Or install a formula directly without tapping first:

```sh
brew install dekobon/tap/<formula>
```

## Available formulas

| Formula | Description |
| --- | --- |
| [`big-code-analysis`](Formula/big-code-analysis.rb) | Compute maintainability metrics for source code in many languages. |
| [`host-identity`](Formula/host-identity.rb) | Stable host UUID across platforms, clouds, and Kubernetes. |

## Platform support

Bottles are currently published for **Apple Silicon macOS only**. On Intel Macs, install via `cargo install host-identity-cli` or run the aarch64 build under Rosetta 2.

## Updating

Formulas are rendered automatically by the upstream project's release workflow (`.github/workflows/release.yml`) on each `v*` tag — do not edit `Formula/*.rb` by hand.
