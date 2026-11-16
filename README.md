## Hi there 👋

<!--
**LittlePyx/LittlePyx** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

[![pytorch/pytorch · Contributor](https://img.shields.io/badge/pytorch%2Fpytorch-Contributor-8250df?logo=github)](https://github.com/pytorch/pytorch/commit/62280d37c702b9f201a34209c67a0ad35a605798) [![google/highway · Contributor](https://img.shields.io/badge/google%2Fhighway-Contributor-8250df?logo=github)](https://github.com/google/highway/pulls?q=is%3Apr+is%3Amerged+author%3ALittlePyx) [![numpy/x86-simd-sort · Contributor](https://img.shields.io/badge/numpy%2Fx86--simd--sort-Contributor-8250df?logo=github)](https://github.com/numpy/x86-simd-sort/commit/1dadd5d3e9730d9cfe428460794a76241968feb3) [![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/LittlePyx/badge.svg)](https://hub.xerj.org/contributors/LittlePyx)

### Open-source contributions

- [PyTorch #204231](https://github.com/pytorch/pytorch/commit/62280d37c702b9f201a34209c67a0ad35a605798) fixed a circular import that could leave Dynamo partly initialized and cause a later `torch.compile` call to fail.
- [Google Highway #3548](https://github.com/google/highway/pull/3548) added support for functions with multiple template arguments in `HWY_EXPORT_AND_DYNAMIC_DISPATCH_T`.
- Google Highway's VQSort now preserves the counts of `+0.0` and `-0.0` in both its [two-value partition (#3543)](https://github.com/google/highway/pull/3543) and its [short-array sorting network (#3544)](https://github.com/google/highway/pull/3544).
- [x86-simd-sort #244](https://github.com/numpy/x86-simd-sort/pull/244) fixed a SIMD compare-exchange that could turn one positive zero and one negative zero into two zeros of the same sign.

[XERJ Corpus Hub](https://hub.xerj.org/contributors/LittlePyx) selected a [Pi_zaya commit](https://github.com/LittlePyx/Pi_zaya/commit/3b1a43e485bab3c73b4dd3dd8b5fddff3d3955cc) that links Noise2Noise conditions to the source passages that support them.
