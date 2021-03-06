# TPS-Jan2022
This is a repository for [Tabular Playground Series-Jan 2022](https://www.kaggle.com/c/tabular-playground-series-jan-2022/leaderboard#score)
![](https://github.com/utibori-jp/TPS-Jan2022/blob/main/images/tps_jan2022_top.jpg)
- Derectory tree
```
Tabular Playground - Cell Instance Segmentation
├── README.md
├── data         <---- gitで管理するデータ
├── data_ignore  <---- .gitignoreに記述されているディレクトリ(モデルとか、特徴量とか、データセットとか)
├── notebook     <---- jupyter lab で作業したノートブック
├── nb_download  <---- ダウンロードした公開されているkagglenb
├── logs         <---- このcompetitionに取り組んだ時のlog
├── image        <---- imageを保存
└── src          <---- .ipynb 以外のコード
```
## Overview
### Description(DeepL)
2021年のTabular Playground Seriesで皆様からいただいたご意見をもとに、Kaggleでは2022年に向けて皆様のご協力を必要としています!

Kaggleグッズを販売する2つの（架空の）独立した店舗チェーンが、Kaggleに関するあらゆるものの公式アウトレットになりたいと考えています。私たちは、Kaggleコミュニティの皆さんに、どちらのチェーン店が将来的に最も売上を伸ばすことができるか、ご協力いただけるかどうかを確認することにしました。そこで、私たちはデータを収集し、私たちが判断するための予測モデルを構築するよう皆さんにお願いしています。

KaggleMartとKaggleRamaのどちらが公式Kaggleアウトレットになるべきかを決めるのを手伝ってください!
**Tabular Playgroundシリーズについて**
Kaggleコンペティションは非常に楽しくてやりがいのあるものですが、データサイエンスの道に比較的浅い人々にとっては、威圧的なものである可能性もあります。過去には、Featuredコンペティションよりも親しみやすく、初心者に優しいPlaygroundコンペティションを数多く立ち上げてきました。

これらのコンペティションのゴールは、楽しく、誰にでも親しみやすい表形式データセットのモデリングを提供することです。これらのコンペティションは、Titanic Getting StartedコンペティションとFeaturedコンペティションの中間のものをお探しの方に最適な選択です。もしあなたがすでにコンペティションのマスターやグランドマスターであるなら、これらのコンペティションはあなたにとってあまりチャレンジングなものではないでしょうから、リーダーボードを飽和させないようにしてください。

各月のコンペティションでは、上位3チームにKaggleグッズを提供する予定です。また、このコンペティションをより学習効果の高いものにするため、チームサイズは3名までに制限しています。

### Evaluation 
応募作品は、予測値と実績値の間のSMAPEで評価されます。実測値と予測値がともに0である場合をSMAPE=0と定義しています。

**Submission File**
テストセット内の各row_idについて、対応するnum_soldを予測する必要があります。ファイルはヘッダを含み、以下のフォーマットである必要があります。
```
row_id, num_sold
26298,100
26299,100
26300,100
etc.
```

### Timeline
* 開始日 - 2022年1月1日
* エントリー締切日 - 最終提出締切日に準ずる
* チーム合併の締切日 - 最終提出期限と同じ
* 最終提出期限 - 2022年1月31日

特に断りのない限り、すべての締め切りは対応する日の午後11時59分（UTC）です。大会主催者は、必要と判断した場合、コンテストのスケジュールを更新する権利を有します。

### Prize
* 1位 - 選べるKaggleグッズ
* 2位 - 選べるKaggleグッズ
* 3位 - 選べるKaggleグッズ

注意：初心者の方の参加をより促すため、Kaggleグッズのプレゼントは本シリーズでお一人様1回のみとさせていただきます。過去に受賞された方がいらっしゃる場合は、次のチームへ飛びます。

## Data Description(DeepL)
この課題では、3カ国にある2つの店舗で、3つの商品の1年分の売上を予測していただきます。このデータセットは完全に架空のものですが、現実のデータで見られる多くの効果、例えば週末や祝日の効果、季節性などが含まれています。このデータセットは十分に小さいので、数多くの異なるモデリングアプローチを試すことができます。

Good luck!

**Files**
* train.csv - 学習セット。日付、国、店舗、アイテムの組み合わせごとの販売データが含まれます。
* test.csv - the test set; あなたのタスクは、各日付と国・店舗・アイテムの組み合わせについて、対応するアイテムの売上を予測することです。パブリックリーダーボードはテスト年の最初の四半期に、プライベートは残りの四半期に採点されることに注意してください。
* sample_submission.csv - 正しい形式のサンプル提出ファイルです。

## Log
### 2022/1/3

## Reference
* [機械学習におけるカテゴリ変数の処理](https://ichi.pro/kikai-gakushu-niokeru-kategori-hensu-no-shori-74774194270355)
* [Torchvisionの機能を理解する(PyTorchの場合)](https://ichi.pro/torchvision-no-kino-o-rikaisuru-pytorch-no-baai-62751404301769)






















