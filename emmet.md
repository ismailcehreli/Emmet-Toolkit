Emmet özelliğini daha hızlı kod blokları yazmak için kullanırız.

       1) + -> Kardeş öğe
       2) > -> İçinde öğe
       3) ^ -> Yukarı çık ve öğe oluştur.
       4) * -> Birden fazla etiket oluşturmak istiyorsak çarpı adet şeklinde kullanabiliriz.
       5) lorem -> Etiket arasını text içerikle doldurur. Kaç kelimeden oluşmasını istiyorsak lorem10 yazdığımızda 10 kelimeden oluşan anlamsız bir metin oluşturur.
       6) . class oluşturur. ($,@, @-)
       7) # id oluşturur. ($,@, @-)
       8) {} öğeye metin eklemek için kullanılır.


    1) + Kardeş öğe kullanımı :
    Aynı anda p ve h etiketi oluşturmak istiyoruz. Html kod blokuna p+h yazdıktan sonra enter tuşuna basıyoruz.
    Bastıktan sonra oluşacak kod bloku aşağıdaki gibidir. Etiket sıralaması soldan sağa şeklindedir.-->

    <!-- Kardeş öğe kullanımı başlangıç - Kod Satırı : p+h -->
    <p></p>
    <h></h>
    <!-- Kardeş öğe kullanımı bitiş -->


    2) İçinde öğe kullanımı :
    Bir etiket içerisinde aynı etiket kullanımı için tercih edilir. Örneğin bir sıralı bir tablo oluşturmak için kullanmamız gereken kod satırı aşağıdaki gibidir.


    <!-- İçinde öğe kullanımı başlangıç - Kod Satırı : ul>li  -->
    <ul>
        <li>List</li>
    </ul>
    <!-- İçinde öğe kullanımı başlangıç bitiş -->


    3) ^ -> Yukarı çık ve öğe oluştur kullanımı :
    Bir liste oluştururken liste etiketleri dışında oluşturmak istediğimiz bir etiket varsa ^ kullanırız. Aşağıdaki kod satırında editör öncelikle ul ve ul altında li etiketi oluşturduktan sonra ul etiketi sonrasında h2 ve p etiketi oluşturacaktır.

    <!-- Yukarı çık ve öğe oluştur başlangıç - Kod Satırı : ul>li^h2+p -->
    <ul>
        <li>Unordered list</li>
    </ul>
    <h2>Başlık</h2>
    <p>İçerik</p>
    <!-- Yukarı çık ve öğe oluştur başlangıç - bitiş -->


    4) * -> Birden fazla etiket oluşturma kullanımı
    Bir etiketten aynı anda birden fazla oluşturmak istiyorsak * kullanırız. Aşağıdaki kod satırında p etiketinden 5 adet oluşturağız.

    <!-- Birden fazla etiket paragraf oluşturma başlangıç - Kod satırı : p*5 -->
    <p>Paragraf 1</p>
    <p>Paragraf 2</p>
    <p>Paragraf 3</p>
    <p>Paragraf 4</p>
    <p>Paragraf 5</p>
    <!-- pBirden fazla etiket paragraf oluşturma bitiş -->


    5) lorem -> Anlamsız text içerik oluşturur. Aşağıdaki komut satırında p etiketi içerisine lorem ile text içerik yazdıracağız.

    <!-- Lorem text oluşturma başlangıç - Kod satırı : p>lorem -->
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias beatae vel facere quasi amet totam adipisci
        quis soluta corporis. Nostrum est eveniet expedita soluta neque tempore tenetur inventore, magnam assumenda?</p>
    <!-- Lorem text oluşturma bitiş -->

    Standart lorem kelime sayısı 30'dur. 30 kelimeden az veya daha fazla kelimeden oluşan bir text oluşturmak istiyorsak lorem sonrasında kelime sayısını belirtmemiz gerekir. Aşağıda lorem ile 10 kelime ve 100 kelimeden oluşan bir text satırı oluşturacağız.

    <!-- 10 kelimelik loram satırı başlangıç - Kod Satırı : p>lorem10 -->
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Tempora, ipsum?</p>
    <!-- 10 kelimelik loram satırı bitiş-->

    <!-- 100 kelimelik loram satırı başlangıç - Kod Satırı : p>lorem100 -->
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum eum fugiat magnam harum, alias nam assumenda
        quas dignissimos neque reprehenderit cum aspernatur sit dolor vitae repudiandae animi accusantium voluptatem?
        Odio quisquam dolor alias quia aliquid, modi, deleniti consequuntur natus quam earum sapiente unde facilis
        architecto inventore aut fugiat assumenda incidunt quibusdam nisi cum perferendis quaerat. Nam, excepturi
        corporis sapiente ex odio inventore earum iusto non dignissimos, odit beatae a quod nisi in harum reiciendis
        eligendi recusandae pariatur ullam nulla architecto! Ullam nam repellat atque eaque, dolore repellendus ab
        ratione culpa, architecto reprehenderit ipsa dignissimos sint vel deleniti itaque velit est?</p>
    <!-- 100 kelimelik loram satırı bitiş p>lorem100-->


    6) . -> etiket için class oluşturmak için kullanılır. Aşağıdaki kod ile bir adet div oluşturacağız lakin bu div'e henüz bir class adı tanımlamayacağız.

    <!-- div oluşturma başlangıç - Kod Satırı : .container -->
    <div class="">Class</div>
    <!-- div oluşturma bitiş -->


    <!-- Oluşturmak istediğimiz div'e aynı zamanda class ismide tanımlamak istiyorsak noktadan sonra class ismi yazmalıyız. -->

    <!-- div oluşturma ve class ismi tanımlama başlangıç - Kod Satırı : .classadi -->
    <div class="classadi">Class Adı</div>
    <!-- .div oluşturma ve class ismi tanımlama başlangıç -->

    <!-- Sıralı class adını numaralandırmak için $ operatörü kullanılır. -->

    <!-- 5 adet sıralı class tanımlama başlangıç Kod Satırı : .classadi$*5 -->
    <div class="classadi1">Class 1</div>
    <div class="classadi2">Class 2</div>
    <div class="classadi3">Class 3</div>
    <div class="classadi4">Class 4</div>
    <div class="classadi5">Class 5</div>
    <!-- 5 adet sıralı class tanımlama bitiş-->

    <!-- Sıralı class numaralarını sondan başa doğru oluşturmak için @- operatörü kullanılır. -->

    <!-- 5 adet classı sondan başa doğru sıralama başlangıç Kod Satırı : .classadi$@-*5  -->
    <div class="classadi5">List 1</div>
    <div class="classadi4">List 2</div>
    <div class="classadi3">List 3</div>
    <div class="classadi2">List 4</div>
    <div class="classadi1">List 5</div>
    <!-- 5 adet classı sondan başa doğru sıralama bitiş -->

    <!-- Sıralı numaralı class tanımlamalarında class adındaki sayıyı istediğimiz sayıdan başlatmak için @ operatörünü kullanırız. -->

    <!-- 3'den başlayacak şekilde sıralı class oluştur başlangıç - Kod Satırı : ul>li.item$@3*5 -->
    <ul>
    <li class="classadi3">List 3</li>
    <li class="classadi4">List 4</li>
    <li class="classadi5">List 5</li>
    <li class="classadi6">List 6</li>
    <li class="classadi7">List 7</li>
    </ul>
    <!-- 3'den başlayacak şekilde sıralı class oluştur bitiş -->


    7) # -> Öğe için id oluşturur.

    <!-- Id oluşturma başlangıç - Kod Satırı : p# -->
    <p id="">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Non autem magni ratione impedit quam doloribus
        error accusamus quia iure in nisi saepe et velit quibusdam eveniet esse, cumque exercitationem nemo.</p>
    <!-- Id oluşturma bitiş-->

    <!-- Id ismi ile öğe oluşturma başlangıç - Kod Satırı : p#idadi -->
    <p id="idadi">Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur ut veritatis rem nesciunt,
        assumenda, quidem, recusandae neque nam nemo cum atque optio perferendis aspernatur porro nobis sed tenetur ad
        saepe.</p>
    <!-- Id ismi ile öğe oluşturma bitiş -->

    <!-- Sıralı birden fazla id oluşturma başlangıç - Kod Satırı : ul>li#id$*5 -->
    <ul>
        <li id="id1">Id 1</li>
        <li id="id2">Id 2</li>
        <li id="id3">Id 3</li>
        <li id="id4">Id 4</li>
        <li id="id5">Id 5</li>
    </ul>
    <!-- Sıralı birden fazla id oluşturma bitiş-->

    <!-- 3'den başlayacak şekilde sıralı id oluşturma başlangıç - Kod Satırı : ul>li#id$@3*5  -->
    <ul>
        <li id="id3">Id 1</li>
        <li id="id4">Id 2</li>
        <li id="id5">Id 3</li>
        <li id="id6">Id 4</li>
        <li id="id7">Id 5</li>
    </ul>
    <!-- 3'den başlayacak şekilde sıralı id oluşturma bitiş -->

    <!-- Sondan başa doğru sıralı id oluşturma başlangıç - Kod Satırı : ul>li#id$@-*5  -->
    <ul>
        <li id="id5">Id 1</li>
        <li id="id4">Id 2</li>
        <li id="id3">Id 3</li>
        <li id="id2">Id 4</li>
        <li id="id1">Id 5</li>
    </ul>
    <!-- Sondan başa doğru sıralı id oluşturma için ul>li#id$@-*5 bitiş -->


    8) {} -> Öğe içerisinde metin oluşturmak için kullanılır. Örnek kullanım aşağıdaki gibidir.

    <!-- Öğe içerisinde metin oluşturma başlangıç - Kod Satırı : ul>li#idadi$.classadi${deneme$}*5 -->
    <ul>
        <li id="idadi1" class="classadi1">deneme1</li>
        <li id="idadi2" class="classadi2">deneme2</li>
        <li id="idadi3" class="classadi3">deneme3</li>
        <li id="idadi4" class="classadi4">deneme4</li>
        <li id="idadi5" class="classadi5">deneme5</li>
    </ul>
    <!-- Öğe içerisinde metin oluşturma bitiş -->
