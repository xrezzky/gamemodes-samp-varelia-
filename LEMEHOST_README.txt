═══════════════════════════════════════════════════
 VARELIA ROLEPLAY - PAKET LEMEHOST FIX10
═══════════════════════════════════════════════════

 ISI FIX10:
 - gamemodes/Main.amx = COMPILE BARU (pawn 3.10.10, no error)
   MySQL creds LemeHost SEMUA SUDAH DI-EMBED:
     host : 51.38.205.167
     user : u291665_XsB5oInqTB
     pass : WfEhm9!xuC3wL.kdYjb7fNGo
     db   : s291665_db1792543135617
   >> TIDAK PERLU COMPILE/EDIT APAPUN LAGI <<
 - server.cfg: port 14956, maxplayers 15 (sesuai plan LemeHost)
 - Database bersih: database/varelia_clean.sql
   (no akun lama, owner bangunan semua 0, dunia utuh:
    ATM/pintu/location - siap diisi via Discord bot + in-game)
 - Semua plugin .so Linux sesuai server.cfg

 CARA PAKAI (WAJIB URUT):
 1. HAPUS dulu file lama Varelia di server LemeHost
    (biar tidak ada sisa cfg/amx/pawno versi usang)
 2. Upload SEMUA isi folder ini ke folder server
 3. phpMyAdmin -> database s291665_db1792543135617
    -> Import -> pilih database/varelia_clean.sql
 4. Tunggu import selesai (cek jumlah tabel ~107)
 5. Start server dari panel

 CEK SUKSES:
 - console log tidak ada "Connection to MySQL FAILED"
 - log menampilkan gamemap normal & tidak exit otomatis
 - kalau masih "gamemode is OFF"/exit:
    -> buka server_log.txt, copy 30-40 baris pertama,
       kirim untuk debug lanjut

 CATATAN TAMBAHAN:
 - Jangan pakai database_dump lama (usang)
 - Source code (.pwn + pawno/include) tetap tersedia di paket
   untuk update di masa depan
 - rcon_password di server.cfg masih jangan lupa diganti
═══════════════════════════════════════════════════
