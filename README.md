# Vincent-app

![](https://pbs.twimg.com/media/DgqdsFCU8AATgCo.jpg)

​		![](https://miro.medium.com/max/500/1*Fe6z8VdUS6laTd6Ev3EohQ.gif)

## Androidで写真や動画を撮影するとリアルタイムで，任意の画風に変換するアプリケーションです[[1](https://www.youtube.com/watch?v=qXqoXhlq7BE#action=share),[2](<https://www.youtube.com/watch?v=TOCr52yLwSE>),[3](https://towardsdatascience.com/artistic-style-transfer-b7566a216431),[4](https://qiita.com/kidach1/items/0e7af5981e39955f33d6)]．

タスクは，主に3つで構成されています．

| タスクの概要 |                                          |
| ------------ | :--------------------------------------- |
| タスク1      | Deep LearningによるStyle Transfer or GAN |
| タスク2      | Androidのウェブアプリケーション          |
| タスク3      | Cloudサーバへの通信やデータベースの管理  |



### タスク1の情報

開発言語は，Python 3.6，Keras 1.5

関連論文についての解説は，[こちらで](https://github.com/https-github-com-mtakamat/Related-Papers)説明する

使用できるスタイル：Vincent Willem van Gogh，Johannes Vermeer ，Pierre-Auguste Renoir，など

### タスク3の情報

[Google Cloud Platform (GCP)](https://console.cloud.google.com/home/dashboard?hl=ja&project=adroit-particle-265806)を使用する場合，設定したCompute Engineに作成したアプリケーションをデプロイする場合は，[Google Cloud SDK](https://cloud.google.com/sdk/?hl=ja)が便利