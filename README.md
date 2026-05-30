# WA-Radar-Server 

سيرفر خلفي (Backend) يقوم بمراقبة الرسائل المحذوفة في واتساب وإعادة توجيهها فوراً إلى بوت تليجرام.

## التقنيات
- Node.js
- whatsapp-web.js
- Puppeteer
- Telegram Bot API

## التشغيل
1. قومي بتثبيت المتطلبات: `npm install`
2. أضيفي ملف `.env` وضعي فيه `TG_TOKEN` و `TG_CHAT_ID`.
3. شغلي السيرفر: `npm start`
