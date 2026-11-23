# R 解析環境テンプレート / R analysis environment templates

研究プロジェクト向けの、R の実行環境と再現性の記録機能を提供するテンプレートです。Docker で環境を構築し、ブラウザーの RStudio Server から利用できます。解析コードは含まれていません。

Templates providing an R runtime environment and reproducibility records for research projects. The environment runs in Docker and can be accessed through RStudio Server in a browser. Analysis code is not included.

## pull して使うリポジトリ / Repositories to clone

git で取得（clone・pull）して、そのまま環境を構築するためのリポジトリです。手順は各リポジトリの `docs/SETUP.md` に従ってください。

Repositories to get with git (clone and pull) and build the environment from directly. Follow `docs/SETUP.md` in each repository.

| R | 日本語版 / Japanese | 英語版 / English |
|---|---|---|
| 4.5.3 | [r_reproducible_r453_jp](https://github.com/keiimai/r_reproducible_r453_jp) | [r_reproducible_r453_en](https://github.com/keiimai/r_reproducible_r453_en) |

## 起動用のファイル付きの ZIP / ZIPs with launcher files

使用する R の版と言語に合った ZIP を、このリポジトリの Releases からダウンロードし、ZIP の中の手順書（`HOW_TO_USE_Mac.html`・`HOW_TO_USE_Windows.html`）に従ってください。

Download the ZIP for your R version and language from this repository’s Releases, and follow the guide inside the ZIP (`HOW_TO_USE_Mac.html` or `HOW_TO_USE_Windows.html`).

| R | 日本語版 / Japanese | 英語版 / English |
|---|---|---|
| 4.5.3 | [r453-v0.1.1](https://github.com/keiimai/r_dist_release/releases/tag/r453-v0.1.1)（`R_jp_r453_*.zip`） | [r453-v0.1.1](https://github.com/keiimai/r_dist_release/releases/tag/r453-v0.1.1)（`R_en_r453_*.zip`） |

## ソースコード / Source code

各環境のソースコード（起動用のファイルを含む）です。ZIP は、これらのリポジトリから作ります。

The source code of each environment, including the launcher files. The ZIPs are built from these repositories.

| R | 日本語版 / Japanese | 英語版 / English |
|---|---|---|
| 4.5.3 | [r_dist_r453_jp](https://github.com/keiimai/r_dist_r453_jp) | [r_dist_r453_en](https://github.com/keiimai/r_dist_r453_en) |

## 環境を持たない枠組み / Framework without an environment

研究プロジェクトを起こすための、ディレクトリの構成・ライセンス・記録の雛形と、再現性の記録層だけを持つテンプレートです。Docker も実行環境も含まず、R の版にもよりません。環境はご自身で用意し、各リポジトリの `README.md` に従ってください。

A template with only the directory structure, the license, record templates and the reproducibility recording layer, for starting research projects. It contains neither Docker nor a runtime environment, and does not depend on the R version. Prepare the environment yourself, and follow `README.md` in each repository.

| 日本語版 / Japanese | 英語版 / English |
|---|---|
| [r_skeleton_jp](https://github.com/keiimai/r_skeleton_jp) | [r_skeleton_en](https://github.com/keiimai/r_skeleton_en) |

## AI の使用 / Use of AI

デモ動画は、AI を道具として使って作りました。台本・字幕・画面の撮影と編集は Anthropic の [Claude Opus 5.5](https://www.anthropic.com/claude/opus)（[Claude Code](https://code.claude.com/docs/en/overview) で使用）、ナレーションの音声は Google の [Gemini](https://ai.google.dev/gemini-api/docs/speech-generation)（`gemini-3.8-flash-tts`）で作り、ナレーションと場面の時刻合わせと音声の確認には `gemini-3.5-flash` を使いました。画面は、実際にこの環境を操作して撮ったものです。

The demo videos were made with AI as a tool. The script, subtitles, screen capture and editing were done with [Claude Opus 5.5](https://www.anthropic.com/claude/opus) by Anthropic (used through [Claude Code](https://code.claude.com/docs/en/overview)), the narration voice was generated with Google's [Gemini](https://ai.google.dev/gemini-api/docs/speech-generation) (`gemini-3.8-flash-tts`), and `gemini-3.5-flash` was used to align the narration with the scenes and to check the audio. The screens were captured by actually operating this environment.
