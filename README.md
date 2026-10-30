# Kalshi 15-Minute Bot (website)

The web page for a private bot that trades Kalshi's 15-minute Bitcoin and Ethereum markets for invited users with their own Kalshi accounts. The trading engine and data live on Supabase; this repository only holds the static page. It contains no secrets: the Supabase key in `index.html` is the public anon key, and every table is protected by row-level security.
