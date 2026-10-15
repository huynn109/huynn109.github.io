---
layout: null
permalink: /p2p-rate/privacy/
---
<!-- P2P Rate's privacy policy (handoff docs/privacy.md, with Firebase added in Phase 6). Published on GitHub Pages
     as https://huynn109.github.io/p2p-rate/privacy/: copy this file to huynn109.github.io/p2p-rate/privacy.md. -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>P2P Rate · Privacy policy</title>
<style>
:root { color-scheme: light dark; --bg: #f3f3f6; --fg: #101014; --muted: #5b6370; --link: #00684b; --line: #dde3ea; }
@media (prefers-color-scheme: dark) {
  :root { --bg: #0a0a0c; --fg: #e8ecf1; --muted: #9aa4b1; --link: #5ee6b8; --line: #262c35; }
}
body { margin: 0; background: var(--bg); color: var(--fg); font: 16px/1.6 -apple-system, "Segoe UI", Roboto, sans-serif; }
main { max-width: 720px; margin: 0 auto; padding: 32px 16px 64px; }
h1 { font-size: 1.8em; line-height: 1.2; }
h2 { font-size: 1.2em; margin-top: 2em; }
a { color: var(--link); }
hr { border: 0; border-top: 1px solid var(--line); margin: 48px 0; }
</style>
<main markdown="1">

[English](#en) · [Tiếng Việt](#vi)

# P2P Rate · Privacy policy {#en}

Effective 13 October 2026 · Applies to P2P Rate for Android and iOS, made by Nguyen Nguyen Huy, an individual
developer in Vietnam ("we").

## In short

P2P Rate has no account and no server of ours. The app reads the exchanges' public P2P pages directly from your
device, keeps your settings on your device, shows ads through Google AdMob, sells one in-app purchase through the App
Store or Google Play, and sends crash reports and fetches its remote settings through Google Firebase.

## What the app does with data

**No account, no server of ours.** You never sign in, and we run no server that receives your data. We do not collect
your name, email, phone number or contacts.

**Prices are read from your device.** To show prices, the app requests the public P2P pages of the exchanges you have
switched on (Binance, OKX, Bybit, KuCoin, HTX, Bitget, MEXC) directly from your device. Like any website visit, those
exchanges receive your device's IP address and a browser User-Agent string. Their handling of that data is governed by
their own privacy policies. The app sends them no information about you beyond what the request itself carries (the
asset, currency, side and amount filters you chose).

**Settings stay on the device.** Your choices (side, asset, currency, filters, enabled exchanges, theme, language, and
whether ads were removed) are stored only on your device and are deleted when you uninstall the app.

**Opening an ad.** When you tap "Open on …", the exchange's app or website opens. From then on you are on the
exchange's service, under its terms and privacy policy.

## Crash reports and remote settings (Google Firebase)

If the app crashes, or an exchange refuses so many requests that the app stops asking it for a while, Firebase
Crashlytics sends a report: what the app was doing (the stack trace), the device model, the system and app versions,
an identifier of this installation, which exchange paused, why and for how long, and how many times each exchange
refused the app's requests. It contains nothing about your trades, your settings or you.

Firebase Remote Config lets us pause an exchange for everyone, for example when it blocks the app, without a new
version: the app fetches these settings with an identifier of this installation.

Google processes this data under its terms: <https://firebase.google.com/support/privacy>

## Advertising (Google AdMob)

The free version shows one banner ad served by Google AdMob. AdMob may collect your device's advertising identifier
(Google Advertising ID on Android, IDFA on iOS), IP address and approximate location, and may use cookies or similar
technologies, to show and measure ads.

- Before personalised ads are shown where the law requires it (for example in the EEA, the UK and Switzerland), the
  app asks for your consent through Google's consent form. You can change your choice at any time in Settings
  ("Ad privacy").
- On iOS, the app asks for permission to track (App Tracking Transparency) before the IDFA is used. If you decline,
  AdMob shows non-personalised ads.
- How Google uses data from apps that use its services: <https://policies.google.com/technologies/partner-sites> ·
  Google privacy policy: <https://policies.google.com/privacy>

Removing ads with the in-app purchase stops the AdMob SDK from loading ads.

## The in-app purchase

"Remove ads" is bought through the App Store or Google Play; we never see your payment details. To check and restore
the purchase, the app uses RevenueCat, which receives an anonymous app user ID, the store receipt and basic device
data. RevenueCat privacy policy: <https://www.revenuecat.com/privacy>

## Children

P2P Rate is not directed at children under 13 (or the age required by your country) and does not knowingly collect
their data.

## Your rights

Because we hold no personal data on a server of ours, there is nothing for us to export or delete. To reset the app,
uninstall it. For data held by Google (AdMob, Firebase), RevenueCat, Apple or Google Play, use their privacy tools
linked above.

## Changes

If this policy changes, the new version is published here with a new effective date.

## Contact

[huynn109@gmail.com](mailto:huynn109@gmail.com) · Nguyen Nguyen Huy, Vietnam

## Disclaimer

Prices shown in P2P Rate come from third parties (the exchanges' public P2P ads), may be a few seconds old, and are
shown for information only. They are not investment, financial or trading advice. P2P Rate does not trade, hold funds
or act for you on any exchange. P2P Rate is not affiliated with, endorsed or sponsored by any exchange; exchange names
and trademarks belong to their owners.

---

# P2P Rate · Chính sách quyền riêng tư {#vi}

Có hiệu lực từ 13 tháng 10 năm 2026 · Áp dụng cho P2P Rate trên Android và iOS, do Nguyễn Nguyên Huy, nhà phát triển
cá nhân tại Việt Nam ("chúng tôi") làm.

## Tóm tắt

P2P Rate không có tài khoản và không có máy chủ riêng. App đọc trang P2P công khai của các sàn trực tiếp từ thiết bị
của bạn, lưu cài đặt trên thiết bị, hiện quảng cáo qua Google AdMob, bán một gói mua trong app qua App Store hoặc
Google Play, và gửi báo cáo lỗi, lấy cài đặt từ xa qua Google Firebase.

## App làm gì với dữ liệu

**Không tài khoản, không máy chủ riêng.** Bạn không bao giờ đăng nhập, và chúng tôi không chạy máy chủ nào nhận dữ
liệu của bạn. Chúng tôi không thu thập tên, email, số điện thoại hay danh bạ.

**Giá được đọc từ thiết bị của bạn.** Để hiện giá, app gửi yêu cầu tới trang P2P công khai của các sàn bạn đang bật
(Binance, OKX, Bybit, KuCoin, HTX, Bitget, MEXC) trực tiếp từ thiết bị. Như khi bạn mở một trang web, các sàn đó nhận
địa chỉ IP của thiết bị và chuỗi User-Agent của trình duyệt; việc họ xử lý dữ liệu này theo chính sách quyền riêng tư
của chính họ. App không gửi cho sàn thông tin gì về bạn ngoài nội dung của chính yêu cầu (tài sản, tiền tệ, chiều mua
bán và số tiền bạn chọn để lọc).

**Cài đặt nằm trên thiết bị.** Các lựa chọn của bạn (chiều, tài sản, tiền tệ, bộ lọc, các sàn đang bật, giao diện,
ngôn ngữ, và việc đã gỡ quảng cáo hay chưa) chỉ được lưu trên thiết bị và bị xoá khi bạn gỡ app.

**Mở một ad.** Khi bạn chạm "Mở trên …", app hoặc trang web của sàn sẽ mở. Từ đó bạn đang dùng dịch vụ của sàn, theo
điều khoản và chính sách quyền riêng tư của sàn.

## Báo cáo lỗi và cài đặt từ xa (Google Firebase)

Nếu app gặp lỗi và đóng, hoặc một sàn từ chối nhiều yêu cầu đến mức app tạm ngưng hỏi sàn đó một lúc, Firebase
Crashlytics gửi một báo cáo: app đang làm gì lúc đó (stack trace), đời máy, phiên bản hệ điều hành và app, một mã định
danh của lần cài app này, sàn nào bị tạm dừng, vì sao và trong bao lâu, và số lần mỗi sàn từ chối yêu cầu của app. Báo
cáo không chứa gì về giao dịch, cài đặt hay thông tin của bạn.

Firebase Remote Config cho phép chúng tôi tạm dừng một sàn cho mọi người dùng, ví dụ khi sàn chặn app, mà không cần
phát hành bản mới: app lấy các cài đặt này kèm một mã định danh của lần cài app.

Google xử lý dữ liệu này theo điều khoản của họ: <https://firebase.google.com/support/privacy>

## Quảng cáo (Google AdMob)

Bản miễn phí hiện một banner quảng cáo do Google AdMob cung cấp. AdMob có thể thu thập mã định danh quảng cáo của thiết
bị (Google Advertising ID trên Android, IDFA trên iOS), địa chỉ IP và vị trí gần đúng, và có thể dùng cookie hoặc công
nghệ tương tự, để hiện và đo lường quảng cáo.

- Trước khi hiện quảng cáo cá nhân hoá ở nơi luật yêu cầu (ví dụ EEA, Vương quốc Anh, Thuỵ Sĩ), app xin sự đồng ý của
  bạn qua biểu mẫu của Google. Bạn có thể đổi lựa chọn bất cứ lúc nào trong Cài đặt ("Quyền riêng tư quảng cáo").
- Trên iOS, app xin phép theo dõi (App Tracking Transparency) trước khi dùng IDFA. Nếu bạn từ chối, AdMob hiện quảng
  cáo không cá nhân hoá.
- Cách Google dùng dữ liệu từ các app dùng dịch vụ của Google: <https://policies.google.com/technologies/partner-sites>
  · Chính sách quyền riêng tư của Google: <https://policies.google.com/privacy>

Gỡ quảng cáo bằng gói mua trong app sẽ dừng việc tải quảng cáo của AdMob.

## Gói mua trong app

"Gỡ quảng cáo" được mua qua App Store hoặc Google Play; chúng tôi không bao giờ thấy thông tin thanh toán của bạn. Để
kiểm tra và khôi phục giao dịch, app dùng RevenueCat; RevenueCat nhận một mã người dùng ẩn danh, biên nhận của cửa hàng
và dữ liệu thiết bị cơ bản. Chính sách quyền riêng tư của RevenueCat: <https://www.revenuecat.com/privacy>

## Trẻ em

P2P Rate không dành cho trẻ em dưới 13 tuổi (hoặc độ tuổi theo luật nước bạn) và không cố ý thu thập dữ liệu của trẻ
em.

## Quyền của bạn

Vì chúng tôi không giữ dữ liệu cá nhân nào trên máy chủ riêng, không có gì để chúng tôi xuất ra hay xoá. Để đặt lại
app, hãy gỡ app. Với dữ liệu do Google (AdMob, Firebase), RevenueCat, Apple hoặc Google Play giữ, hãy dùng công cụ
quyền riêng tư của họ ở các liên kết trên.

## Thay đổi

Nếu chính sách thay đổi, bản mới sẽ được đăng ở đây với ngày hiệu lực mới.

## Liên hệ

[huynn109@gmail.com](mailto:huynn109@gmail.com) · Nguyễn Nguyên Huy, Việt Nam

## Miễn trừ trách nhiệm

Giá trong P2P Rate lấy từ bên thứ ba (các ad P2P công khai của sàn), có thể đã cũ vài giây và chỉ để tham khảo. Đây
không phải lời khuyên đầu tư, tài chính hay giao dịch. P2P Rate không giao dịch, không giữ tiền và không thay bạn hành
động trên sàn nào. P2P Rate không liên kết với sàn nào và không được sàn nào tài trợ hay xác nhận; tên và nhãn hiệu của
các sàn thuộc về chủ sở hữu của chúng.

</main>
