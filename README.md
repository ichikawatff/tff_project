# 株式会社東京福祉不動産 - 統合管理プロジェクト

> AI（Google Antigravity IDE）を活用した会社全体の統合管理リポジトリ

## 概要

本リポジトリは、株式会社東京福祉不動産の経営に関わるすべての情報を一元管理するためのプロジェクトです。

## 会社概要

| 項目 | 内容 |
|------|------|
| 会社名 | 株式会社東京福祉不動産 |
| 英文名 | TOKYO FUKUSHI REAL ESTATE Co., Ltd. |
| 設立 | 2021年（令和3年）8月2日 |
| 資本金 | 4,000,000円 |
| 代表取締役 | 日髙 崇 |
| 所在地 | 〒125-0032 東京都葛飾区水元4-26-13 |
| TEL | 03-5876-4717 |
| FAX | 03-5876-4718 |
| Email | info@tff21.co.jp |
| URL | http://tff21.co.jp |

## 事業内容

- 🏠 民泊事業（HIDAKA STAY VILLA）
- 🏢 不動産賃貸仲介
- 🏘️ 不動産売買仲介
- 🤝 居住支援
- 🔄 不動産買取再販

## フォルダ構成

```
tff_project/
├── README.md                  # 本ファイル
├── .gitignore                 # Git除外設定
│
├── company/                   # 会社基本情報
│   ├── profile.md             # 会社概要・基本情報
│   ├── registrations.md       # 各種登録番号・免許
│   ├── associations.md        # 加盟団体
│   ├── financial_summary.md   # 決算サマリー
│   └── urls_and_sns.md        # URL・SNS・オンラインアカウント
│
├── employees/                 # 従業員情報
│   ├── README.md              # 従業員一覧
│   ├── takashi_hidaka.md      # 日髙崇
│   └── naoto_ichikawa.md      # 市川直人
│
├── properties/                # 物件管理
│   ├── README.md              # 物件一覧
│   ├── minpaku/               # 民泊施設
│   │   ├── shibamata.md       # 柴又施設
│   │   └── iioka.md           # 飯岡施設
│   ├── rental/                # 賃貸管理物件
│   └── sales/                 # 売買物件
│
├── finance/                   # 会計・財務
│   ├── README.md              # 財務管理概要
│   ├── mf_cloud/              # MFクラウド連携
│   └── expenses/              # 経費管理
│
├── operations/                # 業務運営
│   ├── README.md              # 業務概要
│   ├── minpaku/               # 民泊業務マニュアル
│   ├── chintai/               # 賃貸仲介業務
│   ├── baibai/                # 売買仲介業務
│   └── kyojushien/            # 居住支援業務
│
├── contracts/                 # 契約管理
│   ├── README.md              # 契約管理概要
│   ├── templates/             # 契約書テンプレート
│   └── active/                # 現行契約
│
├── marketing/                 # マーケティング
│   ├── README.md              # マーケティング概要
│   └── brand/                 # ブランド素材
│
├── projects/                  # プロジェクト管理
│   ├── README.md              # プロジェクト一覧
│   └── related_repos.md       # 関連リポジトリリンク集
│
├── docs/                      # 各種書類・テンプレート
│   └── README.md              # ドキュメント管理
│
└── confidential/              # 🔒 機密情報（Git管理外）
    ├── bank_accounts.md       # 銀行口座情報
    ├── credit_cards.md        # クレジットカード情報
    └── personal/              # 個人情報（住所・マイナンバー等）
```

## 外部連携

| サービス | 用途 | 連携方法 |
|---------|------|---------|
| MFクラウド | 会計管理 | MCP連携 |
| Google Workspace | メール・ドキュメント | Business Standard + AI |
| ChatGPT | AI活用 | Business プラン |
| GitHub | コード・ドキュメント管理 | Git |

## セキュリティ

⚠️ `confidential/` フォルダは `.gitignore` で除外されています。
銀行口座、クレジットカード、個人住所、マイナンバー等の機密情報はGitHubにプッシュされません。
