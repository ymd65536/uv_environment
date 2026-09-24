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

## Run

```bash
uv run --env-file .env python --version
```

`.env.example` に `PYTHONDONTWRITEBYTECODE=1` を設定済みです。`.env` を作成して `--env-file .env` を付けて実行すると `__pycache__` を作成しません。
