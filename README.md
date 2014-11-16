## TURENG-CLI

~~## Tureng Sözlük~~

~~[tureng sözlük](http://tureng.com/) henüz bizlere bir API sunmadığı için bu betiği geliştirdim.~~

~~Bu betik en ilkel haliyle, konsolda çalışırken tekrar web tarayıcınıza geçmenize gerek kalmadan hızla bir kelimenin anlamına bakabilmenizi sağlar.~~

~~[Tureng'den](http://tureng.com/) bulunan tercümeler ve/veya kelime önerileri biçimlendirilerek ekrana bir tablo içerisinde basılır.~~

~~## Kurulum~~

~~Betiği çalıştırabilmek için sisteminizde nokogiri, open-uri ve text-table GEM'leri kurulu olmalıdır. Bu GEM'leri aşağıdaki şekilde kurabilirsiniz;~~

```
$ [sudo] gem install nokogiri
$ [sudo] gem install text-table
```

~~Daha sonra betiğin bulunduğu dizine düşerek çalıştırmanız yeterlidir;~~

```
$ ruby tureng.rb
```

~~## Ekran Görüntüleri~~

~~**Bulunan kelimeler için sonuçlar:**~~

![](http://i.imgur.com/kgOHeoF.png)

~~**Kelime bulunamadığı zaman öneriler:**~~

![](http://i.imgur.com/AbFkjmv.png)

## Uyarı

Tüm kelimeler ve kelimelerin anlamları [tureng sözlükten](http://tureng.com/) çekilmektedir ve tamamı tureng sözlük veritabanlarında bulunmaktadır. Bu uygulama yalnızca konsol ortamından tureng'e erişmek isteyenlere yardımcı olmak için hazırlanmıştır. Görüntülediğiniz tüm içeriklerin yasal hakları vb. tureng'e aittir.
