# tip-d-n-mleri
ödev

Bir değişken tanımlaması yaptığımızda bellekten o değişkenin tipine bağlı olarak bir alan tesis etmiş oluruz. Dolayısıyla tanımladığımız bu değişkene farklı veri tipinde bir değer atanması bellekte işlerin karışmasına neden olabilir.

Çoğu zaman uygulama yazarken farklı veri tipleri ile çalışmak durumunda kalabiliriz. Bellekte işleri yoluna koyabilmek için bu tip durumlarda tip dönüşümü yapmamız gerekir.

Tip dönüşümleri 2 şekilde yapılabilir:

Implicit Conversion (Bilinçsiz ya da kapalı dönüşüm)
Explicit Conversion (Bilinçli ya da açık dönüşüm)
float a; int b = 25; a = b;
short x = 10; int y; y = x;
