[English](README.md) | 繁體中文

<p align="center"><img src="https://massgrave.dev/img/logo_small.png" alt="MAS Logo"></p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.</p>

<hr>
  
## 如何啟動Windows/Office/擴充安全性更新(ESU)？

### 方法1-PowerShell❤️

1. 按一下 **開始功能表**，輸入 `PowerShell`，然後將其開啟。

2. 複製並貼上下面的程式碼，然後按 **Enter。 **
   - 對於 **Windows 8.1、10 和 11**：
     ```
     irm https://get.activated.win | iex
     ```
如果上述內容被封鎖（被 ISP/DNS），請嘗試以下操作（需要更新 Windows 10 或 11）：
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
	 ```
	- **腳本未啟動？使用下面列出的方法 2。 **

3. 在出現的選單中，鍵入與 **綠色** 選項之一對應的數字。

---

### 方法 2 - 傳統（Windows Vista 及更高版本）

1.   下載腳本：
      *   [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true)（直接腳本）
      *   [**MAS_AIO.zip**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip)（如果直接腳本被您的瀏覽器阻止）
2.   運行`MAS_AIO.cmd` 文件。
3.   在出現的選單中，鍵入與 **綠色** 選項之一對應的數字。

---

> [!TIP]
> - 一些 ISP/DNS 提供者阻止訪問我們的網域。您可以透過在瀏覽器中啟用[DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/)來繞過此問題。
> - **遇到麻煩**？請造訪我們的[troubleshooting page](https://massgrave.dev/troubleshoot) 或在[GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues) 上提出問題。

> [!NOTE]
>
> - PowerShell 中的`irm` 命令從指定的URL 下載腳本，`iex` 命令執行該腳本。
> - 在執行命令之前務必仔細檢查 URL，並在手動下載檔案時驗證來源是否可信。
> - 警惕第三方透過更改 PowerShell 命令中的 URL 來傳播偽裝成 MAS 的惡意軟體。

---

<div align="center">
	
### 首頁 - [https://massgrave.dev/](https://massgrave.dev/)
  
[![1.1]][1]
[![1.2]][2]
[![1.3]][3]
[![1.4]][4]
[![1.5]][5]
[![1.6]][6]
[![1.7]][7]

[1.1]：https://massgrave.dev/img/logo_discord.png（無需註冊即可與我們聊天）
[1.2]：https://massgrave.dev/img/logo_reddit.png（Reddit）
[1.3]：https://massgrave.dev/img/logo_bluesky.png（藍天）
[1.4]：https://massgrave.dev/img/logo_x.png（推特）

[1.5]：https://massgrave.dev/img/logo_github.png（GitHub）
[1.6]：https://massgrave.dev/img/logo_azuredevops.png（AzureDevOps）
[1.7]: https://massgrave.dev/img/logo_gitea.png (自架 Git)

[1]：https://discord.gg/j2yFsV5ZVC
[2]：https://www.reddit.com/r/MAS_Activator
[3]：https://bsky.app/profile/massgrave.dev
[4]：https://twitter.com/massgravel
[5]：https://github.com/massgravel/Microsoft-Activation-Scripts
[6]：https://dev.azure.com/massgrave/_git/Microsoft-Activation-Scripts
[7]：https://git.activated.win/Microsoft-Activation-Scripts

---

最新版本：3.12
發布日期：2026 年 7 月 4 日
