# Perception Neuron2.0 manual

早稲田大学岩田研究室内での技術伝達用の解説マニュアルです.
Noitom社のIMUモーションキャプチャ「perception neuron」<br/>
および専用ソフトウェア「axis neuron」の使い方について説明していきます.<br/>

##Requirement

Windows or MacOS

筆者はWindows10での動作を確認しています.

##Usage

###Downroad + Install
まずは「axis neuron」のダウンロードを行います.
[こちらのリンク](https://neuronmocap.com/content/axis-neuron)からOSに合わせてダウンロードおよびインストールを行ってください.

###Connection with Sensor

perception neuron本体を装着します.実機付属の紙のマニュアルを読みながら行うのがおすすめです.
1. 全身分のセンサー（計31個）をはめ込み体に装着、センサーHubと接続します.
2. センサーHubのDataと記されている端子からPCと接続,「axis neuron」を起動してセットアップを行います.

###Motion Capture

以降のセットアップおよびチュートリアルは[こちらのリンク](https://www.aiuto-jp.co.jp/support/file_51.php)にありますユーザーマニュアルの4章から読んでいただければ可能です.
接続とキャリブレーションを行った後は録画ボタンを押すことでモーションの保存も行えます.

また,6章ではキャプチャーした動作の解析や調整,
8章ではデータの送信やリアルタイム通信の手法も載っていますので合わせてご利用ください.

###Connection with Unity

「axis neuron」では公式でUnityと接続できる開発環境が提供されています.
[こちらのリンク](https://neuronmocap.com/software/unity-sdk)からダウンロードしたカスタムパッケージをUnityでインポートすれば使用できます.
細かいスクリプトの使い方とかは上記リンクから見られるマニュアルを読んでみてください.（英語）

###other Plugin

[公式でサポートしているソフト等の一覧](https://neuronmocap.com/ja/downloads)です.
リンクの下部から見れるので目を通しておくといいかもしれません。
