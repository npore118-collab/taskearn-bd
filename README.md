# TaskEarn BD

A starter web application for a transparent task/reward platform.

## Included
- Responsive landing page
- User registration/login
- User dashboard and balance
- Task creation/completion
- Withdrawal requests
- Referral code
- Membership tiers presented as feature access (not guaranteed returns)
- Fair random spin with published prize probabilities
- Single-owner Super Admin dashboard
- Admin task management and withdrawal approval/rejection
- SQLite database

## Run
1. Install Node.js 18+.
2. Copy `.env.example` to `.env` and change the admin credentials and session secret.
3. Run:
   npm install
   npm start
4. Open http://localhost:3000

## Production notes
- Put the site behind HTTPS.
- Use a strong random SESSION_SECRET and strong admin password.
- Add real payment-provider verification/webhooks before enabling live deposits or withdrawals.
- Have the business terms, privacy policy, refund rules, tax obligations, and local legal requirements reviewed before launch.
- Do not promise fixed daily returns for deposits or manipulate games/spins.
