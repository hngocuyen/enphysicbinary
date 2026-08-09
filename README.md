# Enphysic Binary Runtimes

Native runtimes selected automatically by WEX loaders. A runtime is downloaded once into `.enphysic/<target>/` and then reused locally. Every loader passes the published SHA-256 to the native runtime, which verifies its own loaded file before executing a protected payload.

Targets: Windows x86/x86_64, Linux x86_64/AArch64, Termux x86_64/AArch64.

See `runtime-manifest.json` for immutable file sizes and SHA-256 digests.
