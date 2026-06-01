# pixie-engine-build

Cross-compiles the [xarillian/GDLlama](https://github.com/xarillian/GDLlama) llama.cpp
GDExtension for **Android arm64 (aarch64)** using GitHub's free CI runners.

The build recipe lives in `.github/workflows/build-android.yml`. Each run produces a
downloadable `gdllama-android-arm64` artifact containing the compiled `.so`, which gets
dropped into the PixelPeeps in-process inference rig.

No model, no secrets, nothing private — this only compiles the open-source engine.
