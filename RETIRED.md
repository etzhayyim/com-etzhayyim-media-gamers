# RETIRED — 後継は cloud-itonami/media

**2026-08-09、この repo は retire した**（オーナー指示: media 主題を cloud-itonami に
集約する）。archive してあるので read-only。

これは `cloud-itonami/media-gamers` を切り出した時点の残骸（7 ファイルの stub）で、
その `media-gamers` 自身も同日 retire し、中身は
**[`cloud-itonami/media`](https://github.com/cloud-itonami/media) の `kouryaku/`** に
統合した。公開面は **https://kouryaku.itonami.cloud**。

## 確認したこと（retire 前の実測 2026-08-09）

- `.well-known/did.json` を持っているが **どこからも serve されていない**
  （`media-gamers.etzhayyim.com` は DNS 解決せず、GitHub Pages も未有効化 = 404）。
  DID を止める副作用は無い。
- この DID を参照しているのは retire 対象の `media-gamers` 自身と、
  `kotoba-lang/lexicons-bundle` の生成ファイル 1 件のみ。
