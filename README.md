# SpeedTesting

cocoapodsで重たそうな依存性をpod installした後、クリーンビルドをかけてビルド終了までの時間を計測

以下のコマンドをターミナルで打ち込んでビルド時間がわかるようにした。
```
defaults write com.apple.dt.Xcode ShowBuildOperationDuration YES
```


| マシン |  利用年数 | 購入時価格(円)　| RAM | プロセッサ | GPU |
|:-----------|:------------|:------------|:------------|:------------|:------------|
| MacBook Air (11-inch, Early 2014) | 4年0ヶ月 | 20万強| 8GB 1600 MHz DDR3 | 1.7 GHz Intel Core i7| Intel HD Graphics 5000 1536 MB |
|iMac (Retina 5K, 27-inch, 2017) | 0ヶ月（買いたて） | 50万弱 |64 GB 2400 MHz DDR4 | 4.2 GHz Intel Core i7 | Radeon Pro 580 8192 MB |

| マシン |  クリーンビルド |
|:------------|:------------|
| MacBook Air | 172.623s |
|iMac | 41.124s |
