# README作成記録

## 2026-06-11

### 変更内容

- `README.md` を新規作成。
- `index.html` と `docs` 配下の企画メモ、実装ログをもとに、ゲーム概要、遊び方、ゲームモード、ドリンク進化、技術構成、ローカル確認手順、関連ドキュメントを整理。
- GitHub Pages公開時にトップページとして `index.html` を開く前提の説明を追加。
- Three.jsをCDNから読み込むため、プレイ時にインターネット接続が必要であることを明記。

### 変更理由

- GitHub Pagesでスマートフォン向けデモを共有する際、初見のプレイヤーや確認者がゲーム内容、起動方法、操作方法を把握できるようにするため。
- 実装経緯が `docs` 配下に分散しているため、入口となるREADMEに要点を集約するため。

### 確認内容

- `index.html` のタイトル、画面構成、モード定義、ドリンク定義を確認。
- `docs/01_game_concept.md`、`docs/10_3d_cylinder_prototype_log.md`、`docs/11_3d_mobile_layout_and_touch_launch_log.md`、`docs/17_3d_scene_modes_log.md`、`docs/18_3d_hud_quit_button_log.md`、`docs/19_3d_quit_message_log.md` の内容を参照。
