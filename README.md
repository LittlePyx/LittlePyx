# Yanxi Pan · 潘彦茜

I build software and contribute to open source, with interests in **AI applications, numerical computing, and systems programming**.

My work spans tools for research and reading, floating-point correctness in SIMD libraries, and fixes in the PyTorch ecosystem.

[Website & writing](https://littlepyx.github.io/about/) · [Open-source contributions](#open-source-contributions) · [Selected projects](#selected-projects)

## Open-source contributions

[![PyTorch contributor](https://img.shields.io/badge/PyTorch-Contributor-8250df?logo=github)](https://github.com/pytorch/pytorch/commit/62280d37c702b9f201a34209c67a0ad35a605798)
[![Google Highway contributor](https://img.shields.io/badge/Google_Highway-Contributor-8250df?logo=github)](https://github.com/google/highway/pulls?q=is%3Apr+is%3Amerged+author%3ALittlePyx)
[![x86-simd-sort contributor](https://img.shields.io/badge/x86--simd--sort-Contributor-8250df?logo=github)](https://github.com/numpy/x86-simd-sort/commit/1dadd5d3e9730d9cfe428460794a76241968feb3)

Selected contributions incorporated upstream:

| Project | Contribution | Upstream links |
| --- | --- | --- |
| **PyTorch** | Fixed an AOT/Dynamo circular import that could leave Dynamo partially initialized and break a later `torch.compile` call; added subprocess regression coverage. | [#204231 · commit](https://github.com/pytorch/pytorch/commit/62280d37c702b9f201a34209c67a0ad35a605798) |
| **Google Highway** | Added support for multiple template arguments in dynamic dispatch; preserved signed-zero counts in VQSort's two-value partition and sorting networks. | [#3548](https://github.com/google/highway/pull/3548) · [#3543](https://github.com/google/highway/pull/3543) · [#3544](https://github.com/google/highway/pull/3544) |
| **x86-simd-sort** | Fixed floating-point SIMD compare-exchange so equal-valued positive and negative zeros retain their original bit-pattern counts. | [#244](https://github.com/numpy/x86-simd-sort/pull/244) |

## Selected projects

I develop and maintain three tools for finding, reading, and working with research papers.

| Project | What it does | Explore |
| --- | --- | --- |
| **[Pi Zaya](https://github.com/LittlePyx/Pi_zaya)** | A research assistant for a local academic library, with cross-paper retrieval, evidence-grounded answers, and citations that lead back to source passages. | [Code](https://github.com/LittlePyx/Pi_zaya) · [Windows&nbsp;releases](https://github.com/LittlePyx/Pi_zaya/releases) |
| **[Pi&nbsp;Research](https://github.com/LittlePyx/pi-research)** | Continuous paper discovery and personalized screening, with research maps and reading paths built from relevant papers. | [Code](https://github.com/LittlePyx/pi-research) · [Web&nbsp;app](https://pi-research-agent.qiudao-pika.chatgpt.site/) |
| **[Pi&nbsp;Translator](https://github.com/LittlePyx/Pi-translator)** | An Edge extension for bilingual reading across webpages, Overleaf, and PDFs, with research notes, terminology, and user-configured AI providers. | [Code](https://github.com/LittlePyx/Pi-translator) · [Edge&nbsp;Add-ons](https://microsoftedge.microsoft.com/addons/detail/pi-translator/edfkcddhenkhdkedhnmcebmmfacabcjf) |

[XERJ Corpus Hub](https://hub.xerj.org/contributors/LittlePyx) selected a [Pi Zaya commit](https://github.com/LittlePyx/Pi_zaya/commit/3b1a43e485bab3c73b4dd3dd8b5fddff3d3955cc) that links Noise2Noise conditions to supporting source passages.

---

Currently exploring numerical software, framework internals, and performance engineering while continuing to improve my applications.
