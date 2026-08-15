# Tinbany Scanner 1.0.0

Native Android companion for Tinbany Bale AI Agent v1.9.0.

## Requirements
- Android 6.0+ (API 23)
- Google Play services
- HTTPS WordPress site with Tinbany Bale AI Agent v1.9.0+

## Pairing
1. In Bale, a user with `update_prices` permission taps `📱 اتصال اسکنر اندروید`.
2. The bot returns a six-digit code valid for 10 minutes.
3. Open Tinbany Scanner, enter the site URL and pairing code.
4. The app stores a random device token locally. The pairing code itself is single-use.

## Scan flow
1. Tap `📷 اسکن بارکد`.
2. Google Code Scanner opens natively (not in Bale WebView).
3. Scan one or more barcodes; duplicates are ignored.
4. Tap `✅ ارسال به بله و تعیین قیمت`.
5. The existing bulk-price conversation continues in Bale.

## Build
Open the folder in a current Android Studio. The project uses AGP 9.3.0, Java 17, compileSdk 36, and Google Code Scanner 16.1.0.
