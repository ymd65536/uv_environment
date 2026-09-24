# uv Python Template

## Overview

このリポジトリは、`uv` を使ってすぐに Python 開発を始めるためのテンプレートです。

## Quick Start

1. `uv` をインストール
2. 仮想環境を作成
3. 依存関係を同期

```bash
cp .env.example .env
uv venv
uv sync
```

## Check

```bash
PYTHONDONTWRITEBYTECODE=1 uv run python -c "import sys; print(sys.dont_write_bytecode)"
```

`.env.example` に `PYTHONDONTWRITEBYTECODE=1` を設定済みです。`.env` を作成してシェルで読み込むか、上記のように環境変数を付与して実行すると `__pycache__` を作成しません。
