# **1. Pembagian tugas 3 orang – Kasus C**

# **1**

**Anggota 1 – DFD & Threat Analysis**

Penanggung jawab DFD

**Tugas utama:**

- Mengidentifikasi aset, aktor, dan komponen sistem.
- Menyusun alur data keseluruhan sistem.
- Membuat DFD di OWASP Threat Dragon.
- Menentukan dan menggambar trust boundary.
- Memastikan semua data flow memiliki arah dan label yang tepat.
- Mengerjakan analisis STRIDE untuk bagian registrasi dan penerbitan tiket.

**Ancaman yang dikerjakan:**

- T01 – Pemalsuan identitas peserta.
- T04 – Modifikasi QR Code / ID tiket.

**Output:** DFD lengkap, trust boundary, dan dua analisis ancaman.

# **2**

**Anggota 2 – Authentication & Scanning Security**

Penanggung jawab analisis keamanan

**Tugas utama:**

- Menganalisis proses login petugas.
- Menganalisis keamanan sesi petugas.
- Menganalisis pemindaian QR Code.
- Mengidentifikasi ancaman STRIDE pada proses autentikasi dan pemindaian.
- Mengisi skenario, dampak, kemungkinan, skor risiko, dan mitigasi.
- Memasukkan ancaman ke Threat Dragon.

**Ancaman yang dikerjakan:**

- T02 – Penyalahgunaan identitas sesi petugas.
- T05 – Penyangkalan aktivitas check-in.
- T06 – Kebocoran data peserta.
- T08 – Gangguan layanan validasi tiket.

**Output:** Empat analisis ancaman lengkap beserta mitigasinya.

# **3**

**Anggota 3 – Validation & Administration Security**

Penanggung jawab analisis keamanan

**Tugas utama:**

- Menganalisis proses validasi tiket.
- Menganalisis pembaruan status check-in.
- Menganalisis proses dashboard admin.
- Mengidentifikasi ancaman STRIDE pada Backend Tiket dan Database Tiket.
- Mengisi skenario, dampak, kemungkinan, skor risiko, dan mitigasi.
- Memasukkan ancaman ke Threat Dragon.

**Ancaman yang dikerjakan:**

- T03 – Manipulasi status check-in.
- T07 – Akses tidak sah dashboard admin.
- T09 – Pemindaian tiket secara bersamaan.
- T10 – Peningkatan hak akses petugas menjadi admin.

**Output:** Empat analisis ancaman lengkap beserta mitigasinya.

# **2. Pembagian beban kerja**

| Pekerjaan                    | Anggota 1 | Anggota 2 | Anggota 3 |
| ---------------------------- | --------- | --------- | --------- |
| Identifikasi aset dan aktor  | ✓         | Review    | Review    |
| Identifikasi asumsi          | ✓         | ✓         | ✓         |
| Penyusunan DFD               | ✓         | -         | -         |
| Trust boundary               | ✓         | Review    | Review    |
| Analisis STRIDE              | 2 ancaman | 4 ancaman | 4 ancaman |
| Risk assessment              | ✓         | ✓         | ✓         |
| Mitigasi                     | ✓         | ✓         | ✓         |
| Input ancaman Threat Dragon  | ✓         | ✓         | ✓         |
| Review DFD                   | ✓         | ✓         | ✓         |
| Review ancaman               | ✓         | ✓         | ✓         |
| Ekspor dan pemeriksaan hasil | Bersama   | Bersama   | Bersama   |

**Mengapa pembagian ini adil?**

- Anggota 1 memiliki tanggung jawab teknis tambahan berupa penyusunan DFD lengkap.
- Anggota 2 dan 3 memiliki empat ancaman yang harus dianalisis secara mendalam.
- Ketiganya tetap mengerjakan STRIDE, risk assessment, mitigasi, dan input Threat Dragon.
- Semua anggota melakukan review hasil pekerjaan anggota lainnya.

# **3. Alur pengerjaan bersama**

**Tahap 1 – Diskusi bersama**

Semua memahami kasus, aset, aktor, dan asumsi.

**Tahap 2 – Anggota 1 membuat DFD**

Anggota 2 dan 3 memberikan masukan alur sistem.

**Tahap 3 – Analisis STRIDE**

Ketiga anggota mengerjakan ancaman masing-masing.

**Tahap 4 – Input Threat Dragon**

Semua memasukkan ancaman ke elemen DFD yang relevan.

**Tahap 5 – Review dan pengumpulan**

Periksa konsistensi DFD, ancaman, skor, mitigasi, JSON, dan PDF.

# **4. Pesan pembagian tugas untuk grup**

**Pembagian Tugas Keamanan Siber – Kasus C (E-Ticket)**

Agar pengerjaan lebih terstruktur, DFD dikerjakan oleh satu orang sebagai penanggung jawab utama, sedangkan analisis STRIDE dibagi berdasarkan modul sistem.

**Anggota 1 – DFD & Threat Analysis**

- Membuat DFD keseluruhan sistem dan trust boundary.
- Mengidentifikasi aset, aktor, serta alur data.
- Mengerjakan T01 dan T04 beserta risk assessment dan mitigasi.

**Anggota 2 – Authentication & Scanning Security**

- Menganalisis login dan sesi petugas serta pemindaian QR Code.
- Mengerjakan T02, T05, T06, dan T08.
- Melengkapi skenario, dampak, risiko, dan mitigasi.

**Anggota 3 – Validation & Administration Security**

- Menganalisis validasi tiket, pembaruan status check-in, dan dashboard admin.
- Mengerjakan T03, T07, T09, dan T10.
- Melengkapi skenario, dampak, risiko, dan mitigasi.

**Ketentuan bersama:**

1. Semua anggota ikut berdiskusi menentukan aset, aktor, dan asumsi.
2. Anggota 2 dan 3 wajib memberikan masukan terhadap DFD.
3. Setiap anggota memasukkan ancaman yang menjadi tanggung jawabnya ke Threat Dragon.
4. Semua anggota melakukan review diagram dan ancaman.
5. Semua anggota memahami hasil akhir.

Target pengumpulan: satu file JSON dan satu laporan PDF.
