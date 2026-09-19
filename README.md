# FEAR SWITCH PWA MVP

スマホだけで使う個人用FEAR SWITCHの最初のMVPです。

## 今できること
- Fear Score（デモデータ）
- VIX / NASDAQ-100 / S&P500の市場状態表示
- ユーザー自身のVIXルール設定
- 類似局面UI（デモ履歴）
- 暴落シミュレーター
- PWAとしてホーム画面追加に対応
- Service Workerによる基本的なオフラインキャッシュ

## 重要
現在の市場データは実データではなく、動作確認用のデモ値です。
Cboe / Nasdaq / S&P DJI等の実データ接続は次段階で追加します。

## スマホで試す
HTMLファイルをそのまま開く方法では、PWAのインストールやService Workerが動かない場合があります。
HTTPSでホストしたURLをAndroid Chromeで開き、「ホーム画面に追加」してください。
