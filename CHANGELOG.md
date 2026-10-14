# Changelog

## v1.0.0
- CHOST Panel: PasarGuard + Xray core + nginx in one Railway service (port 8080)
- Zero-touch setup: owner, core, 6 configs, hosts on the Railway domain, 2 groups, 10 templates, reseller role
- Two groups: 𝗖𝗛𝗢𝗦𝗧 VIP (Turbo, Stream, Ultra) and 𝗖𝗛𝗢𝗦𝗧 GAME (Gaming, Call, Stable)
- Config names use clean symbols only (✦ for VIP, ◆ for GAME); older lightning-bolt names are still detected by the subscription page
- 6 really different configs: VLESS-WS, VMess-WS, VLESS-HTTPUpgrade, Trojan-WS, all TLS 443 with early data
- New CHOST subscription page: liquid gold usage orb, live countdown, real ping test, auto device detection (phone / desktop), one-tap import, built-in QR, Persian and English
- Works in every Railway region: listens on IPv4 and IPv6 (auto IPv4-only fallback), longer start-up grace for slow regions, region shown in the logs
- Sidebar "پنل نمایندگی" (owner only): a native page inside the panel with stats, search, table / mobile cards and row actions; create reseller panels with a data quota, top up or set quota, change password, enable/disable, delete; login info ready to copy
- Login page "دسترسی مالک": new owner key dialog (CH-XXXX-XXXX-XXXX, 5 minutes, one use, paste button, password strength, any password from 4 characters, brute-force lock)
- Bot wallet: card-to-card top up, instant buy/renew from balance, automatic refund on failure
- Referral system: personal invite link, commission % to the inviter wallet
- Admin user management in the bot: search by ID/username, add/subtract balance, direct message, ban/unban
- Faster bot start (settings apply within seconds); fixed admin menu and back buttons
- Telegram sales bot: sidebar page "ربات تلگرام" (token + admin IDs, live status, sales numbers, test message). In the bot: plans, prices, card number, texts, channel + force join, pending receipts, broadcast, open/close sales. Users: buy, card-to-card receipt, auto-created subscription, renew, my subscriptions, help, support
- PasarGuard donation popup and "Support us" menu item removed; a CHOST creator card with the official channel (@CHOST543) shows once per login
- Bot: discount codes (percent, usage cap, once per user), one-time free test account, renewal reminders (low data / 3 days left), full daily backup to the admins (panel DB + bot DB + install keys) and on-demand backup
- Bilingual: every CHOST page, dialog, toast and server message follows the panel language (Persian / English) live, with the right text direction
- Dashboard: clean menu, password change in the "امنیت حساب" page, 5-minute owner key, self-healing core and watchdog
