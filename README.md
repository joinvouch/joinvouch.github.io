# Vouch · Register your interest

The page at https://joinvouch.github.io: people leave their name, email and region, and they're saved to the Vouch
database (Supabase) through `register_interest()`. The key in `index.html` is Supabase's publishable key, which is
public by design: the page can only add someone's details, never read the list.

Served by GitHub Pages from the `main` branch. `share.png` is the preview card shown when the link is shared.
