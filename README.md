# tgstation-native-deps-nix

Nix flake to compile tgstation's native dependencies, currently `librust-g` and `libdreamluau`. `libauxcpu` support may be added in the future, along with other dependencies.

Currently a WIP until I figure out how to work out flake inputs

# Running the flake

Run `nix build` in the repo's directory, or `nix build .#librust-g` or `nix build .#libdreamluau` to build the crates independently.
