# system-docs-template
**要件定義・アーキテクチャ・設計ドキュメントのためのテンプレート集**です。

Documentation templates for **system requirements and architecture**
for business system development.

---

## 概要 / Overview

本リポジトリは、業務システム開発において以下を目的とした
**ドキュメント構成のテンプレート**を提供します。

- 要件定義から設計までを一貫して整理できる構成
- 実務と教育の両方で利用可能な粒度と構成
- 特定の技術・フレームワーク・業務に依存しないテンプレート

This repository provides **documentation templates**
that can be used in both real-world projects and educational contexts.

---

## 想定利用シーン / Intended Use

- 業務システムの新規開発・刷新プロジェクト
- 要件定義・基本設計・アーキテクチャ設計の整理
- 設計レビューや設計教育の教材
- ドキュメント構成の標準化・再利用

---

## ドキュメント構成 / Structure

本リポジトリは、以下の考え方で構成されています。

- `docs-template/`  
  設計ドキュメントの**テンプレート（抽象）**。  
  個別プロジェクトの具体内容は含みません。

- `samples/`
  テンプレートの**適用例（具体）**。  
  サンプル業務・サンプル実装を配置します。

---

## 設計上の方針 / Design Principles

- ドキュメントは「読むため」ではなく「判断基準として使う」ことを重視
- レイヤー構造・責務・境界を明確にする
- モノリシックな業務システムを前提とした現実的な設計を想定
- トランザクションスクリプト方式を含む実務向けアプローチを許容
- AI（Copilot 等）による補助入力も前提とし、人が最終判断を行う

---

## 利用方法 / How to Use

1. `docs-template/` をコピーまたは参照してプロジェクト用ドキュメントを作成
2. テンプレートに従って要件・設計を記述
3. 必要に応じてサンプルを参照

---

## License
Except where otherwise noted, this documentation is licensed under  
Creative Commons Attribution 4.0 International (CC BY 4.0).

Some parts were created with the assistance of AI tools such as
Microsoft Copilot Chat and GitHub Copilot; the author has reviewed and
curated the final content.

- License text: https://creativecommons.org/licenses/by/4.0/legalcode

## ライセンス
特に記載のない限り、本ドキュメントは  
Creative Commons 表示 4.0 国際（CC BY 4.0）の下で提供します。

一部の内容は Microsoft Copilot Chat および GitHub Copilot 等の
AI ツールの支援を受けて作成していますが、
最終的な内容は著者がレビュー・編集（キュレーション）したものです。

- 日本語要約（deed）: https://creativecommons.org/licenses/by/4.0/deed.ja


