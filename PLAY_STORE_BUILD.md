# Money Diary – Expense Manager — Play Store Build Notes

- Web app: PWA, Supabase Auth, RLS-protected cloud data.
- Target Android API: 36+ for Google Play submissions from 31 Aug 2026.
- Recommended Android packaging: Trusted Web Activity (TWA) / Bubblewrap or PWABuilder, producing an AAB.
- Package name should be chosen once and kept stable, e.g. `com.smjgroup.moneydiary` if available.
- Before production: add the GitHub Pages URL and privacy policy URL to Play Console.
- If using a new personal Play developer account created after 13 Nov 2023, Google currently requires a closed test with at least 12 opted-in testers for 14 continuous days before production access.
