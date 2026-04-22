# ChurchCircle — KBC

NFC-powered church engagement platform for Kennebecasis Baptist Church.

## Files
- `public/index.html` — What people see when they tap an NFC circle
- `public/admin.html` — Your admin dashboard (manage circles, analytics, editor)
- `netlify.toml` — Hosting config (do not edit)

## URLs (after deployment)
- **kbc.churchcircle.app** → NFC landing page
- **kbc.churchcircle.app/admin.html** → Your admin dashboard
- **kbc.churchcircle.app/?circle=auditorium** → Auditorium circle
- **kbc.churchcircle.app/?circle=lobby** → Lobby circle  
- **kbc.churchcircle.app/?circle=kids** → Kids circle

## NFC Tag URLs to Program
Program each NFC tag type ONCE with these URLs:
- Chair tags: `https://kbc.churchcircle.app/?circle=auditorium`
- Lobby tags: `https://kbc.churchcircle.app/?circle=lobby`
- Kids tags: `https://kbc.churchcircle.app/?circle=kids`

## Connect Card
Submissions are sent to: nate@kbconline.ca via Netlify Forms
