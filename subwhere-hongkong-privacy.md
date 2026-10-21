# Subwhere Hong Kong 私隱政策

最後更新：2026 年 10 月 21 日

*English below.*

本私隱政策說明 Subwhere Hong Kong（主畫面上顯示為「Subwhere」；下稱「本 app」、「我們」）在你使用本 app 及其小工具（iOS 及 Android）時如何處理資料。

Subwhere Hong Kong 由 AppLand（Stefan Almqvist）發佈，總部設於瑞典。

聯絡：<applandapps@gmail.com>

## 簡要說明

本 app 不收集個人資料。沒有帳戶、沒有分析工具、沒有廣告，亦沒有追蹤。你的位置和相機影像絕不會傳送給我們。為顯示實時列車，本 app 會經由我們營運的一項小型服務下載港鐵資料。這些請求不含帳戶、識別碼或位置座標，我們亦不會保留任何請求記錄。擴增實境（AR）畫面使用 Apple 或 Google 的 AR 服務，其資料處理方式見下文「Apple 服務」及「Google 服務」。

## 本 app 在你裝置上使用的資料

**相機影像。** 由裝置的擴增實境框架（iPhone 及 iPad 上的 Apple ARKit；Android 上的 Google Play Services for AR）用來顯示 AR 畫面，並辨認你周圍的建築物，使列車與街道對齊。本 app 絕不會錄影、儲存或把相機影像傳送給我們。在 Android 上，Google 會處理相機資料以運行 AR 工作階段（見「Google 服務」）。

**位置。** 用來按你所在之處放置列車、找出最近的車站並為你指示方向，以及在 iPhone 及 iPad 上選擇小工具顯示的車站。本 app 只在你的裝置上使用你的位置，絕不會傳送給我們，不會儲存為位置記錄，亦不會分享或出售。在 Android 上，Google 會處理位置資料以運行 AR 工作階段（見「Google 服務」）。

**裝置動態感應及指南針方向。** 用於 AR 畫面及車站指南針，只在你的裝置上處理。

**保留在你裝置上的資料。** 為讓小工具毋須開啟本 app 也能運作，本 app 會保留港鐵車站及月台的名稱、最近車站及小工具所選車站的最新班次，以及最近一次讀取的路綫服務狀況。本 app 亦會記住你選擇的語言，以及你是否已看過簡介。這些資料都不會傳送給我們，並會在你刪除本 app 時一併刪除。

我們不使用任何分析工具、追蹤 SDK、廣告、當機報告服務或其他第三方資料收集。本 app 不使用廣告識別碼，亦不會在其他公司的 app 或網站上追蹤你。

## 小工具

Subwhere Hong Kong 提供可選用的小工具，顯示即將開出的班次。

在 iPhone 及 iPad 上，主畫面及鎖定畫面小工具會顯示你選擇的車站，或預設顯示離你最近的車站。為找出最近的車站，小工具會在你的裝置上讀取裝置位置，包括在本 app 關閉時。與本 app 一樣，你的位置只在裝置上用來計算哪個車站最近，絕不會儲存為記錄、傳送給我們、分享或出售。

在 Android 上，主畫面小工具顯示你選擇的車站，不會使用你的位置。

## 實時列車資料

列車到站時間及服務資訊來自香港鐵路有限公司的「港鐵下一班列車」數據，經香港政府資料一線通（DATA.GOV.HK）發佈。本 app 不會直接聯絡港鐵或 DATA.GOV.HK，而是向 AppLand 在 Cloudflare 上營運的一項小型服務發出請求；該服務向 DATA.GOV.HK 取得資料、加以儲存，再轉交本 app。這樣可大大減輕港鐵數據服務的負荷：無論有多少人使用本 app，每個車站最多每 30 秒只會被查詢一次。Subwhere Hong Kong 與香港鐵路有限公司並無關聯，亦未獲其認可。

這些請求不含帳戶、裝置識別碼或位置座標。大部分請求要求的是全網絡的到站時間或各路綫的服務狀況，對所有人都一樣。當小工具需要某一個車站的班次時，請求只會列出該車站的代號，不含任何關於你的資料。若車站由小工具自動選擇，那就是離你最近的車站。

與任何互聯網連線一樣，請求到達我們的服務時會附帶你裝置的 IP 位址，以便把回應傳回給你。我們不會保留請求或 IP 位址的記錄，亦不會用它們識別或追蹤任何人。Cloudflare 代我們處理這些連線資料，以提供及保護該服務，並受其私隱政策約束：<https://www.cloudflare.com/privacypolicy/>

港鐵及 DATA.GOV.HK 只會收到來自我們服務的請求，從不會收到來自你裝置的請求，因此看不到你的 IP 位址。

## Apple 服務（iPhone 及 iPad）

AR 畫面使用 Apple ARKit 的位置錨點（地理追蹤）。為對齊畫面，ARKit 會下載你所在地區的 Apple 地圖定位資料，並在你的裝置上與相機影像比對。Apple 表示不會有相機影像傳送到 Apple。實時地圖為 Apple 地圖（MapKit）。

Apple 可能透過這些服務、App Store 及 TestFlight 收集資料，詳情見其私隱政策：<https://www.apple.com/legal/privacy/>

## Google 服務（Android）

在 Android 上，本 app 以 Google 提供的 Google Play Services for AR（ARCore）運行，並受 Google 私隱政策約束。AR 畫面使用 ARCore 的 Geospatial API 找出你所站的確切位置：為運行此工作階段，Google 會處理感應器資料（例如相機及位置）。Google 說明 Google Play Services for AR 如何處理你的資料：<https://support.google.com/ar?p=how-google-play-services-for-ar-handles-your-data>

實時地圖為 Google 地圖（Maps SDK for Android）。

Google 可能透過這些服務及 Google Play 收集資料，詳情見其私隱政策：<https://policies.google.com/privacy>

## 測試版

如你透過 TestFlight 測試測試版，Apple 會與我們分享部分資料：測試版的當機記錄及使用資料、你的姓名和電郵地址（如我們以電郵邀請你；經公開連結加入則不會），以及你選擇傳送的意見及螢幕截圖。Apple 說明 TestFlight 如何處理資料：<https://www.apple.com/legal/privacy/data/en/test-flight/>

如你透過 Google Play 測試預先發佈版本，我們會知道我們加入測試人員名單的電郵地址，並會收到你選擇傳送的意見。

我們只會用這些資料測試及改善本 app，不會與任何人分享。

## 當機及效能報告

Apple 和 Google 可能會向我們提供本 app 的當機及效能報告，來源是在裝置設定中開啟了分享診斷資料的用戶。這些報告描述問題及裝置類型，而不是你的身分。我們只會用它們修正本 app 的問題。

## 電郵

如你電郵給我們，我們會收到你的電郵地址及訊息，只會用來回覆你，並會按你的要求刪除。

## 權限

本 app 會要求以下權限：

**相機**：AR 畫面需要使用。

**位置**：用來在你周圍放置列車及找出最近的車站。在 iPhone 及 iPad 上，小工具的最近車站模式亦會使用。

你可隨時更改這些權限：在 iPhone 及 iPad 上前往「設定」中的 Subwhere；在 Android 上前往「設定」>「應用程式」> Subwhere >「權限」。

## 你的權利

AppLand 負責本政策所述的個人資料。凡我們處理任何個人資料（上文所述的連線資料、測試版資料、當機報告及電郵），都是因為運行、測試及支援本 app 所需。我們保留的資料極少，通常沒有甚麼可供查閱、更正或刪除，但你可隨時以下列電郵地址向我們查詢。

如你身處香港，可向個人資料私隱專員公署投訴；如你身處歐盟或英國，亦可向資料保障機構投訴：瑞典（AppLand 所在地）的瑞典私隱保障局（IMY），或英國資訊專員辦公室（ICO）。

## 兒童

本 app 並非以 13 歲以下兒童為對象，亦不會向任何人收集個人資料。

## 政策變更

如我們更改本政策，會更新上方的「最後更新」日期。

## 聯絡

如有疑問，請電郵至 <applandapps@gmail.com>。

---

# Privacy Policy for Subwhere Hong Kong

Last updated: 21 October 2026

This Privacy Policy describes how Subwhere Hong Kong ("Subwhere" on your Home Screen; "the App", "we", "us") handles information when you use the App and its widgets on iOS and Android.

Subwhere Hong Kong is published by AppLand (Stefan Almqvist), based in Sweden.

Contact: <applandapps@gmail.com>

## Short version

The App does not collect personal data. There are no accounts, no analytics, no advertising and no tracking. Your location and your camera image are never sent to us. To show live trains, the App downloads MTR data through a small service we run. Those requests contain no account, no identifier and no location coordinates, and we keep no record of them. The augmented reality view uses Apple's or Google's AR services, which handle data as described under "Apple services" and "Google services".

## What the App uses on your device

**Camera feed.** Used by your device's augmented reality framework (Apple's ARKit on iPhone and iPad, Google Play Services for AR on Android) to show the augmented reality view and to recognise the buildings around you, so the trains line up with the street. The App never records, saves or sends the camera image to us. On Android, Google processes camera data to power the AR session (see "Google services").

**Location.** Used to place trains relative to where you are standing, to find your nearest station and point the way to it, and on iPhone and iPad to choose the station the widget shows. The App uses your location on your device. It is never sent to us, never stored as a location history, and never shared or sold. On Android, Google processes location data to power the AR session (see "Google services").

**Device motion and compass heading.** Used for the AR view and the station compass. Processed on your device only.

**Data kept on your device.** So the widget can work without opening the App, the App keeps the names of the MTR stations and their platforms, the latest departures for your nearest station and your widgets' stations, and the latest reading of the lines' service status. It also remembers your language choice and whether you have seen the introduction. None of this is sent to us, and it is deleted when you delete the App.

We do not use analytics, tracking SDKs, advertising, crash-reporting services or any other third-party data collection. The App does not use an advertising identifier and does not track you across other companies' apps or websites.

## Widgets

Subwhere Hong Kong offers optional widgets that show upcoming departures.

On iPhone and iPad, the Home Screen and Lock Screen widgets show either a station you choose or, by default, the station nearest you. To find the nearest station a widget reads your device's location on your device, including while the App is closed. As in the App, your location is used only on your device to work out which station is nearest. It is never stored as a history, sent to us, shared or sold.

On Android, the home-screen widget shows a station you choose. It does not use your location.

## Live train data

Train arrival times and service information come from MTR Corporation's Next Train data, published on the Hong Kong Government's DATA.GOV.HK. The App does not contact MTR or DATA.GOV.HK itself. It asks a small service that AppLand runs on Cloudflare, which fetches the data from DATA.GOV.HK, stores it and passes it on. This keeps the load on MTR's data service low: however many people use the App, each station is asked for at most once every 30 seconds. Subwhere Hong Kong is not affiliated with or endorsed by MTR Corporation.

These requests contain no account, no device identifier and no location coordinates. Most ask for the arrival times for the whole network or the service status of every line, which are the same for everyone. When a widget needs departures for a single station, the request names that station's code and nothing else about you. When the widget picks the station itself, that is the station nearest you.

Like any internet connection, a request reaches our service with your device's IP address, which is needed to send the answer back. We do not keep logs of requests or IP addresses, and we do not use them to identify or follow anyone. Cloudflare processes this connection data on our behalf to deliver and protect the service, under its privacy policy: <https://www.cloudflare.com/privacypolicy/>

MTR and DATA.GOV.HK receive requests only from our service, never from your device, so they do not see your IP address.

## Apple services (iPhone and iPad)

The AR view uses Apple's ARKit location anchors (geotracking). To line up the scene, ARKit downloads Apple Maps localisation data for the area you are in and matches it against the camera image on your device. Apple states that no camera images are sent to Apple. The live map is Apple Maps (MapKit).

Apple may collect data through these services, the App Store and TestFlight as described in its privacy policy: <https://www.apple.com/legal/privacy/>

## Google services (Android)

On Android, the App runs on Google Play Services for AR (ARCore), which is provided by Google and governed by the Google Privacy Policy. The AR view uses ARCore's Geospatial API to find exactly where you are standing: to power this session, Google processes sensor data (such as camera and location). Google explains how Google Play Services for AR handles your data here: <https://support.google.com/ar?p=how-google-play-services-for-ar-handles-your-data>

The live map is Google Maps (Maps SDK for Android).

Google may collect data through these services and Google Play as described in its privacy policy: <https://policies.google.com/privacy>

## Beta testing

If you test a beta version through TestFlight, Apple shares some information with us: crash logs and usage information from the beta, your name and email address if we invited you by email (not if you joined through a public link), and any feedback and screenshots you choose to send. Apple explains TestFlight's data handling here: <https://www.apple.com/legal/privacy/data/en/test-flight/>

If you test a pre-release version through Google Play, we know the email address we added to the tester list, and we receive any feedback you choose to send.

We use this information only to test and improve the App, and we do not share it with anyone.

## Crash and performance reports

Apple and Google may give us crash and performance reports about the App from people who have turned on diagnostics sharing in their device settings. These reports describe the problem and the type of device, not who you are. We use them only to fix problems in the App.

## Email

If you email us, we receive your email address and your message, and use them only to reply. We delete them on request.

## Permissions

The App will ask for permission to use:

**Camera** - needed for the AR view.

**Location** - needed to place trains around you and to find your nearest station. On iPhone and iPad it is also used by the widget's nearest-station mode.

You can change these at any time: on iPhone and iPad in Settings under Subwhere, and on Android in Settings under Apps, Subwhere, Permissions.

## Your rights

AppLand is responsible for the personal data described in this policy. Where we handle any (the connection data, beta testing information, crash reports and emails described above), we do so because it is needed to run, test and support the App. We keep so little that there is usually nothing for us to access, correct or delete, but you can ask us about any of it at the address below.

If you are in Hong Kong, you can complain to the Office of the Privacy Commissioner for Personal Data (PCPD). If you are in the EU or the UK, you can complain to a data protection authority: in Sweden, where AppLand is based, the Swedish Authority for Privacy Protection (IMY); in the UK, the Information Commissioner's Office (ICO).

## Children

The App is not directed at children under 13, and it does not collect personal data from anyone.

## Changes to this policy

If we change this policy, we will update the "Last updated" date above.

## Contact

Questions? E-mail <applandapps@gmail.com>.
