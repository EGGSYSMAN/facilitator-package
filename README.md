[![NPM](https://nodei.co/npm/facilitator-package.png?downloads=true&downloadRank=true&stars=true)](https://npmjs.com/package/facilitator-package/)

# Örnek Kullanımlar

```js
const facilitator-package = require('facilitator-package')

console.log(facilitator-package.kısalt("baştan", 4, "deneme"))
//Bu kod "baştan" silecek bir şekilde "deneme" yazısının 4 harfini siler.

console.log(facilitator-package.kısalt("sondan", 4, "deneme"))
//Bu kod "sondan" silecek bir şekilde "deneme" yazısının 4 harfini siler.

console.log(facilitator-package.matematik('4+4'))
//Bu kod 4+4 işleminin sonucunu verir.

console.log(facilitator-package.büyült("ilki", "deneme"))
//Bu kod "deneme" yazısının ilk harfini otomatik olarak büyütür.

console.log(facilitator-package.büyült("tamamı", "deneme"))
//Bu kod "deneme" yazısının tamamını otomatik olarak büyütür.

console.log(facilitator-package.küçült("ilki", "deneme"))
//Bu kod "deneme" yazısının ilk harfini otomatik olarak küçültür.

console.log(facilitator-package.küçült("tüm", "deneme"))
//Bu kod "deneme" yazısının tamamını otomatik olarak küçültür.

console.log(facilitator-package.rastgele("pozitif", 10))
//Bu kod "pozitif" ve "10"u geçmeyecek bir şekilde rastgele sayı gönderir.

console.log(facilitator-package.boşluk("deneme", 10))
//Bu kod "deneme" yazısının başından 10 harflik bir boşluk bırakır.

console.log(facilitator-package.tekrarla("tekrar", 5))
//Bu kod "a" yazısını otomatik olarak 5 kez tekrarlar.

```

# Aktif Fonksiyonlar

| Fonksiyon | Açıklaması |
|-----------|------------|
| kısalt | [Yazılan yazıyı, yazılan uzunlukta kısaltır. baştan ve sondan kısaltma olmak üzere fonksiyonları bulunur. ]|
| matematik | Yazılan işlemin sonucunu verir. |
| büyült | Yazılan yazının harflerini büyütür. ilki ve tamamı olmak üzere fonksiyonları bulunur. |
| küçült | Yazılan yazının harflerini büyütür. Tüm ve ilk fonksiyonları bulunur. |
| rastgele | Negatif veya pozitif rastgele sayı atar. Yazılan sayıyı geçmeyecek şekilde. |
| boşluk | Yazılan yazının başından yazılan sayıda boşluk bırakır. |
| tekrarla | Yazılan yazıyı yazılan sayıda tekrarlar. |
