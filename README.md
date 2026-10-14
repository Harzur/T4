# YuE2_(Q8_0)_Colab_T4

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harzur/YuE2_Q8_0_Colab_T4/blob/main/YuE2_(Q8_0)_Colab_T4.ipynb)

A ready-to-use Google Colab notebook that downloads and runs the T4 build published in this repository's Releases.

## Quick summary

1. Open the notebook using the badge above.  
2. Run the cells in order — the notebook downloads the build from Releases and runs it inside the Colab runtime.  

## Encourage adding the official skill to your AI agent 😊

If you use this notebook together with an AI agent, consider adding the official YuE2 music skill so your agent can invoke generation or play music directly. The official skill documentation is available here:

Skill file: https://github.com/multimodal-art-projection/YuE/tree/main/skills/yue2-music


## Based on / Attribution

This project is adapted from the original work:

- Upstream repository: https://github.com/ServeurpersoCom/yue2.cpp  
- Original author: ServeurpersoCom  
- Original license: MIT License — see upstream LICENSE: https://github.com/ServeurpersoCom/yue2.cpp/blob/master/LICENSE

Please keep attribution to the upstream project when redistributing or publishing derivatives.

## License note

Parts of this repository rely on code from `ServeurpersoCom/yue2.cpp` (MIT). When redistributing or publishing derived work, please:

- Preserve the upstream copyright and attribution.
- Include or reference the upstream MIT license.
- Clearly state that this repo contains adaptations for Colab and is not an official upstream release.

## Usage & links
- Upstream repo: https://github.com/ServeurpersoCom/yue2.cpp
- This repo releases: https://github.com/Harzur/T4/releases
- Colab notebook: https://colab.research.google.com/github/Harzur/T4/blob/main/YuE2_(Q8_0)_Colab_T4.ipynb 

## Disclaimer
This repository is an adaptation for convenience and testing in Colab. It does not replace or change the upstream project's license or terms. Always follow the upstream license and third-party requirements.

## Safety / verification

Running binaries downloaded from the internet has risks. We recommend verifying integrity before execution.

Example to download and show SHA256 in Colab:
```bash
# Download (replace <TAG> and <FILENAME>)
curl -L -o /content/t4_build.zip "https://github.com/Harzur/T4/releases/download/<TAG>/<FILENAME>"
# Print SHA256
sha256sum /content/t4_build.zip
# Unzip
unzip -o /content/t4_build.zip -d /content/t4_build
