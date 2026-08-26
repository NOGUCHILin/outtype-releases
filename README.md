# outtype-releases

**Outtype の配布物と、自動更新のマニフェストだけを置く場所。**
ソースは別リポジトリ（非公開）。

- `Outtype_<版>_arm64.dmg` — 新しく入れる人向け（公証済み）
- `Outtype.app.tar.gz` + `.sig` — 自動更新が取りに来るもの
- `latest.json` — 更新の宛先。アプリは
  `releases/latest/download/latest.json` を見に来る

作り方は Outtype 側の `scripts/release-updater.sh`。
