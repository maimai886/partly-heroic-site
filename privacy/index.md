---
layout: doc
lang: zh-Hant
key: "privacy/"
legal: true
title: "隱私權政策｜晴時多勇者"
heading: "晴時多勇者 隱私權政策"
description: "晴時多勇者（iOS）的隱私權政策：本遊戲不收集任何個人資料。"
---
{% comment %}
Source: game repo docs/store/privacy.md (draft 2026-10-08, compliance-officer + localization-specialist; not lawyer-reviewed).
Website changes vs. the source: §7 covers the GitHub Issues support page (no support email yet), new §8 covers this website.
Placeholders (operator, email, effective date) come from _config.yml.
{% endcomment %}
這份政策說明 iOS App「晴時多勇者」（以下稱「本遊戲」）如何處理你的資料。本遊戲由{{ site.operator[page.lang] }}（以下稱「我們」）營運。

## 1. 簡短版

**本遊戲不收集任何個人資料。** 本遊戲沒有帳號、不連網路、沒有廣告、沒有分析或追蹤工具。你的遊戲進度只存在你自己的裝置上，我們看不到，也拿不到。

## 2. 我們不收集的資料

本遊戲不收集、不傳送、不分享以下任何資料：姓名、電子郵件、電話、生日、位置、聯絡人、照片、裝置識別碼、廣告識別碼（IDFA）、IP 位址、使用紀錄、購買紀錄或當機紀錄。

本遊戲不使用任何第三方的分析、廣告、登入或追蹤服務，也不會跨 App 或網站追蹤你。

## 3. 存在你裝置上的資料

- **遊戲存檔：** 關卡、英雄等級、裝備、金幣等進度，存在你裝置上本遊戲自己的儲存空間。存檔不會傳給我們或任何人。
- **裝置備份：** 如果你開啟 iCloud 備份或電腦備份，Apple 的備份功能可能會一併備份存檔。這是 Apple 提供的服務，適用 Apple 的隱私權政策，我們無法存取。
- **刪除方式：** 刪除本遊戲，存檔就會從裝置上刪除。我們沒有存檔的副本，所以刪除後無法還原。

## 4. 子母畫面

本遊戲用 iOS 的子母畫面（Picture in Picture）顯示遊戲畫面。子母畫面的內容由本遊戲在你的裝置上即時產生，不連網路、不錄影、不讀取其他 App 的內容。

## 5. Apple 提供的資料

如果你在裝置設定裡選擇「與 App 開發者分享」分析資料，Apple 可能會把匿名的當機報告和使用統計提供給我們。這由你在 iOS 設定中決定，可以隨時關閉（設定 › 隱私權與安全性 › 分析與改進）。我們只用這些資料修正錯誤。

## 6. 兒童

本遊戲不收集任何人的個人資料，包括兒童。

## 7. 你聯絡我們時

- **問題回報頁（GitHub Issues）：** 目前客服透過本網站在 GitHub 上的問題回報頁進行。你送出的回報會**公開**顯示在 GitHub 上，包含你的 GitHub 帳號名稱和你寫的內容，並適用 GitHub 的隱私權聲明。請不要在回報裡寫姓名、電子郵件、電話、地址等個人資料。我們只用回報內容處理你的問題。想刪除自己的回報時，在回報裡留言告訴我們，我們會刪除。
{%- if site.support_email != "" %}
- **電子郵件：** 如果你寄信到客服信箱，我們會收到你的電子郵件地址和信件內容，只用來回覆你的問題，問題處理完畢後 12 個月內刪除。不想留下資料的話，信裡不必提供姓名或其他個人資料。
{%- endif %}

## 8. 本網站

本網站放在 GitHub Pages 上。本網站不使用 Cookie，沒有分析、廣告或追蹤工具，也不從其他網站載入字型或程式。GitHub 是主機服務商，可能為了安全和維運記錄訪客的 IP 位址等技術資料，適用 [GitHub 的隱私權聲明](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)。

## 9. 政策變更

如果本遊戲之後加入需要處理資料的功能（例如帳號或雲端存檔），我們會在推出該功能的同一個版本前更新這份政策，在本頁標示新的生效日期，並在 App 內通知。新功能推出前已經存在的資料不受影響。

## 10. 聯絡我們

- 客服：[客服頁]({{ '/support/' | relative_url }})（[問題回報]({{ site.issues_url }})）
{%- if site.support_email != "" %}
- 客服信箱：<{{ site.support_email }}>
{%- endif %}
- 網站：<{{ site.url }}{{ site.baseurl }}/>

繁體中文版、日文版和英文版內容不一致時，以你使用的 App Store 店面語言的版本為準（台灣：繁體中文；日本：日文；其他店面：英文）。
