# 0. Self-made PC

- [ゼロから始める自作PC（パソコン） ​｜ドスパラ公式通販サイト](https://www.dospara.co.jp/contents/start-homebuild-pc.html)
- [初めての自作PC(パソコン)におすすめ！PCパーツの選び方【2024年最新版】｜ソフマップ[sofmap]](https://www.sofmap.com/contents/?id=nw_ps_select&sid=first)
- [【コスパ最強】オススメ構成！自作ゲーミングPC ～Ryzen 5 5600 + Radeon RX 7600～ - YouTube](https://www.youtube.com/watch?v=EMC1e9_N6ZQ)

# 1. Requirements

## 1.1. What I want to do
- Developement Using...
  - Machine Learning
    - [低スペックPCで機械学習を行った人間の末路 #機械学習 - Qiita](https://qiita.com/kaitaryu/items/9543713305e696976744#%E3%81%BE%E3%81%A8%E3%82%81)
    - [自宅で使う機械学習/ディープラーニング用PCの構成 - ゼロから始める機械学習](https://zero-ai.hatenablog.com/entry/2017/07/28/213613)
    - [How to build the perfect Deep Learning Computer and save thousands of dollars | by Jeff Chen | Mission.org | Medium](https://medium.com/the-mission/how-to-build-the-perfect-deep-learning-computer-and-save-thousands-of-dollars-9ec3b2eb4ce2)
    - [機械学習を実践するためのPC（相棒）選び｜mucun_wuxian](https://note.com/mucun_wuxian/n/n3ca10f2968c2)
    - [ディープラーニングで必要なパソコンパーツ、スペックをまとめてみた #機械学習 - Qiita](https://qiita.com/yuki_2020/items/c233d903fe41d98bfff3)
    - [【2023年度版】30万円の機械学習用の自作PCのパーツを説明する。](https://zenn.dev/derbuihan/articles/928ae5f279afbc)
  - Flutter
    - https://docs.flutter.dev/get-started/install/windows/desktop
      - They needs x64_64 8 cores, 16 GB Memory, Display 1920 x 1080 and 52GB disk
  - Grafana
    - https://grafana.com/docs/grafana/latest/setup-grafana/installation/
      - They need 512 MB Memory, 1 core
  - elastic
    - https://www.elastic.co/guide/en/cloud-enterprise/current/ece-hardware-prereq.html
      - They need 8GB RAM, 32GB Memory

- OSS Contribution
  - Polars: https://docs.pola.rs/development/contributing/#setting-up-your-local-environment
    - They need 8GB RAM
  - Airflow: https://github.com/apache/airflow/blob/main/contributing-docs/03_contributors_quick_start.rst
    - They need 4GB RAM, 40GB disk and at least 2 cores

- Ordinary Outlet
  - [電源容量計算（電源電卓）電源の選び方｜ドスパラ通販【公式】](https://www.dospara.co.jp/5info/cts_str_power_calculation_main.html)
  - [知っておきたい電気の基礎知識 | Panasonic](https://panasonic.jp/support/useful/basic.html#:~:text=%E4%B8%80%E8%88%AC%E7%9A%84%E3%81%AA%E3%82%B3%E3%83%B3%E3%82%BB%E3%83%B3%E3%83%88%E3%81%AB,%E4%BD%BF%E3%81%86%E3%81%93%E3%81%A8%E3%81%8C%E3%81%A7%E3%81%8D%E3%81%BE%E3%81%99%E3%80%82)

- Wide x Depth x Height
  1. 95 x 65 x 75
  1. 40 x 50 x -

- Wifi & Bluetooth
  - [【自作PC 】有線接続できない時は◯◯で無線接続できますよ｜てんふら](https://note.com/tenfura_2888/n/n74e95e612061)
  - [デスクトップパソコン・自作PCで無線LAN(Wi-Fi)をつける方法【3通り】 | パソログ](https://pc-bto.net/bto-desktop-pc-wireless/)
  - [【安く簡単に】自作PCでワイヤレス機能(Wi-fi/Bluetooth)を使う方法3選！｜キチマル.net](https://kichimaru.net/how-to-use-the-wireless-function-on-your-homebuild-pc/)

## 1.2 Terminology

- DDR
- PCle

## 1.3 What I should buy

- CPU:
  - at least 2 core
  - [Intel（インテル）CPU性能比較表【2023/12/26更新】｜ドスパラ【公式】](https://www.dospara.co.jp/5info/cts_lp_intel_cpu.html)
  - [AMD CPU（APU）性能比較表【2024/3/4更新】｜ドスパラ【公式】](https://www.dospara.co.jp/5info/cts_lp_amd_cpu.html)

- CPU Cooler
  - [CPUクーラーの種類、選び方やチェックしておくべきポイントについてご紹介｜ドスパラ通販【公式】](https://www.dospara.co.jp/5info/cts_str_parts_cpu-cooler.html)

- GPU:
  - [【2022】ディープラーニングで「2枚挿し」は有効？GPU運用のポイントとは | M:CPP](https://jp.morgenrot.cloud/blog/2-gpu-for-deep-learning/)
  - [グラフィックボード｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/BR31)
  - [グラフィックボード性能比較　2024/3/7更新【ドスパラ】 ｜ドスパラ公式通販サイト](https://www.dospara.co.jp/5shopping/shp_vga_def_parts.html)

- Motherboard:
  - [マザーボード｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/BR21)

- Memory:
  - 16GB x 2
  - [メモリ｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/BR12)
  - because double inserted
    - [What is Dual Channel Memory? | Crucial.com](https://www.crucial.com/articles/about-memory/what-is-dual-channel-memory)
    - [メモリを選択する場合、16GB×1枚と8GB×2枚ではどういう違いがあるのですか？ | パソコン工房【公式通販】](https://www.pc-koubou.jp/faq/faq_detail.html?id=183)

- SSD:
  - [SSDの通販・価格/性能比較 売れ筋ランキングTOP3｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/BR115)

- Case:
  - [PCケースの通販・価格/性能比較｜PCパーツ・周辺機器｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/BR72)

- Power:
  - [電源ユニットの通販・価格/性能比較｜PCパーツ・周辺機器｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/BR83)

- Display:
  - [「液晶モニター」の検索結果｜パソコン（PC）通販のドスパラ【公式】](https://www.dospara.co.jp/SBR119)

- Keyboard
  - [ワイヤレスキーボード｜パソコン通販のドスパラ【公式】](https://www.dospara.co.jp/SBR530)

