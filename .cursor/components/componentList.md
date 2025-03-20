# コンポーネント一覧

このドキュメントでは、デザインシステムに含まれるコンポーネントの一覧を管理します。コンポーネントの追加や変更の際には、このリストを更新してください。

## コアコンポーネント

基本的な UI の構成要素となるシンプルで汎用性の高いコンポーネント群です。

| コンポーネント名 | 説明                                         | 状態   | 実装パス                   | 最終更新日 |
| ---------------- | -------------------------------------------- | ------ | -------------------------- | ---------- |
| Button           | ユーザーアクションを促すボタンコンポーネント | 計画中 | components/core/Button     | -          |
| Input            | テキスト入力フィールド                       | 計画中 | components/core/Input      | -          |
| Checkbox         | チェックボックス入力                         | 計画中 | components/core/Checkbox   | -          |
| Radio            | ラジオボタン入力                             | 計画中 | components/core/Radio      | -          |
| Select           | ドロップダウン選択メニュー                   | 計画中 | components/core/Select     | -          |
| TextArea         | 複数行テキスト入力                           | 計画中 | components/core/TextArea   | -          |
| Icon             | アイコン表示                                 | 計画中 | components/core/Icon       | -          |
| Typography       | テキスト表示用コンポーネント                 | 計画中 | components/core/Typography | -          |
| Toggle           | オン/オフ切り替えスイッチ                    | 計画中 | components/core/Toggle     | -          |
| Link             | ハイパーリンク                               | 計画中 | components/core/Link       | -          |

## 複合コンポーネント

コアコンポーネントを組み合わせた、より複雑な機能を持つコンポーネント群です。

| コンポーネント名 | 説明                         | 状態   | 実装パス                        | 最終更新日 |
| ---------------- | ---------------------------- | ------ | ------------------------------- | ---------- |
| Card             | 情報をカード形式で表示       | 計画中 | components/composite/Card       | -          |
| Modal            | モーダルダイアログ           | 計画中 | components/composite/Modal      | -          |
| Navigation       | ナビゲーションメニュー       | 計画中 | components/composite/Navigation | -          |
| Form             | フォームレイアウト           | 計画中 | components/composite/Form       | -          |
| Tabs             | タブ切り替え                 | 計画中 | components/composite/Tabs       | -          |
| Table            | データテーブル               | 計画中 | components/composite/Table      | -          |
| Pagination       | ページネーションコントロール | 計画中 | components/composite/Pagination | -          |
| Alert            | 通知・アラートメッセージ     | 計画中 | components/composite/Alert      | -          |
| Tooltip          | ツールチップ                 | 計画中 | components/composite/Tooltip    | -          |
| Accordion        | アコーディオンパネル         | 計画中 | components/composite/Accordion  | -          |
| Dropdown         | ドロップダウンメニュー       | 計画中 | components/composite/Dropdown   | -          |
| Breadcrumb       | パンくずリスト               | 計画中 | components/composite/Breadcrumb | -          |

## 状態の定義

コンポーネントの開発状態を以下のように定義します：

- **計画中**: 要件定義や設計前の初期状態
- **設計中**: デザイン仕様の作成中
- **実装中**: コード実装の進行中
- **レビュー中**: 実装完了後のレビューフェーズ
- **完了**: 実装・テスト・ドキュメント化が完了した状態
- **廃止予定**: 将来的に廃止される予定のコンポーネント
- **廃止**: 使用が推奨されないコンポーネント

## コンポーネント追加のガイドライン

新しいコンポーネントを追加する際は、以下の点を考慮してください：

1. **必要性**: 既存のコンポーネントで代替できないか確認
2. **汎用性**: 多くのユースケースで使用できる汎用的な設計を心がける
3. **整合性**: 既存のデザイン原則と一貫性を保つ
4. **アクセシビリティ**: WCAG AA レベルの基準を満たすよう設計・実装
5. **テスト可能性**: 自動テストが可能な設計にする

## 更新履歴

| 日付       | 更新者 | 変更内容 |
| ---------- | ------ | -------- |
| YYYY-MM-DD | 氏名   | 初版作成 |
