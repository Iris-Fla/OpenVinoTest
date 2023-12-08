# OpenVinoTest✨
 OpenVinoの動作確認アプリケーションです！

## 開発の仕方📗
Venv環境を作成してから

1. Venv環境に入る
`.\venv\Scripts\activate`
1. 関連パッケージをインストール
`pip install -r requirements.txt`
1. (Requirementsを作り直す)
`pip freeze > requirements.txt`

## Memo📘
GPUで動くようにする場合はランタイムをインストール([リンク](https://github.com/intel/compute-runtime))