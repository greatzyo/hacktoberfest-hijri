# Kalender Hijiriah Converter
Konverter Kalender Hijiriah dari Kalender Masehi.

![alt text](https://www.mashara.id/_nuxt/img/2751b66.jpg)

## Tentang Mashara (https://www.mashara.id)
Mimpi besar Mashara adalah ingin mengumpulkan dan membagikan pengetahuan tentang dunia keislaman ke seluruh dunia. Perintah mempelajari ilmu agama adalah wajib bagi seluruh umat islam. Untuk itu, mengkodifikasi sumber-sumber keilmuan berkualitas melalui orang-orang terpercaya sangat penting bagi Mashara. Fenomena hari ini, pengetahuan terkait keislaman seringkali hanya terbatas bagi kalangan tertentu saja. Mashara hadir untuk menjembatani orang-orang yang memiliki pengetahuan dengan yang membutuhkannya.

## Build Setup
```
# install dependencies
$ npm run install
```

## How it Work?
1. Pada index.js terdapat fungsi hijriConverter(). 
2. Fungsi tersebut menerima dua parameter, tanggal dan penyesuaian
3. Tanggal yang di input menggunakan format YYYY-MM-DD (2019-10-19)
4. Penyesuaian memiliki 5 inputan yang berbeda: -2, -1, 0, 1, dan 2.
5. Selain penyesuaian tersebut, maka fungsi akan mengembalikan error.
6. Contoh inputan: 
```
hijriConverter("2019-10-19", 0) // Sabt, 20 Safar 1441 H
hijriConverter("2019-10-19", 2) // Sabt, 22 Safar 1441 H
hijriConverter("2019-10-19", -2) // Sabt, 18 Safar 1441 H
```

## TEST
Gunakan test berikut sebelum di push: 
```
npm run test
```
Pastikan sudah lulus test baru push code kamu. Terimakasih

# HAPPY CODING
