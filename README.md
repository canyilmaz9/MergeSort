# Merge Sort
Merge Sort - Proje 2

## İlk Dizin
[16,21,11,8,12,22]


```
Bölünmüş Hali: [16,21,11] - [8,12,22]

Sonraki Adım: [16,21][11] - [8,12][22]

Tamamen Açılmış Hali: [16][21][11] - [8][12][22]

Sıralı Halde Birleşme: [16,21][11] - [8,12][22]

Üçlü Birleşme: [11,16,21] - [8,12,22]

Son Hali: [8,11,12,16,21,22]
```

Big O: n tane adım her adımda 2^x=n => x= log(n) O(nlog(n))