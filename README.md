# CDO Jakarta - Breakfix Plan

Tampilan web untuk **bf.cokesoe.com** (GitHub Pages). Data dan login ditangani oleh Google Apps Script lewat API JSON — repo ini tidak berisi data maupun kata sandi.

- `index.html` — aplikasi (dibangun dari sumber Apps Script dengan `build_github.py`)
- `CNAME` — domain kustom `bf.cokesoe.com`

Mengubah tampilan: edit `Index.html` / `Styles.html` / `Script.html` di folder kerja, jalankan `python build_github.py`, lalu unggah ulang `index.html` ke repo ini.
