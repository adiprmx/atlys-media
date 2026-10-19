# AI Context — atlys-media (PUBLIK)

> Repo ini PUBLIK. Khusus file gambar hasil maker endpoint. Tidak ada data sensitif.

## Fungsi repo ini

Ini **album foto** Atlys API. Isinya file gambar hasil dari endpoint maker yang pakai parameter `?simpan=1`.

Dipisah dari `atlys-data` karena repo itu privat (berisi data user), sedangkan file gambar perlu bisa diakses publik via URL langsung.

## Hubungan dengan repo lain

| Repo | Hubungan |
|------|----------|
| `adiprmx/osint-api` (privat) | Dapur utama. Endpoint maker simpan gambar ke repo ini. |
| `adiprmx/atlys-data` (privat) | Gudang data (terpisah karena privat). |

## Aturan kerja di repo ini

1. Hanya untuk file hasil `?simpan=1`. Jangan taruh file lain.
2. Repo ini publik — jangan taruh data user atau secret di sini.

## Keputusan final (jangan ditanya ulang)

- Repo ini PUBLIK (pilihan Adip 2026-10-19).
- `atlys-data` tetap privat.

---
*Update dokumen ini setiap ada keputusan baru. Terakhir: 2026-10-19.*
