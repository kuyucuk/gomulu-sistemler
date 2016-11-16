# ADC

Analog sinyalleri dijital sinyallere dönüştürmemizi sağlayan gömülü sistemlerin vazgeçilmez bir elektronik parçasıdır. **A**nalog to **D**igital **C**onverter olarak kısaltması açılabilir. Adc devreleri, referans noktası ile ölçülmek istenen noktadaki voltaj farkından yola çıkarak cinsine bağlı olarak n-bit'te dijital değerler verebilir. Bit değerleri adc'nin çözünürlüğünü belirler.


Örneğin: 3 bit çözünürlüğe sahip bir adc devresi, aralığı 2 üzeri 3 _(8)_ parçaya böler. Referans ile giriş noktası arasında 5V fark olsun. Voltajın okunacağı alanda 2V olsun. Bu durumda adc'nin çözünürlüğünden dolayı 5V 8'e bölünecek ve her bir parça 0.625V olacaktır.

0. 0V - 0,625V
1. 0,625V - 1,25V
2. 1.25V - 1,875V
3. 1,875V - 2,5V 
4. 2,5V - 3.125V
5. 3,125V - 3,75V
6. ,75V - 4,375V
7. ,375V - 5V
