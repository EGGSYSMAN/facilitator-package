[![NPM](https://nodei.co/npm/facilitator-package.png?downloads=true&downloadRank=true&stars=true)](https://npmjs.com/package/facilitator-package/)

# Örnek Kullanımlar

```js
const facilitator = require('facilitator-package')

console.log(facilitator.kısalt("baştan", 4, "deneme"))
//Bu kod "baştan" silecek bir şekilde "deneme" yazısının 4 harfini siler.

console.log(facilitator.kısalt("sondan", 4, "deneme"))
//Bu kod "sondan" silecek bir şekilde "deneme" yazısının 4 harfini siler.

console.log(facilitator.hesapla('4+4'))
//Bu kod 4+4 işleminin sonucunu verir.

console.log(facilitator.büyült("ilki", "deneme"))
//Bu kod "deneme" yazısının ilk harfini otomatik olarak büyütür.

console.log(facilitator.büyült("tamamı", "deneme"))
//Bu kod "deneme" yazısının tamamını otomatik olarak büyütür.

console.log(facilitator.küçült("ilki", "deneme"))
//Bu kod "deneme" yazısının ilk harfini otomatik olarak küçültür.

console.log(facilitator.küçült("tamamı", "deneme"))
//Bu kod "deneme" yazısının tamamını otomatik olarak küçültür.

console.log(facilitator.rastgele("pozitif", 10))
//Bu kod "pozitif" ve "10"u geçmeyecek bir şekilde rastgele sayı gönderir.

console.log(facilitator.boşluk("deneme", 10))
//Bu kod "deneme" yazısının başından 10 harflik bir boşluk bırakır.

console.log(facilitator.tekrar("tekrar", 5))
//Bu kod "a" yazısını otomatik olarak 5 kez tekrarlar.

```

# Aktif Fonksiyonlar

| Fonksiyon | Açıklaması |
|-----------|------------|
| kısalt | [Yazılan yazıyı, yazılan uzunlukta kısaltır. baştan ve sondan kısaltma olmak üzere fonksiyonları bulunur.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/k%C4%B1salt.md) |
| hesapla | [Yazılan işlemin sonucunu verir.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/hesapla.md) |
| büyült | [Yazılan yazının harflerini büyütür. ilki ve tamamı olmak üzere fonksiyonları bulunur.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/b%C3%BCy%C3%BClt.md) |
| küçült | [Yazılan yazının harflerini küçültür. ilki ve tamamı olmak üzere fonksiyonları bulunur.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/k%C3%BC%C3%A7%C3%BClt.md) |
| rastgele | [Negatif veya pozitif rastgele sayı atar. Yazılan sayıyı geçmeyecek şekilde.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/rastgele.md) |
| boşluk | [Yazılan yazının başından yazılan sayıda boşluk bırakır.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/bo%C5%9Fluk.md) |
| tekrar | [Yazılan yazıyı yazılan sayıda tekrarlar.](https://github.com/SepulturA0/facilitator-package/blob/master/kullan%C4%B1mlar/tekrar.md) |
