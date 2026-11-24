# Lotteria Social Pulse — Free static dashboard

## Deploy with Cloudflare Pages (Direct Upload)

1. Sign in to Cloudflare and open **Workers & Pages**.
2. Choose **Create application → Pages → Upload assets** (wording may vary).
3. Create a project named `lotteria-social-pulse`.
4. Upload the contents of this folder (the `index.html` file must be at the project root), or upload the ZIP archive.
5. Deploy. Cloudflare will provide a `*.pages.dev` URL.

## What this version does

- Static responsive dashboard shell.
- Clearly marks missing social data; no fabricated KPIs.
- Scope: Lotteria, KFC, Jollibee, McDonald's, Popeyes, Texas Chicken.
- Platforms: Facebook, TikTok, Instagram, Threads.
- UGC excluded from MVP.

## What is not configured

- No social listening provider or API credentials.
- No automatic social collection, 90-day backfill, or 3-hour scheduled refresh.
- No email notifications.
- This static page does not query the Supabase database yet.

Do not place API keys or secrets in `index.html` or any client-side file.
