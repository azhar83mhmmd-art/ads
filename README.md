# premify-ads
Halaman iklan terpisah untuk AM Premify (ditampilkan di popup "Tonton Iklan").
1. Deploy folder ini ke Vercel (project baru, tanpa build).
2. Pasang domain, mis. ads.kairoo.my.id, atau pakai nama project .vercel.app.
3. Daftarkan domain ini sebagai website di Adsterra (domain iklan harus cocok).
4. Di project panel, isi env AD_FRAME_URL=https://<domain-iklan>/ lalu redeploy.
5. Ganti domain panel di vercel.json (frame-ancestors) kalau bukan premifyy.kairoo.my.id.
