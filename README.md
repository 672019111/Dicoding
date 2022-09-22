Pada contoh kode berikut, manakah hasil yang benar?

const newObject = {
  satu: 'satu',
  dua: 'dua',
  tiga: true,
};
localStorage.setItem('newItem', JSON.stringify(newObject));
const getObject = localStorage.getItem('newItem');
console.log(`${getObject.satu} ${getObject.dua} ${getObject.tiga}`);

* undefined undefined undefined

---------------------------------------------------------------------------------

Berapakah maksimal penyimpan data di web storage untuk masing-masing domain?

* 10 MB


---------------------------------------------------------------------------------

Method pada local storage dan session storage yang berfungsi untuk membersihkan seluruh item adalah …

- [ ] clear()
- [x] removeAll()
- [x] reset()
- [x] destroy()


---------------------------------------------------------------------------------
- [ ] setItem()
- [ ] length
- [x] clear()
- [ ] deleteItem()

---------------------------------------------------------------------------------
Apa fungsi dari JSON.stringify()?

- [ ] Mem-parsing object JavaScript menjadi string
- [x] Mengubah string menjadi JSON
- [ ] Mem-parsing string menjadi object JavaScript
- [x] Mem-parsing JSON menjadi string

---------------------------------------------------------------------------------
Manakah method atau properti yang tidak didukung oleh Local Storage maupun Session Storage?

- [X] setItem()
- [ ] deleteItem()
- [x] length
- [ ] clear()
  
---------------------------------------------------------------------------------
Apa yang dimaksud dengan Web Storage?

- [ ] Sebuah web server yang berfokus dalam menangani perdataan website
- [ ] Salah satu Web API yang memiliki fitur penyimpanan data secara local di sisi client (browser)
- [ ] Benar semua
- [X] Salah satu database pengganti yang ada di web server
---------------------------------------------------------------------------------
Web Storage memiliki dua tipe penyimpanan yaitu …

* Session Storage dan Local Storage
---------------------------------------------------------------------------------
Manakah pernyataan yang benar dari Local Storage dan Session Storage?
* Data yang disimpan pada local storage tidak akan hilang sampai menghapusnya secara manual, sedangkan data yang disimpan pada session storage akan hilang saat tab atau browser ditutup
---------------------------------------------------------------------------------
