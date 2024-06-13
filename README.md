<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
       .logo {
            width: 200px;
            height: 100px;
        }
    </style>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!--
    main div
    navbar->logo, navlinks->search
    sidebar->categories, tags
    content->posts
    footer->social media links
    -->
    <div class="container">
      <header class="header">
        <div class="col2">
          <img src="logo.png" alt="logo" class="logo" />
        </div>
        <div class="col6">
          <nav class="nav">
            <ul class="nav__list">
              <li class="nav__item">
                <a href="#" class="nav__link">Anasayfa</a>
              </li>
              <li class="nav__item">
                <a href="#" class="nav__link">100 Temel Eser</a>
              </li>
              <li class="nav__item">
                <a href="#" class="nav__link">Populer Eserler</a>
              </li>
              <li class="nav__item">
                <a href="#" class="nav__link">İletişim</a>
              </li>
            </ul>
          </nav>
        </div>
        <!--
        <div class="col4">
          <input type="text" class="search" placeholder="Search" />
        </div>
        -->
      </header>
      <div class="main">
        <!-- banner-->
        <div class="col12 banner">
          <img
            src="https://picsum.photos/1200/300?grayscale"
            alt="banner"
            class="banner"
          />
        </div>
        <div class="sidebar">
          <div class="categories">
            <h2 class="categories__title">Kategoriler</h2>
            <ul class="categories__list">
              <li class="categories__item">
                <a href="#" class="categories__link">Bilim - Kurgu</a>
              </li>
              <li class="categories__item">
                <a href="#" class="categories__link">Roman</a>
              </li>
              <li class="categories__item">
                <a href="#" class="categories__link">Siir</a>
              </li>
              <li class="categories__item">
                <a href="#" class="categories__link">Arastirma - Inceleme</a>
              </li>
              <li class="categories__item">
                <a href="#" class="categories__link">Is Ekonomi - Hukuk</a>
              </li>
            </ul>
          </div>
          <div class="tags">
            <h2 class="tags__title">En Cok Okunan Kitaplar</h2>
            <ul class="tags_list">
              <li class="tags_item">Saatleri Ayarlama Enstitusu</li>
              <li class="tags_item">Hayvan Ciftligi – George Orwell</li>
              <li class="tags_item">Turkcenin Sirlari – Nihad Sami Banarli</li>
              <li class="tags_item">Momo – Michael Ende</li>
              <li class="tags_item">Nutuk - Mustafa Kemal Ataturk</li>
            </ul>
          </div>
        </div>
        <div class="content">
          <div class="col4">
            <div class="post">
              <img
                src="https://picsum.photos/200/300?grayscale"
                alt="post"
                class="post__img"
              />
              <h3 class="post__title">Visne Bahcesi Ozet -Anton Cehov</h3>
              <p class="post__content">
                Vişne Bahçesi, Mayıs sabahının ilk saatlerinde Rusya’da başlar. Dışarısı soğuk olsa da kiraz ağaçlarının çiçek açtığını öğreniriz. Ailenin dostu Yermolay Lopakhin ve Ranevsky malikanesinin hizmetçisi Dunyasha, malikanenin sahibi Ranevsky’yi ana evde, “çocuk odası” denilen bir odada beklemektedirler. Lopakhin, Ranevsky’nin son beş yıldır Paris’te olduğunu açıklar. Lopakhin, otuzlarının ortalarında, şatafatlı sarı ayakkabılarla beyaz bir takım elbise giymiş yerel bir iş adamıdır ve Ranevsky’ye karşı duyduğu karışık hisler vardır: geçmişteki iyilikleri için şükran dolu sevgi ve köylü kökenlerinden dolayı onun kendisine olan küçümsemesi nedeniyle kızgınlık. Malikanede ayrıca “Basit Simon” lakaplı, sık sık komik kazalar geçiren bahtsız genç Simon Yephikodov da bulunmaktadır.
              </p>
              <!-- paylaş button-->
              <a href="#" class="share_href">Paylaş</a>
              <!-- yorum yap button-->
              <button type="button" class="comment_button">Yorum Yap</button>
            </div>
          </div>
          <div class="col4">
            <div class="post">
              <img
                src="https://picsum.photos/200/300?grayscale"
                alt="post"
                class="post__img"
              />
              <h3 class="post__title">Momo Ozet - Michael Ende</h3>
              <p class="post__content">
                Yarı dairesel bir tiyatro, bir kasabada harabeler arasına yerleştirildi ve geçmişten kalma bir amfi tiyatronun kalıntıları olduğu düşünülüyordu. Bir kız olan Momo orada yaşardı. Vatandaşlar, ona bir uyuma alanı inşa ettiler ve ona her gün yiyecek getirdiler.


Onun polise haber vermek istemediler, böylece bir bakım evinde sona ermeyecekti. Bir keresinde böyle bir yerden kaçtığını ve oraya geri dönmek istemediğini söyledi. Ona birinin yanına taşınmasını önerdiler, ancak sonunda Momo’nun tiyatroda kalmasının herkesin onunla biraz zaman geçirebilmesi için en iyi olacağına karar verdiler.
              </p>
              <!-- paylaş button-->
              <a href="#" class="share_href">Paylaş</a>
              <!-- yorum yap button-->
              <button type="button" class="comment_button">Yorum Yap</button>
            </div>
          </div>
          <div class="col4">
            <div class="post">
              <img
                src="https://picsum.photos/200/300?grayscale"
                alt="post"
                class="post__img"
              />
              <h3 class="post__title">
                Denizler Altında Yirmi Bin Fersah Ozet - Jules Verne</h3>
              <p class="post__content">
                
                Denizler Altında Yirmi Bin Fersah, Jules Verne‘in ilk kez 1870 yılında yayınlanan bilimkurgu romanıdır.

                Denizler Altında Yirmi Bin Fersah, 1866’de Nautilus denizaltısı ile seyahat eden Kaptan Nemo ve denizaltıya katılan bilim insanı Pierre Aronnax’ın kayıp Atlantis kıtasını, içeren seyahatleri ve maceralarını anlatmaktadır.
              </p>
              <!-- paylaş button-->
              <a href="#" class="share_href">Paylaş</a>
              <!-- yorum yap button-->
              <button type="button" class="comment_button">Yorum Yap</button>
            </div>
          </div>
          <div class="col4">
            <div class="post">
              <img
                src="https://picsum.photos/200/300?grayscale"
                alt="post"
                class="post__img"
              />
              <h3 class="post__title">Ay Isigi Sokagi Ozet – Stefan Zweig</h3>
              <p class="post__content">
                Anlatıcı, Fransız limanına yanaşan genç bir Alman’dır. Gemi geç bir saatte demir attığı için Almanya’ya giden treni kaçırır. Böylece, ona yabancı olan bu şehirde bir gece geçirmek zorunda kalır. Küçük şehrin sokaklarında gece vakti yürürken, bir kadının Weber’in Der Freischütz’ünü söylediğini duyar. Fransız bir şehirde kendi ana dilini duymak, genç adamı çeker ve sesin kaynağını bulmak için takip eder. Sonunda aradığını bulur: ses küçük bir bar benzeri genelevden gelmektedir.
              </p>
              <!-- paylaş button-->
              <a href="#" class="share_href">Paylaş</a>
              <!-- yorum yap button-->
              <button type="button" class="comment_button">Yorum Yap</button>
            </div>
          </div>
          <div class="col4">
            <div class="post">
              <img
                src="https://picsum.photos/200/300?grayscale"
                alt="post"
                class="post__img"
              />
              <h3 class="post__title">Ivan Ilyic’in Olumu Ozet – Lev Tolstoy</h3>
              <p class="post__content">
                Yargıç Ivan İlyiç Golovin’in öldüğünü öğrenince, Ivan’ın arkadaşları ve meslektaşları özel olarak bu ölümden nasıl fayda sağlayabileceklerini düşünürler. Ivan İlyiç’in uzun yıllar arkadaşlık ettiği Pyotr Ivanovich, bu yeni boşluk nedeniyle kayınbiraderine yardım edebileceğini fark eder ve Fyodor Vasilyevich terfi almayı hayal eder. Ancak, kimse bu düşünceleri yüksek sesle dile getirmez; bunun yerine, Ivan’ın uzun ve acılı hastalığının sonunda teslim olduğunu üzüntüyle ifade ederler.
              </p>
              <!-- paylaş button-->
              <a href="#" class="share_href">Paylaş</a>
              <!-- yorum yap button-->
              <button type="button" class="comment_button">Yorum Yap</button>
            </div>
          </div>
          <div class="col4">
            <div class="post">
              <img
                src="https://picsum.photos/200/300?grayscale"
                alt="post"
                class="post__img"
              />
              <h3 class="post__title">Aile Mutlulugu Ozet – Tolstoy</h3>
              <p class="post__content">
                Aile Mutluluğu, genç bir kadın olan Masha ile yaşlı bir dul olan Sergey Mikhaylych’in evlilikleri etrafında döner. Hikaye, Masha’nın soylu bir ailede büyümesini ve Sergey ile tanışmasını anlatarak başlar. Masha, gençliğinde pek çok hayranlık uyandıran deneyim yaşamıştır. Ancak, bu deneyimler onun için tam anlamıyla tatmin edici değildir. Bir gün, Sergey ile karşılaşır ve aralarında güçlü bir çekim oluşur.Sergey, toprak sahibi zengin bir adamdır. 
              </p>
              <!-- paylaş button-->
              <a href="#" class="share_href">Paylaş</a>
              <!-- yorum yap button-->
              <button type="button" class="comment_button">Yorum Yap</button>
            </div>
          </div>
          <div id="none" style="display: none">
            <div class="col4">
              <div class="post">
                <img
                  src="https://picsum.photos/200/300?grayscale"
                  alt="post"
                  class="post__img"
                />
                <h3 class="post__title">Ilyada Ozet – Homeros</h3>
                <p class="post__content">
                  Troya Savaşı’nın başlamasından dokuz yıl sonra, Yunan (“Akhai”) ordusu, Troya’ya müttefik olan Chryse adlı kasabayı yağmalar. Savaş sırasında Akhalar, Chryseis ve Briseis adında iki güzel genç kadını esir alır. Akhaların lideri Agamemnon, Chryseis’i ödül olarak alır ve Akhaların en büyük savaşçısı olan Achilles, Briseis’i sahiplenir. Chryseis’in babası, tanrı Apollo’nun rahibi olan Chryses, kızının geri verilmesi için büyük bir fidye teklif eder, ancak Agamemnon Chryseis’i geri vermeyi reddeder. Bunun üzerine Chryses, Apollo’ya dua eder ve Apollo Akha kampına bir veba salgını gönderir.
                </p>
                <!-- paylaş button-->
                <a href="#" class="share_href">Paylaş</a>
                <!-- yorum yap button-->
                <button type="button" class="comment_button">Yorum Yap</button>
              </div>
            </div>
            <div class="col4">
              <div class="post">
                <img
                  src="https://picsum.photos/200/300?grayscale"
                  alt="post"
                  class="post__img"
                />
                <h3 class="post__title">Mutlulugun Kazanilmasi Ozet – Farabi</h3>
                <p class="post__content">
                  Farabi’nin felsefesi, psikoloji, felsefe, ahlak, siyaset ve metafizik arasında sıkı bir bağ kurar. Metafiziğe doğru ilerleyen felsefe araştırması, mutluluğun ahlaki bir noktadan başlayarak değil, metafiziğin inşasıyla belirlenir. Farabi’ye göre, mutluluğun ne olduğu ve ona nasıl ulaşılacağı, metafizik sistem tarafından belirlenir. Metafizik, diğer bilimler için gerekli olan evrenselliği ve konusunun yüceliği nedeniyle en üst konuma sahiptir.
                </p>
                <!-- paylaş button-->
                <a href="#" class="share_href">Paylaş</a>
                <!-- yorum yap button-->
                <button type="button" class="comment_button">Yorum Yap</button>
              </div>
            </div>
            <div class="col4">
              <div class="post">
                <img
                  src="https://picsum.photos/200/300?grayscale"
                  alt="post"
                  class="post__img"
                />
                <h3 class="post__title">Gülme Kitap Ozet – Henri Bergson</h3>
                <p class="post__content">
                  1.Du comique en général (Genel olarak komik olan) </br>
                  2.Le comique des formes et le comique des mouvements (Biçimin komedisi ve hareketin komedisi)</br>
                  3.Force d’expansion du comique (Komik olanın genişleyici gücü)</br>
                  Kısa bir girişte, Bergson komiği tanımlamaya çalışacağını ancak kelimenin sıkı bir tanımını vermek istemediğini belirtir; komiği insan hayatının bir parçası olarak ele almak istemektedir. Onun amacı ayrıca toplumun, insan hayal gücünün ve kolektif hayal gücünün işleyişinin daha iyi anlaşılması, ayrıca sanat ve hayatın da anlaşılmasıdır.
                </p>
                <!-- paylaş button-->
                <a href="#" class="share_href">Paylaş</a>
                <a
                  href="https://www.linkedin.com/shareArticle?url=file:///Users/selahaddinciftci/Desktop/ders/index3.html#&title=Flaş Haber"
                  class="linkedin"
                  target="_blank"
                  >LinkedIn'de Paylaş</a
                >
                <!-- yorum yap button-->
                <button type="button" class="comment_button">Yorum Yap</button>
              </div>
            </div>
          </div>
          <button
            type="button"
            class="loadmore"
            onclick="loadMore1()"
            style="display: none"
            id="load1"
          >
            Daha Az Göster
          </button>
          <button type="button" class="loadmore" onclick="loadMore()" id="load">
            Daha Fazla Göster
          </button>
        </div>
      </div>
      <footer class="footer">
        <ul class="social__list">
          <li class="social__item">
            <a href="#" class="social__link">Bahance</a>
          </li>
          <li class="social__item">
            <a href="#" class="social__link">Github</a>
          </li>
          <li class="social__item">
            <a href="#" class="social__link">Stackoverflow</a>
          </li>
          <li class="social__item">
            <a href="#" class="social__link">Linkedin</a>
          </li>
        </ul>
      </footer>
    </div>
    <script>
      function loadMore() {
        document.getElementById("none").style.display = "block";
        document.getElementById("load").style.display = "none";
        document.getElementById("load1").style.display = "block";
      }
      function loadMore1() {
        document.getElementById("none").style.display = "none";
        document.getElementById("load").style.display = "block";
        document.getElementById("load1").style.display = "none";
      }
    </script>
  </body>
</html>
