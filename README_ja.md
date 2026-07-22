# RemoteHub

[English README](README.md)

**シミュレータの確認を、もっと手元に。** RemoteHubは、シミュレータのライブ映像と主要な操作をスマホに届けます。机から離れていても、開発中のUIをすばやく確認できます。

## クイックスタート

1. PCアプリをHomebrewまたはDMGからインストールします。
2. PCアプリとスマホのRemoteHubを起動します。
3. PCとスマホを同じネットワークまたはVPNへ接続します。
4. 初回設定ではiCloudによる自動接続を確認します。共有する場合は、PCアプリの設定画面から「アプリURLを共有」を選び、AirDropでスマホへ送信します。
5. シミュレータを選び、表示と操作を始めます。

## PCアプリをインストール

### Homebrew

```bash
brew tap kmatsushita1012/tap
brew install --cask remote-hub
```

### DMG

最新版の[RemoteHub.dmg](https://github.com/kmatsushita1012/RemoteHub/releases/latest/download/RemoteHub.dmg)をダウンロードして開き、`RemoteHub.app`をアプリケーションへ移動します。

## できること

- シミュレータ画面をリアルタイムに表示
- タップ、スワイプ、文字入力
- 表示するシミュレータの切り替え
- UI確認に集中できるフルスクリーン表示
- 共有または自動検出した接続情報による再接続

## 接続について

PCとスマホが、同じネットワークまたはVPNを通じて互いに到達できる必要があります。PCアプリを起動し、操作したいシミュレータへアクセスできる状態にしてください。

## リリース

最新版は[Releases](https://github.com/kmatsushita1012/RemoteHub/releases)から取得できます。公開ファイルは署名・公証済みで、DMGとHomebrew Caskを利用できます。

## サポート

質問や不具合の報告は、[サポートフォーム](https://forms.gle/zyBMXx3Ganz7zjMC8)からお送りください。
