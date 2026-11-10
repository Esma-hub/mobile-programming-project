# StudyFlow - Figma tasarım paketi

Paket, uygulamadaki görsel dili temel alan 10 mobil ekran, tasarım sistemi ve tıklanabilir ekran bağlantıları içerir.
Ekranlar 390 x 844 ölçüsündedir. Metinler, renkler ve şekiller Figma içinde ayrı katmanlar olarak oluşturulur.

## Figma içinde oluşturma

1. Figma masaüstü uygulamasında boş bir Design dosyası açın.
2. Plugins > Development > Import plugin from manifest bölümünden bu klasördeki manifest.json dosyasını seçin.
3. StudyFlow Tasarım Paketi eklentisini çalıştırın. Tasarım sistemi ve ekranlar yeni bir sayfada oluşur.
4. İlk ekranı seçip Present ile prototipi başlatın. Alt gezinme ve temel işlem alanlarında ekran bağlantıları bulunur.

Geliştirme eklentisi kimliğiyle ilgili uyarı alınırsa Figma'da yeni bir geliştirme eklentisi oluşturun; üretilen manifest dosyasındaki id değerini koruyup diğer alanları bu paketteki manifest ile eşleştirin. code.js dosyasını aynı klasöre kopyalayın.

## Alternatif: SVG içe aktarma

ekran_01.svg ... ekran_10.svg dosyalarını Figma tuvaline sürükleyin. Vektörler içe aktarılır; prototip bağlantıları bu yöntemde otomatik kurulmaz. Yerel eklenti yöntemi metin katmanlarını doğrudan Figma TextNode olarak oluşturur.

screens.json, düzeni tanımlayan taşınabilir kaynak verisidir. design-tokens.json renk, yazı ve ölçü değerlerini içerir.
Ornek dersler, görevler ve e-posta gösterim verisidir. Bu tasarımlar gerçek kullanıcı hesabına veya veritabanına bağlanmaz.
Bulut yedeği ve yükleme ekranları arayüz durumlarını anlatır; prototip gerçek hesap oluşturmaz veya veri göndermez.

Bu paket doğrudan .fig dosyası değildir. Hesaptaki Figma dosyası, içe aktarıldıktan sonra oluşur. Eklentinin Figma hesabında çalıştırılması ayrıca doğrulanmalıdır.
