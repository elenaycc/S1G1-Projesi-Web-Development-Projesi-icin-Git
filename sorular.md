# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
 Git, Açık Kaynak Dağıtılmış Sürüm Kontrol Sistemi(Open Source Distributed Version Control System)'dir.

2. Git ile GitHub arasında ne fark var?
   GitHub, bulut tabanlı bir git barındırma hizmeti sunan kâr amaçlı bir şirkettir. GitHub'daki projelere standart git komut satırı arayüzü kullanılarak erişilebilir ve tüm standart git komutları bununla çalışır.

3. Neden bir branch oluşturuyoruz?
   Branchler projelerimizin birer kopyasıdır. Branchler, projemizin o anki haline dokunmadan, aynı proje üzerinde birden fazla kişi farklı konularda yeni özellikler (feature) ekleyerek çalışmamızı sağlar. Böylece proje hızla geliştirilmeye devam edebilir.

4. Pull Request'in amacı nedir?
   Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
   git checkout.    git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu konutlar ne yapar açıklayınız.
    Git Fetch, değişiklikleri yerel depoya getirmeden uzak depoda mevcut değişiklikler olduğunu bildiren komuttur.Git         Git Pull ise uzak dizin değişikliklerinin kopyasını yerel depoya getirir.
    Git Merge branchları birleştirir.

7. Merge conflict nedir?
 İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 

8. Merge conflict'i nasıl çözeriz?
 Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
