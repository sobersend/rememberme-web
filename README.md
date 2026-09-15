# RememberMe web door

Public HTTPS host for Legend invite links: `https://rememberme.sobersend.com/s/{token}`.

This is a static Expo web export (`npx expo export -p web`) from [sober-send-factory/rememberme](https://github.com/sober-send-factory/rememberme). GitHub Pages + Cloudflare DNS.

Rebuild: in the app repo, `npx expo export -p web`, then copy `dist/` here (keep `CNAME`, `.nojekyll`, and `404.html` = `index.html` for client routes).
