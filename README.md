## 自己紹介

- そこら辺の大学に生えてる学部生です
- STM32や各種センサー類のコードを書いています
- 今年の目標　コミットメッセージをちゃんと書く

## 書いている言語

ほんのちょっとわかる

<img alt="my skills" src="https://skillicons.dev/icons?theme=dark&perline=7&i=c,cpp" />

触ったことあるけど意味不明

<img alt="my skills" src="https://skillicons.dev/icons?theme=dark&perline=7&i=python,lua,html,react" />

## 作成した（ぽんこつ）プログラム

ちゃんと動くものから、動くか不明なものまで色々あります

### FC(フライトコントローラー)

> 大会に出す予定があるので、しばらくPrivateにしてるかも

・[PFlight](https://github.com/NOKOLat/PFLIGHT) 
> マルチコプターのFCのP(ぽんこつ）Flightです。現在開発中

<details>

<summary><h3>センサーライブラリ</h3></summary>

  ・[STM32_BM1422AGV](https://github.com/NOKOLat/STM32_BM1422AGMV) 
  
  > 精度のいい3軸地磁気センサー
  > - 実行環境: STM32 HALライブラリ
  > - 通信形式: I2C(~400kbps)
  
  ・[STM32_ICM45686](https://github.com/NOKOLat/STM32_ICM45686)
  
  > 低電力の6軸センサー
  > - 実行環境: STM32 HALライブラリ
  > - 通信形式: I2C(~1Mbps) / SPI(~24Mbps)
  
  ・[STM32_ICM42688P](https://github.com/NOKOLat/STM32_ICM42688P)
  
  > 高精度の6軸センサー
  > - 実行環境: STM32 HALライブラリ + Arudino Wireライブラリ(I2C）
  > - 通信形式: I2C(~1Mbps) / SPI(~24Mbps) 

</details>

### データ処理

・[ComplementaryFilter](https://github.com/NOKOLat/ComplementaryFilter)

> 一般的な相補フィルタ
> - 加速度のノルムを使うことで、急な移動に少し対応

### 謎のツールたち

・[python_SBUS_Generator](https://github.com/aoi-256/SBUS_Generator)

> PythonでSBUSを送信する装置です
> - UARTとして受信するため反転処理をしてあります


### ドキュメント

・[STM32](https://aoi-256.github.io/STM32_DEV/)

> 所属しているサークルの引継ぎ用です

・[STM32_React](https://github.com/aoi-256/STM32_document_React)

> React + TsとGASを使用して自動進捗管理機能を付ける（開発中）

<details>

<summary><h3>ESP32のツールなど</h3></summary>

・[ESP32_SoftAP_Utility](https://github.com/aoi-256/Arudino_SoftAP_Utility) 

> - <Wifi.h>のsoftAPを使ったデバック用のコードセットです
> - PC側の受信コード(python)も付属しています

・[ESP32_StateDev](https://github.com/aoi-256/ESP32_StateDev) 

> - Stateパターンのクラスサンプルです
> - 割と詳細に処理の流れが書いてあります
> - vscodeのplatformIOなどを使用して実行してください

</details>

### その他
・[STM32_F446_Register](https://github.com/aoi-256/STM32_F446_Register)
> レジスタ縛りSTM32の記録（勉強用）


## 使用について

- Readmeやlicenseに記載がない限りMITライセンスを採用しています
>
> 商用、非商用に問わず改変や再配布などは自由ですので、適当に使ってください
>
> ただし、一切の責任は取りません
>
> [MITlicense](https://opensource.org/license/mit)
>
> 使用報告をくれたら私がうれしいです
