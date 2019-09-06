Pencarian dapat digunakan untuk menemukan transaksi, akun, anggaran, dll.

Untuk mempersempit pencarian Anda untuk transaksi tertentu, Anda dapat menggunakan "pengubah" berikut. Ini terbatas pada transaksi dan kerja sama: jika Anda mencari transaksi dengan tanggal tertentu dan tipe tertentu, kedua syarat harus dipenuhi.

* Gunakan `amount:12.34` untuk menemukan transaksi dengan *tepatnya* jumlah ini. Anda harus menggunakan titik (.) Sebagai pemisah desimal.
* Anda bisa menggunakan `amount_less:100.00` dan `amount_more:15.02` dengan cara yang sama.
* Gunakan `amount_less` bersama dengan `amount_more` untuk mencari berbagai jumlah.
* Gunakan `source:employer` untuk mencari transaksi yang memiliki akun sumber tertentu.
* Gunakan `destination:walmart` untuk mencari transaksi yang memiliki akun tujuan tertentu.
* Gunakan `category:groceries` untuk mencari transaksi dengan kategori tertentu.
* Gunakan `budget:bills` untuk mencari transaksi dengan budget tertentu.
* Use `tag:groceries` to search for transactions with a specific tag.
* Use `bill:insurance` to search for transactions tied to a specific bill.
* Use `type:withdrawal` to search for specific types. Supported: transfer, deposit, withdrawal.
* Use `on:2017-02-19`, `before:2016-12-10` or `after:2015-08-30` to limit the date range of the transactions returned.

Apa yang tidak bisa kamu lakukan? </em> lakukan dengan pengubah adalah sebagai berikut:

* `source:my employer`: Anda tidak bisa menggunakan spasi.
* `destination:"albert heijn"`: menggunakan tanda kutip tidak akan membantu.
* `amount:€ 12,35`: jangan gunakan penyebut mata uang, dan gunakan titik sebagai pemisah desimal.
* `on:today` or `before:30/5/17`: the only supported format is `YYYY-MM-DD`.