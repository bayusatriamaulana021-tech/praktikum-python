# praktikum-python

Proyek praktikum Pemrograman Berorientasi Objek nih: bikin program Python
pertama, main-main sama virtual environment, terus belajar Git dan GitHub.

## Ini proyek apaan sih?

Isinya cuma dua program kecil:

- `halo.py` : nyapa kamu, nanya **tahun lahir**, terus ngitungin perkiraan
  umur kamu. Kalau kamu iseng ngetik huruf atau tahun dari masa depan, tenang,
  program nggak bakal ngambek. Dia bakal minta kamu ngetik ulang (pakai
  `try/except`). Tulisannya juga warna-warni berkat paket `colorama`.
- `tampil.py` : nampilin tabel alat praktikum yang cakep pakai paket `rich`.

## Yang harus disiapin dulu

- Python 3.10 ke atas
- Git

## Bikin dan nyalain virtual environment

Bikin dulu venv-nya (cukup sekali aja) di folder proyek:

```bash
# Windows
py -m venv .venv

# macOS / Linux
python3 -m venv .venv
```

Terus nyalain:

```bash
# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# Windows (Command Prompt)
.venv\Scripts\activate.bat

# macOS / Linux
source .venv/bin/activate
```

Kalau di terminal udah muncul tulisan `(.venv)` di depan, berarti venv-nya
udah nyala. Mau matiin? Ketik `deactivate`.

## Install paket-paketnya

Pas venv udah nyala, tinggal ketik:

```bash
pip install -r requirements.txt
```

## Cara ngejalanin programnya

```bash
python halo.py      # di Windows boleh juga: py halo.py
python tampil.py
```

Contoh hasil `halo.py`:

```
Masukkan nama Anda: Budi
Halo, Budi! Selamat datang di praktikum Python.
Masukkan tahun lahir Anda: 2005
Perkiraan usia Anda saat ini 21 tahun.
Semoga sukses!
```

## Isi folder proyek

```
praktikum-python/
├── .gitignore
├── README.md
├── halo.py
├── requirements.txt
└── tampil.py
```

Udah, gitu aja. Selamat nyobain, semoga lancar dan nggak error!

## Catatan

Program ini dibuat untuk latihan praktikum Python, venv, dan Git.

MAULANA BAYU SATRIA GANTENG