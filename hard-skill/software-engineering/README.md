# ソフトウェアエンジニアリング

## 理論・原則・法則

### 改善（Kaizen）

* 小さな進歩を継続して積み重ねていくこと
* そのまま英語になっている日本語である

### 割れ窓理論

* 軽微な秩序違反を放置するといずれ重大な秩序違反を起こし無秩序になっていく
* どんな軽微な秩序違反もすぐに対処しなければならない
* あらゆるものは時間経過とともに無秩序になっていく

### ゆでガエル理論

* 小さな変化は気づきにくいが気づかないといずれ取り返しのつかないことになる

### ETC原則（Easy To Change: 変更容易性）

* 良い設計原則は全て「簡単に変更できる」を達成する
* 「簡単に変更できる」選択肢を最優先する

### DRY原則

* 全ての知識は単一かつ明確で信頼できる表現であるべき
* コードの重複を防ぐという意味ではない（たまたま2つの知識が同じ規則を持っていただけ）

### 曳光弾

* 目標を捉える単純な1つのユースケースを実装する
* 目標の正しさや到達する道筋に対するフィードバックを得る
* プロトタイプと違い曳光弾は目標の正しさが確認できればそのまま使われる

### プロトタイプ

* 曳光弾を放つ前の偵察、諜報活動
* 完成品よりも安価な素材で簡単かつ素早く作成する（異なる素材やダミーを使って良い）
* 曳光弾と違い使用後は破棄される
* 学びを得ることが目的

### コンウェイの法則

* システムの設計は組織のコミュニケーション構造を模倣する設計になる

### セキュリティの基本原則

* アタックサーフェスの最小化
* 最小権限の原則
* デフォルトセキュア
* 機密データ暗号化
* セキュリティアップデート

## 思想・思考

### 完璧なソフトウェアは存在しない

### プログラムとはデータ変換の連続である

### 偶発的プログラミングを避ける

* 幸運と行き当たりばったりの成功に頼らない
* たまたまうまくいっただけかもしれない
* 偶然や仮定に依存しない
* なぜコードがいま動いているのかを理解する

### ソフトウェア開発は建築ではなくガーデニングである

* ソフトウェアは有機的なものであり常に変化に応じて手入れが必要
* どんなに完璧に仕上げても放置すると腐る
* リファクタリングは雑草抜きや落ち葉拾いみたいなもの

### プログラマーの仕事は要求の探求である

* 顧客自身も要求をわかってない
* フィードバックをもらいながら要求を明確にする
* 要求を整理するために用語集を使う

### 失敗プロジェクトの多くはスコープの膨張が原因である

## 習慣

### 日誌を書く

* 記憶よりも記録
* アイデアの蓄積

### 知識ポートフォリオ

* 習慣的かつ定期的な投資
* 分散投資
* 見直しと再配分
* 安く書い高く売る

### 知識はプレインテキストに保存する

* あらゆるツールで知識を操作し活用できる
* 構造化されていても構わない（Markdown,json,htmlなど）

### エディタに熟達する

* 全てを理解するのではなく日々の作業に「もっと良い方法はないか」自問自答する

### バージョン管理

### スクリプトによる自動化
