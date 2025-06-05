# ACT Base Circuit（β版）
## What's ACT Base Circuit
![Image](https://github.com/user-attachments/assets/9c1ff4e7-ef69-43a2-a87d-43eb80ff22f7)
　ACT Base Circuit（以降，ABC）は，東京工業大学ロボット技術研究会ACTが開発した，多軸ロボット駆動用の汎用制御基板です．
　ESP32をメインの計算機として搭載し，USB-Cポートを経由したシリアル通信，Feetech社サーボモータのTTL信号への対応，RS485ポートを経由したシリアル通信などに対応しています．
　また，9軸IMUであるBNO055を搭載しており，多軸ロボットの重心移動検知が実施できます．

## ファイル構成
　このリポジトリ内のファイル構成は，以下のようになっています．
```
Top
|-LICENSE                                   ライセンス情報
|-README.md                                 本リポジトリの説明
|-Parts_list.csv                            ABC部品表
|-ACT_Base_Circuit.stp                      ABCの3Dデータ
|-gbr_and_drl                               ガーバーデータ，およびドリルデータ．このデータをJLCPCBやPCBGOGOなどの業者に投稿することで，基板が作成できます．
    |-ACT_Base_board-B_Cu.gbr               ガーバーデータの一部
            ～略～
```
## 現在発生している問題（2025/06/05現在）
現在発生している問題は，以下の通りです．近日中に対処いたします．
- BNO055の認識ができていない
- 部品表に一部誤表記がある

## コンタクト
　技術的お問い合わせは，本リポジトリのIssueよりお願いいたします．

　その他の問い合わせについては，[主任開発者HP内のコンタクトに記載された手段](https://sugi-kmmm.github.io/contact.html)により行ってください．また，教育機関の講義で使用する場合等においては，特段の連絡は必要ありませんが，ご報告していただけますと製作者のモチベーションにつながります．ぜひご一報いただけますと幸いです．

## 開発者
開発者は以下の通りです．
[Sugi_kmmm](https://github.com/Sugi-kmmm)
[21-kojima](https://github.com/21-kojima)
[22-soeda](https://github.com/22-soeda)


## LICENSE情報
BaseNoidは以下のクリエイティブ・コモンズ・ライセンスにより保護されています．

BaseNoid © 2025 by [Rei Sugihara](https://sugi-kmmm.github.io/index.html) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1).