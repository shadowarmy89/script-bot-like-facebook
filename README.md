# script-bot-like-facebook
Script bot like facebook terbaru 2024 menggunakan google script app
cara penggunaan

login ke script.google.com
buat projek baru dan tempelkan kode script bot like
tempelkan accessToken facebook pada kolom yang disediakan
masuk ke google drive dan buat file bernama likes_log.json masukan {}
buat lagi file bernama target.json, dan masukan
{
    "targets": {
        "ID PROFIL TARGET": "Nama Target"
    },
    "script-created-by": "AMIRZY"
}

Temukan ID Facebook
Untuk menambah ID, Anda perlu mendapatkan ID profil Facebook terlebih dahulu.
Berikut caranya:
Buka profil Facebook orang yang ingin Anda tambahkan.Salin URL dari bilah alamat browser. Contoh: https://www.facebook.com/profile.php?id=1000123456789
Nomor setelah id= adalah ID Facebook mereka. Misalnya, 1000123456789.Tambahkan ID ke JSON
Setelah Anda memiliki ID tersebut, Anda bisa menambahkannya ke bagian "targets". Formatnya seperti ini:"ID_Facebook": "Nama Panggilan"Contoh: jika Anda ingin menambahkan ID 1000123456789 dengan nama panggilan "Aldi", maka hasilnya akan seperti ini:
{
    "targets": {
        "1000123456789": "Aldi"
    },
    "script-created-by": "AMIRZY"
}

Anda dapat menambahkan beberapa id lagi
contoh dengan 2 id
{
    "targets": {
        "1000123456789": "Aldi",
        "10001383838": "Joni"
    },
    "script-created-by": "AMIRZY"
}

Simpan Perubahan
Setelah menambah ID, simpan perubahan pada file JSON Anda. Pastikan formatnya benar dengan koma (,) di tempat yang tepat dan tanda kutip ganda (") mengelilingi nilai-nilainya.
