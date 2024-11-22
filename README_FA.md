[![فارسی](https://img.shields.io/badge/زبان-فارسی-red)](README_FA.md)
[![English](https://img.shields.io/badge/Language-English-red)](README.md)

## 🚀 شروع سریع

1. یک [کلاینت متن‌باز](https://github.com/awesome-vpn/awesome-vpn/wiki/Clients) را در Github جستجو و نصب کنید
2. لینک‌های اشتراک زیر را در کلاینت کپی کنید
3. یک نود مناسب را انتخاب کرده و شروع به استفاده کنید

لینک پروژه:
- [https://github.com/awesome-vpn/awesome-vpn](https://github.com/awesome-vpn/awesome-vpn)

## 📥 لینک‌های اشتراک

لینک اشتراک اصلی:
- https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all

لینک‌های آینه (در صورت ناپایداری GitHub استفاده کنید):
- https://raw.kkgithub.com/awesome-vpn/awesome-vpn/master/all [بهینه‌شده برای: هنگ‌کنگ/ژاپن/سنگاپور]
- https://ghp.ci/https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all [بهینه‌شده برای: ژاپن/کره/آمریکا/اروپا]
- https://ghproxy.net/https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all [بهینه‌شده برای: ژاپن]

## 📊 تحلیل پروتکل‌های VPN و پروکسی

| لایه OSI | پروتکل | توضیحات |
|----------|--------|---------|
| لایه 2 - پیوند داده | PPTP | پروتکل تونل‌سازی نقطه به نقطه، قدیمی، امنیت پایین |
| لایه 2 - پیوند داده | L2TP | پروتکل تونل‌سازی لایه 2، اغلب با IPsec استفاده می‌شود |
| لایه 3 - شبکه | IPsec | امنیت پروتکل اینترنت، می‌تواند با L2TP یا به‌تنهایی استفاده شود |
| لایه 3 - شبکه | WireGuard | پروتکل VPN جدید و کارآمد، عملکرد برتر |
| لایه 3 - شبکه | GRE | کپسوله‌سازی مسیریابی عمومی، می‌تواند پروتکل‌های مختلف لایه شبکه را کپسوله کند |
| لایه 4 - انتقال | TUIC | TCP بر روی UDP، پروتکل لایه انتقال مبتنی بر QUIC |
| لایه 4 - انتقال | Hysteria | پروتکل انتقال شبکه با سرعت بالا مبتنی بر QUIC |
| لایه 4 - انتقال | Hysteria2 | نسخه بهبود یافته Hysteria، کارآمدتر و امن‌تر |
| لایه 4 - انتقال | QUIC | اتصالات اینترنتی UDP سریع، توسعه‌یافته توسط Google |
| لایه 5 - جلسه | SOCKS4 | پروتکل ساده عبور از فایروال، بدون پشتیبانی از احراز هویت |
| لایه 5 - جلسه | SOCKS5 | پروتکل پروکسی جهانی که از احراز هویت و UDP پشتیبانی می‌کند |
| لایه 5 - جلسه | SSL/TLS | لایه سوکت‌های امن/امنیت لایه انتقال، رمزگذاری برای لایه کاربرد فراهم می‌کند |
| لایه 7 - کاربرد | OpenVPN | سیستم VPN که از کتابخانه OpenSSL برای رمزگذاری استفاده می‌کند |
| لایه 7 - کاربرد | Shadowsocks | پروتکل پروکسی رمزگذاری شده سبک |
| لایه 7 - کاربرد | ShadowsocksR | نسخه گسترش‌یافته Shadowsocks، ویژگی‌هایی مانند مبهم‌سازی اضافه می‌کند |
| لایه 7 - کاربرد | VMess | پروتکل انتقال رمزگذاری شده مبتنی بر TLS، پیشنهاد شده توسط پروژه V2Ray |
| لایه 7 - کاربرد | VLESS | نسخه ساده‌شده VMess، کاهش سربار رمزگذاری |
| لایه 7 - کاربرد | Trojan | پروتکل پروکسی که به‌عنوان ترافیک HTTPS ظاهر می‌شود |
| لایه 7 - کاربرد | Trojan-Go | پیاده‌سازی Go از پروتکل Trojan، ویژگی‌هایی مانند WebSocket اضافه می‌کند |
| لایه 7 - کاربرد | پروکسی HTTP | نوع پروکسی پایه، معمولاً رمزگذاری نشده |
| لایه 7 - کاربرد | پروکسی HTTPS | پروکسی HTTP رمزگذاری شده، امنیت بهتری فراهم می‌کند |
| لایه 7 - کاربرد | تونل SSH | ایجاد تونل‌های رمزگذاری شده با استفاده از پروتکل SSH |
| لایه 7 - کاربرد | Tor | شبکه ارتباطی ناشناس، حریم خصوصی بالا از طریق رمزگذاری چندلایه و انتقال فراهم می‌کند |
| لایه 7 - کاربرد | Naive | پروتکل پروکسی HTTPS مبتنی بر پشته شبکه Chromium |
| لایه 7 - کاربرد | Brook | پروتکل پروکسی ساده چندپلتفرمی |
| لایه 7 - کاربرد | Shadowtls | پروتکلی که ترافیک Shadowsocks را به‌عنوان ترافیک TLS ظاهر می‌کند |
| لایه 7 - کاربرد | Reality | پروتکل پروکسی جدید مبتنی بر TLS 1.3، قابلیت ضد شناسایی بهتری فراهم می‌کند |
| لایه 7 - کاربرد | WebSocket | پروتکلی که ارتباط دوطرفه کامل بر روی یک اتصال TCP واحد فراهم می‌کند |

## ⚠️ چالش‌های فعلی

بسیاری از کلاینت‌های VPN یک‌کلیکی با مشکلات زیر مواجه هستند:
- مشکلات اتصال به دلیل دامنه‌ها/IP های مسدود شده
- عدم دسترسی در فروشگاه‌های برنامه
- پرداخت‌های اجباری یا نسخه‌های آزمایشی محدود

## 🔬 مأموریت ما

ما در حال تحقیق بر روی کلاینت‌های VPN قدیمی هستیم تا یک راه‌حل رایگان و قابل اعتماد چندپلتفرمی توسعه دهیم. هدف ما ایجاد یک برنامه است که ارائه دهد:

- استفاده رایگان و نامحدود به‌صورت دائمی
- اتصالات پایدار
- پشتیبانی از همه پلتفرم‌ها
- پشتیبانی از چندین پروتکل پروکسی
- پشتیبانی از چندین روش رمزگذاری
- نسخه موبایل روش‌های نصب و به‌روزرسانی خارج از فروشگاه‌های برنامه رسمی را فراهم می‌کند

## ⚖️ سلب مسئولیت

این پروژه فقط برای اهداف آموزشی و تحقیقاتی است. کاربران مسئولیت رعایت قوانین و مقررات محلی را در هنگام استفاده از این منابع بر عهده دارند.