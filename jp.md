# Box64 aarch64 for Termux

[English](en.md) | 日本語

Termux向けにビルドした Box64 ARM64 パッケージです。

## 必要環境

- Android 8以降
- aarch64版 Termux

## インストール

GitHub Releasesから `.deb` ファイルをダウンロードしてください。

ダウンロードした場所で実行:

```sh
pkg install ./box64_0.4.3_aarch64.deb
または:
dpkg -i box64_0.4.3_aarch64.deb
apt -f install
動作確認
box64 --version
ビルド情報
アーキテクチャ: aarch64
Dynarec: ARM64 有効
コンパイラ: clang (Termux)
ターゲット: Termux native
使用方法
box64 ./program
Box64はARM64端末上でLinux x86_64アプリケーションを実行します。
注意
Wineなどのx86_64アプリケーションを使用する場合、追加ライブラリが必要になる場合があります。
このパッケージはTermux向けにビルドされています。
