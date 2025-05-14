SDSetupManager

> **A lightning-fast, reproducible setup for AUTOMATIC1111’s Stable Diffusion WebUI on Colab + GDrive**  
> Colab ノートブック上で GDrive にキャッシュ化された仮想環境とモデルをシンボリックリンクし、一度の実行で環境構築・起動まで完結します。

---

## 📋 Table of Contents

1. [Features / 特長](#-features--特長)  
2. [Requirements / 要件](#-requirements--要件)  
3. [Quick Start / クイックスタート](#-quick-start--クイックスタート)  
4. [Configuration / 設定](#-configuration--設定)  
5. [Usage / 使い方](#-usage--使い方)  
6. [Development / 開発](#-development--開発)  
7. [License / ライセンス](#-license--ライセンス)

---

## ✨ Features / 特長

- **Automated Colab + GDrive integration**  
  Colab の起動時に GDrive 上のキャッシュ済み環境をリンクし、毎回の再セットアップを最小化。  
- **Virtualenv cache**  
  GDrive 上に一度インストールした Python 仮想環境を再利用し、起動時間を大幅短縮。  
- **Git clone & submodule update**  
  WebUI リポジトリを指定タグで自動クローン、サブモジュールも同時更新。  
- **Flexible configuration**  
  `.env` ファイルでパスやタグを簡単カスタマイズ。  
- **Bilingual docs**  
  英語・日本語の両方で手順を明示。

---

## 🛠 Requirements / 要件

- Google Colab  
- Google Drive マウント権限  
- Python 3.7+  
- GDrive にあらかじめ準備しておくもの：  
  - **仮想環境キャッシュ**（`virtualenv` で一度インストール済み）  
  - **Stable Diffusion WebUI リポジトリ**（任意のタグで）  
  - **モデル／拡張フォルダ**  

---

## 🚀 Quick Start / クイックスタート

  1. **Google Colab でノートブック(SDSetupManager.ipynb)を開く**  
	2.	.env ファイルを準備 (settings_sdm.env など)
	3.	SDSetupManager を実行
  4.	数3分待つだけで WebUI が起動します。


## ⚙️ Configuration / 設定




