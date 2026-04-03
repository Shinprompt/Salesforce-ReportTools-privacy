# プライバシーポリシー / Privacy Policy

**最終更新日 / Last Updated: 2026-04-03**

---

## はじめに / Introduction

本プライバシーポリシーは、Chrome拡張機能「Salesforce ReportTools」（以下「本拡張機能」）におけるユーザーデータの収集、使用、取り扱い、保存、共有について説明します。本拡張機能をインストールまたは使用することにより、本プライバシーポリシーの内容に同意したものとみなします。

This Privacy Policy describes how the Chrome extension "Salesforce ReportTools" (the "Extension") collects, uses, handles, stores, and shares user data. By installing or using this Extension, you agree to the terms of this Privacy Policy.

---

## 収集する情報 / Information We Collect

### Salesforceセッション情報 / Salesforce Session Information

本拡張機能は、Salesforce APIとの通信を行うために、ブラウザのCookieからSalesforceのセッションID（sid）を読み取ります。このセッション情報は本拡張機能内でのAPI認証にのみ使用され、外部サーバーに送信・保存されることはありません。

The Extension reads Salesforce session IDs (sid) from browser cookies to communicate with Salesforce APIs. This session information is used solely for API authentication within the Extension and is never transmitted to or stored on external servers.

### Salesforceレポートメタデータ / Salesforce Report Metadata

本拡張機能は、SalesforceのAPI（Analytics API、SOAP Metadata API、Tooling API、sObject Describe API）を使用してレポートメタデータを取得・更新します。これらのデータはすべてユーザーのSalesforce組織とブラウザ間で直接やり取りされ、第三者のサーバーを経由しません。

The Extension uses Salesforce APIs (Analytics API, SOAP Metadata API, Tooling API, sObject Describe API) to retrieve and update report metadata. All data is exchanged directly between the user's Salesforce org and the browser, without passing through any third-party servers.

### 拡張機能の設定 / Extension Settings

本拡張機能は、ユーザーの設定情報（表示設定等）をブラウザのローカルストレージ（chrome.storage）に保存します。個人を特定する情報は保存されません。

The Extension stores user settings (display preferences, etc.) in the browser's local storage (chrome.storage). No personally identifiable information is stored.

### 利用統計情報 / Usage Statistics

本拡張機能は、サービス改善を目的として匿名の利用統計情報を収集します。ただし、ユーザーのSalesforce環境データ（レコード情報、組織情報等）や個人情報を取得・収集することはありません。

The Extension collects anonymous usage statistics for the purpose of service improvement. However, the Extension does not collect or retrieve users' Salesforce environment data (record data, organization information, etc.) or personal information.

### 収集しない情報 / Information We Do NOT Collect

本拡張機能は以下の情報を収集しません。 / The Extension does NOT collect:

- 個人を特定できる情報（名前、メールアドレス、住所等） / Personally identifiable information (name, email, address, etc.)
- 認証情報（パスワード、セキュリティトークン等） / Authentication credentials (passwords, security tokens, etc.)
- Salesforce環境データ（レコード情報、組織情報等） / Salesforce environment data (record data, organization information, etc.)
- 閲覧履歴、検索履歴 / Browsing or search history
- 財務情報、支払い情報 / Financial or payment information
- 健康に関する情報 / Health-related information
- 位置情報 / Location data

---

## 情報の使用目的 / How We Use Information

収集した情報は、以下の目的でのみ使用されます。 / Collected information is used only for the following purposes:

- **Salesforceセッション情報**: Salesforce APIへの認証に使用します。認証以外の目的では使用しません。 / Used for Salesforce API authentication only. Not used for any other purpose.
- **レポートメタデータ**: ブラウザのサイドパネルでの表示、編集、Excelエクスポート機能の提供に使用します。 / Used for display, editing, and Excel export in the browser side panel.
- **拡張機能の設定**: ユーザーの表示設定を保持するために使用します。 / Used to maintain user display preferences.
- **利用統計情報**: 拡張機能の改善および利用状況の分析に使用します。 / Used to improve the Extension and analyze usage.

---

## 情報の取り扱い / How We Handle Information

### データの処理方法 / Data Processing

- Salesforceから取得したメタデータは、ブラウザのメモリ上でリアルタイムに処理されます。 / Metadata retrieved from Salesforce is processed in real-time in browser memory.
- データの処理はすべてユーザーのブラウザ内で完結し、外部サーバーに送信されることはありません。 / All data processing is completed within the user's browser and is never sent to external servers.
- メタデータの編集・更新は、ユーザーのSalesforce組織に直接送信されます。 / Metadata edits and updates are sent directly to the user's Salesforce organization.

### データの保持期間 / Data Retention

- **Salesforceセッション情報**: ブラウザセッション中のみメモリに保持され、セッション終了時に破棄されます。本拡張機能による永続的な保存は行いません。 / Retained in memory only during the browser session and discarded when the session ends. No persistent storage by this Extension.
- **レポートメタデータ**: サイドパネルの表示中のみメモリに保持され、サイドパネルを閉じるかページを離れると破棄されます。 / Retained in memory only while the side panel is displayed, and discarded when the side panel is closed or the page is navigated away.
- **拡張機能の設定**: アンインストール時に自動的に削除されます。 / Automatically deleted upon uninstallation.
- **利用統計情報**: 匿名化された状態で分析サービスに保持されます。 / Retained in anonymized form by the analytics service.

---

## 情報の保存 / Data Storage

- 拡張機能の設定はブラウザのローカルストレージ（chrome.storage）に保存されます。 / Extension settings are stored in the browser's local storage (chrome.storage).
- Salesforceから取得したメタデータはブラウザのメモリ上で一時的に処理され、永続的に保存されることはありません。 / Metadata retrieved from Salesforce is temporarily processed in browser memory and is not persistently stored.
- 本拡張機能は独自のサーバーを持たず、ユーザーデータを外部サーバーに保存しません。 / The Extension does not operate its own servers and does not store user data on external servers.
- すべてのデータはユーザーのローカルデバイス上にのみ存在します。 / All data exists only on the user's local device.

---

## 情報の共有 / Information Sharing

### データを共有する関係者 / Parties We Share Data With

本拡張機能は、以下の関係者とのみデータを共有します。 / The Extension shares data only with the following parties:

| 関係者 / Party | 共有するデータ / Data Shared | 目的 / Purpose |
|---|---|---|
| **Salesforce, Inc.** (salesforce.com) | レポートメタデータ（取得・更新リクエスト）、セッションID（API認証） / Report metadata (retrieval/update requests), Session ID (API authentication) | レポートメタデータの閲覧・編集機能の提供 / Providing report metadata viewing and editing functionality |
| **Google LLC** (Google Analytics) | 匿名の利用統計情報 / Anonymous usage statistics | サービス改善 / Service improvement |

### 共有しないケース / Cases Where We Do NOT Share Data

- 本拡張機能は、上記以外の第三者にユーザーデータを共有、販売、転送しません。 / The Extension does not share, sell, or transfer user data to any third parties other than those listed above.
- 広告目的でのデータ共有は行いません。 / No data sharing for advertising purposes.
- ただし、法律に基づく要求がある場合は、法令に従いデータを開示することがあります。 / However, data may be disclosed in compliance with legal requirements when required by law.

---

## Cookieの使用 / Use of Cookies

本拡張機能は、SalesforceドメインのCookieからセッションIDを読み取ります。これはSalesforce APIへの認証に必要であり、それ以外の目的でCookieを使用することはありません。本拡張機能は独自のCookieを作成しません。

The Extension reads session IDs from Salesforce domain cookies. This is required for Salesforce API authentication and cookies are not used for any other purpose. The Extension does not create its own cookies.

---

## ユーザーの権利 / User Rights

- ユーザーはいつでも本拡張機能をアンインストールし、ローカルストレージに保存されたすべてのデータを削除できます。 / Users can uninstall the Extension at any time, which deletes all data stored in local storage.
- Cookieの管理はブラウザの設定から行えます。 / Cookie management can be done through browser settings.
- 本拡張機能はユーザーデータを外部サーバーに保存しないため、サーバー上のデータ削除リクエストは不要です。 / Since the Extension does not store user data on external servers, no server-side data deletion requests are necessary.
- データの取り扱いに関するご質問やご要望がある場合は、下記のお問い合わせ先までご連絡ください。 / For questions or requests regarding data handling, please contact us at the address below.

---

## セキュリティ / Security

本拡張機能はユーザーデータの保護に努めています。 / The Extension strives to protect user data.

- すべてのAPI通信はHTTPSを使用して暗号化されます。 / All API communications are encrypted using HTTPS.
- セッション情報はメモリ上でのみ使用され、永続的なストレージには保存されません。 / Session information is used only in memory and is not saved to persistent storage.
- ただし、インターネット上のデータ転送は100%安全であることを保証するものではありません。 / However, no method of data transmission over the Internet is guaranteed to be 100% secure.

---

## Chrome Web Store ユーザーデータポリシーの遵守 / Chrome Web Store User Data Policy Compliance

本拡張機能は、Chrome Web Storeのユーザーデータポリシーに準拠しています。ユーザーデータの使用は、本拡張機能の機能の提供および改善に限定されます。

The Extension complies with the Chrome Web Store User Data Policy. The use of user data is limited to providing and improving the functionality of this Extension.

---

## プライバシーポリシーの変更 / Changes to This Privacy Policy

本プライバシーポリシーは予告なく変更される場合があります。変更があった場合は、このページを更新し、最終更新日を変更します。重要な変更がある場合は、拡張機能の更新を通じてユーザーに通知します。

This Privacy Policy may be changed without notice. If changes are made, this page will be updated and the last updated date will be revised. For significant changes, users will be notified through extension updates.

---

## お問い合わせ / Contact Us

本プライバシーポリシーに関するご質問やご懸念がある場合は、以下までご連絡ください。
For questions or concerns regarding this Privacy Policy, please contact:

shin.prompt@gmail.com
