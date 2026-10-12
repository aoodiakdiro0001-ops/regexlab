# 🧪 RegexLab — RegEx & Payload Tester (MIT)

Interactive lab for developers and authorized pentesters. UI in EN/TR/AR.
Static single file + README. **Authorized testing only.**

## Tools

- **🧪 RegEx Lab:** live match highlighting + group tables, preset library
  (email, URL, IPv4, CVE-ID, JWT...), replace mode, **ReDoS heuristic
  warning** (nested quantifiers), 500-match cap, empty-match guard.
- **💥 Payload Lab:** 23 standard test strings (XSS/SQLi/SSTI/Path/CMDi/
  XXE/SSRF/Redirect/LFI) with instant URL/double-URL/base64/HTML variants
  + copy. **WAF check** runs every payload against YOUR pattern.
- **🔀 Encoder:** URL, double-URL, URL-decode, base64 ⇄, hex, HTML entities,
  `\uXXXX`, `String.fromCharCode()`, UPPER, MiXeD.
- **🛠️ Pro Toolset:** Burp/ZAP/BrowserStack/regex101/CyberChef/Probely
  cards with referral support (`CONFIG.refs`).

## Money & contact

- `CONFIG.ads` (AdSense/Carbon): top + left/right sticky side rails
  (dismissible, hidden on mobile).
- Donate: BTC + USDT-TRC20 live.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd regexlab
python3 -m http.server 8080
```

## License

MIT. Test only systems you own or are authorized to test.

## Telegram (@BaranScanBot)

- Footer'da herkese açık "Telegram" butonu (`t.me/BaranScanBot`) — ziyaretçi
  doğrudan bota yazar, ek ayar gerekmez.
- Sipariş/satış bildirimleri (`tgSend`) yalnızca `CONFIG`... `TG.chat`
  doluysa sahibine gider. Chat ID'yi @userinfobot'tan alıp `TG.chat`e yazın.
- ⚠️ **GÜVENLİK:** Bot tokeni herkese açık istemci kodundadır; kaynağı
  gören herkes bot adına mesaj gönderebilir. Kötüye kullanımda BotFather'dan
  tokeni yenileyin ve asla bu botla hassas işlem yapmayın. Gerçek çözüm:
  backend proxy.
