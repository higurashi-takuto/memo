---
sidebar: auto
---

# Tech

技術に関するメモを残す。

## GitHub Actions からアップロード

[actions/upload-artifact](https://github.com/actions/upload-artifact) を使用すると、必ず zip になってアップロードされるため、自前で zip にすると二重になってしまう。

リリースにアップロードするだけなら [actions/upload-release-asset](https://github.com/actions/upload-release-asset) を使えば勝手に zip にはされないので、解決できる。

## Codespaces

[Codespaces](https://github.com/features/codespaces) が実装されたら、このメモも開発環境を作る必要がなくなるかも。

今も、ブラウザ上でファイルの変更はできるので、メモの追加自体はブラウザで完結しているけど。
