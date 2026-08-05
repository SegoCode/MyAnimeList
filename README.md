# MyAnimeList

[![Top language](https://img.shields.io/github/languages/top/SegoCode/MyAnimeList?style=flat-square)](https://github.com/SegoCode/MyAnimeList)
[![Repository size](https://img.shields.io/github/repo-size/SegoCode/MyAnimeList?style=flat-square&label=repo%20size)](https://github.com/SegoCode/MyAnimeList)
[![Commit activity per year](https://img.shields.io/github/commit-activity/y/SegoCode/MyAnimeList?style=flat-square&label=commits)](https://github.com/SegoCode/MyAnimeList/graphs/commit-activity)
[![License: MIT License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/SegoCode/MyAnimeList/blob/main/LICENSE)
[![Bitcoin BTC](https://img.shields.io/badge/buy_me_a_coffee-BTC-F7931A?style=flat-square&logo=bitcoin&logoColor=white)](https://github.com/SegoCode/SegoCode/discussions/2)

Personal MyAnimeList gallery generator. It reads completed anime URLs from `docs/completed`, fetches cover images from the Jikan API and writes a visual gallery to `docs/README.md`.

## Quick Start & Information

1. Edit [`docs/completed`](docs/completed) with one MyAnimeList URL per line:

   ```text
   https://myanimelist.net/anime/1535/Death_Note
   https://myanimelist.net/anime/5114/Fullmetal_Alchemist__Brotherhood
   ```
2. Open the repository [**Actions**](https://github.com/SegoCode/MyAnimeList/actions) tab.
3. Run the [**Load anime gallery**](https://github.com/SegoCode/MyAnimeList/actions/workflows/load-anime-gallery.yml) workflow.
4. When it finishes, open [`docs/README.md`](docs/README.md) to see the updated gallery.

The generated gallery lives in [`docs/README.md`](docs/README.md).

---
<p align="center"><a href="https://github.com/SegoCode/MyAnimeList/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SegoCode/MyAnimeList" />
</a></p>
