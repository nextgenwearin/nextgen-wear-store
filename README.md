# NEXTGEN WEAR + Razorpay
1. Install Node.js and run `npm install`.
2. Copy `.env.example` to `.env`.
3. Put Razorpay TEST Key ID and Key Secret in `.env`.
4. Run `npm start`, then open http://localhost:3000.
5. Test payment first.
6. For live mode use HTTPS, LIVE keys, payment capture and webhooks.
7. Never put RAZORPAY_KEY_SECRET in frontend code.
8. Replace the demo in-memory orders Map with a real database before production.
