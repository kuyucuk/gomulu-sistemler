# ADC

Analog sinyalleri dijital sinyallere dönüştürmemizi sağlayan gömülü sistemlerin vazgeçilmez bir elektronik parçasıdır. **A**nalog to **D**igital **C**onverter olarak kısaltması açılabilir. Adc devreleri, referans noktası ile ölçülmek istenen noktadaki voltaj farkından yola çıkarak cinsine bağlı olarak n-bit'te dijital değerler verebilir. Bit değerleri adc'nin çözünürlüğünü belirler.


Örneğin: 3 bit çözünürlüğe sahip bir adc devresi, aralığı 2 üzeri 3 _(8)_ parçaya böler. Referans ile giriş noktası arasında 5V fark olsun. Voltajın okunacağı alanda 2V olsun. Bu durumda adc'nin çözünürlüğünden dolayı 5V 8'e bölünecek ve her bir parça 0.625V olacaktır.

0. 0V - 0,624V
1. 0,625V - 1,249V
2. 1.25V - 1,874V
3. 1,875V - 2,49V 
4. 2,5V - 3.1249V
5. 3,125V - 3,749V
6. 3,75V - 4,3749V
7. 4,375V - 5V

Yukarada da görülebileceği üzere **2V** **1,875V - 2,49V** grubuna girecektir. Adc sahip olduğu 3 bit digital output'una **3** değerini gönderecektir. _(Liste 1 den 8'e gidiyor ama aslında 0'dan başlıyıp 7'e gidiyor)_

Bu 3 değerini nasıl gönderecek diye sormak isteyebilirsiniz. Ne kadar hödükte olsanız açıklayalım. Binary işlemlerini hatırlarsanız 3 değerinin binary karşılığı **11** dir. Adc devresinin 3 bit digital outputu var dedik. O halde bu 3 pine sırasıyla **011** olacak şekilde 5V veya 0V ataması yapacaktır.


### Çözünürlüğü arttırmak

Adc devreleri ne kadar şahane olsalarda bazı zamanlarda 10 bit adc hatta 20 bit adc bile işimizi görmeyebilir. Ne kadar manyak çılgın olduğumuza bağlı. [Mesela bu step motorlar](https://www.youtube.com/watch?v=1F4-plhdnj0)

