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
