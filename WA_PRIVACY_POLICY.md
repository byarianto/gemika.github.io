# Kebijakan Privasi — WhatsApp Seller Copilot

**Tanggal Berlaku:** 14 November 2026

WhatsApp Seller Copilot ("Ekstensi") adalah ekstensi browser **gratis** yang dirancang untuk membantu admin dan penjual merekap pesanan langsung dari WhatsApp Web (`https://web.whatsapp.com/`).

## 1. Data yang Diproses
Ekstensi ini hanya membaca konten obrolan aktif di WhatsApp Web **secara langsung atas perintah pengguna** (saat pengguna menekan tombol *Ambil dari WA* atau *Sisipkan*), serta menyimpan data berikut secara lokal di browser pengguna (`chrome.storage.local`):
- Draf pesanan sementara per kontak, daftar produk katalog, template balas cepat (FAQ), identitas toko pengirim, dan catatan/status pembeli.
- Pengaturan opsional milik pengguna, yaitu URL Web App Google Apps Script dan/atau Gemini API Key milik pengguna sendiri.

## 2. Pengiriman Data ke Pihak Ketiga
- **Pengembang tidak memiliki server backend** dan tidak pernah mengumpulkan, menyimpan, menjual, atau mengakses data pengguna maupun percakapan WhatsApp Anda.
- Jika Anda menghubungkan **Google Sheets**, data pesanan, produk, catatan pelanggan, dan FAQ dikirim langsung dari browser Anda ke **Google Apps Script Web App milik Anda sendiri**.
- Jika Anda memasukkan **Gemini API Key milik Anda sendiri** dan menekan *Isi Otomatis*, teks chat yang dipilih dikirim langsung ke API Google Gemini (`generativelanguage.googleapis.com`) menggunakan kunci Anda sendiri.

## 3. Keamanan & Kontrol Pengguna
Anda memiliki kendali penuh untuk menghapus seluruh data lokal kapan saja melalui pengaturan ekstensi Chrome atau dengan menghapus ekstensi dari browser.

## 4. Kontak
Jika ada pertanyaan terkait kebijakan privasi ini, silakan hubungi: `[ISI-EMAIL-ANDA@domain.com]`
