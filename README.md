# {reponame}

<h3 align="center"><img src="media/MyAnimeListLogo.png"></h3>

<p align="center">
  <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#quick-start--information">Quick Start & Information</a> •
  <a href="#gallery">Gallery</a>
</p>

## About
[![Top language](https://img.shields.io/github/languages/top/{username}/{reponame}?style=flat-square)](https://github.com/{username}/{reponame})
[![Repository size](https://img.shields.io/github/repo-size/{username}/{reponame}?style=flat-square&label=repo%20size)](https://github.com/{username}/{reponame})
[![Commit activity per year](https://img.shields.io/github/commit-activity/y/{username}/{reponame}?style=flat-square&label=commits)](https://github.com/{username}/{reponame}/graphs/commit-activity)
[![Commits since tagged version](https://img.shields.io/github/commits-since/{username}/{reponame}/latest?style=flat-square&label=commits%20since%20tag)](https://github.com/{username}/{reponame}/releases)
[![GitHub downloads](https://img.shields.io/github/downloads/{username}/{reponame}/total?style=flat-square&label=downloads)](https://github.com/{username}/{reponame}/releases)
[![Licencia: PolyForm Noncommercial + GNU AGPL-3.0](https://img.shields.io/badge/License-PolyForm%20Noncommercial%20%2B%20GNU%20AGPL--3.0-blue?style=flat-square)](https://github.com/{username}/{reponame}/blob/main/LICENSE)
[![Bitcoin BTC](https://img.shields.io/badge/buy_me_a_coffee-BTC-F7931A?style=flat-square&logo=bitcoin&logoColor=white)](https://github.com/SegoCode/SegoCode/discussions/2)

Personal MyAnimeList gallery generator. It reads completed anime URLs from `docs/completed`, fetches cover images from the Jikan API and writes a visual gallery to `docs/README.md`.

## Features

- List-driven gallery: add or remove anime by editing `docs/completed`.
- Automatic cover fetch from [Jikan](https://jikan.moe/) with a pictures endpoint fallback.
- Generated gallery published under `docs/README.md`.
- Manual regeneration through the **Load anime gallery** GitHub Action.

## Quick Start & Information

1. Edit `docs/completed` with one MyAnimeList URL per line:
   ```text
   https://myanimelist.net/anime/1535/Death_Note
   https://myanimelist.net/anime/5114/Fullmetal_Alchemist__Brotherhood
   ```
2. Open the repository **Actions** tab.
3. Run the **Load anime gallery** workflow.
4. When it finishes, open [`docs/README.md`](docs/README.md) to see the updated gallery.

> [!NOTE]
> The workflow rate-limits requests to the Jikan API. Large lists take longer to regenerate.

> [!TIP]
> Keep only completed titles in `docs/completed`. The workflow does not track watching or plan-to-watch lists.

## Gallery

The generated gallery lives in [`docs/README.md`](docs/README.md).

---
<p align="center"><a href="https://github.com/{username}/{reponame}/graphs/contributors">
  <img src="https://contrib.rocks/image?repo={username}/{reponame}" />
</a></p>
