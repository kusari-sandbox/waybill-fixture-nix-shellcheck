# waybill-fixture-nix-shellcheck

A fixture for waybill's public-corpus harness. It exposes `shellcheck`, a statically linked Haskell executable, from nixpkgs pinned at `a799d3e3`, so the nightly corpus run exercises `--nix-closure` scope derived from the runtime closure that cache.nixos.org returns.

Nothing here is meant to be used directly.
