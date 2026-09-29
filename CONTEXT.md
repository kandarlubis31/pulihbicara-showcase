# CONTEXT — showcase-pulihbicara

> Repo ini = showcase publik untuk project `nodeJS/therapy_pasca_stroke` (PulihBicara).
> Kategori SHOWCASE-ONLY: README + screenshot + diagram, TANPA source code.

## Aturan penting
- ATURAN #1 workspace: push PUBLIC = WAJIB konfirmasi eksplisit Kandar dulu.
  Repo ini dibuat PRIVATE dulu — flip public hanya setelah konfirmasi.
- Kode asli aman di `nodeJS/therapy_pasca_stroke` (repo privat). Tidak ada file source disalin ke sini.
- `CONTEXT.md` ini jangan dihapus — catatan internal (publik = tidak masalah, tidak ada info sensitif).

## Isi
- `README.md` — bahan jualan: masalah → solusi → fitur → arsitektur (Mermaid)
- `screenshots/` — desktop-vokal.png + mobile-vokal.png (Chrome headless vs dist/, bukan screenshot hot, cukup baik)
- `LICENSE` — All Rights Reserved 2026

## Cara screenshot di-reproduce (kalau mau update)
```bash
CHROME="/c/Program Files/Google/Chrome/Application/chrome.exe"
"$CHROME" --headless=new --disable-gpu --hide-scrollbars --window-size=1280,800 \
  --virtual-time-budget=15000 \
  --screenshot=screenshots/desktop-vokal.png \
  "file:///C:/Users/KandarLubis/Desktop/Project/nodeJS/therapy_pasca_stroke/dist/index.html"
# mobile: --window-size=390,844 → screenshots/mobile-vokal.png
```

## Checklist sebelum flip public
- [ ] Kandar lihat README + screenshots, OK
- [ ] Deskripsi repo + topics profesional (PWA, speech-therapy, astro, accessibility)
- [ ] Flip ke public via `gh repo edit kandarlubis31/pulihbicara-showcase --visibility public --accept-visibility-change-consequences`
