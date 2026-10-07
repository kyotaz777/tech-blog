# AWS Tech Blog

AWS / IaC / CI/CD / Monitoring の実践を目的として構築する、個人用技術ブログです。

## Overview

個人用の技術ブログをAWS上に構築・運用するプロジェクトです。

ブログそのものの構築に加えて、AWS上でのインフラ設計・構築、TerraformによるIaC、CI/CD、監視・運用までを一通り実践することを目的としています。

## Features

### Public

- 公開済み記事の閲覧

### Admin

- 管理者ログイン
- 記事の作成
- 記事の編集
- 記事の削除

初期リリースでは、上記の最小機能を実装対象とします。

## Tech Stack

### Frontend

- TypeScript
- Next.js

### Backend

- Python
- FastAPI

### Database

- PostgreSQL

### Infrastructure

- AWS
- Terraform

### CI/CD

- GitHub Actions

## Architecture

AWSアーキテクチャについては設計中です。

Frontend / Backend / Database を分離し、それぞれの構築・デプロイ・監視を経験できる構成を検討します。

```text
Browser
   |
   v
Next.js
   |
   v
FastAPI
   |
   v
PostgreSQL
```

## Repository Structure

```text
.
├── README.md
├── docs/
│   └── requirements.md
├── frontend/
├── backend/
├── terraform/
└── .github/
```

ディレクトリ構成は実装に合わせて変更します。

## Documentation

- `docs/requirements.md` - 要件定義
