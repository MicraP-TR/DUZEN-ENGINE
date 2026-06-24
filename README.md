# DUZEN-ENGINE

👾MicraP Game Language & Engine

MicraP, süslü parantez ({}) karmaşasından uzak, satır bazlı (line-based) çalışan özgün bir oyun programlama dili ve SDL2 tabanlı bir 2D simülasyon motorudur. Geliştiricilerin kod karmaşasıyla vakit kaybetmesini önlemek ve oyun mekaniklerine odaklanmasını sağlamak için tasarlanmıştır.

Parser altyapısı, token mantığı ve yerel fonksiyon mimarisi tamamen Micraçer tarafından kurgulanmıştır.
#
✨ Özellikler (Features)

  - Parantezsiz & Yalın Sözdizimi: Kod blokları @ana, @bitis, eğer ve bitir; gibi temiz ifadelerle yönetilir.
  - Hafif ve Bağımsız: compiler.cpp modülleri doğrudan ana motora (main.cpp) ve SDL2 grafik döngüsüne göbekten bağlıdır.
  - Hızlı Geliştirme: C++ ile satırlarca sürecek grafik ve klavye girdileri (input.key), MicraP sözdizimi ile birkaç satırda çözülür.
#
🛠️ Örnek Kod Yapısı (Syntax Example)

Projenin temel mantığını anlamak için basit bir .mip dosyası örneği:

Plaintext
@ana
sayı parça_x = 0d100;
sayı parça_y = 0d200;

eğer input.key == "D"
    parça_x = parça_x + 0d5;
bitir;

output.screen(parça_x, parça_y, 0d32, 0d32);
@bitis
#
👥 Ekip Katılımı & Süzgeç Süreci (Contribution)

C++ ve SDL2 alanında kendini geliştirmek isteyen "çılgın" geliştiricilerin katkılarına açığız. Ancak projenin kalitesini korumak adına turnikede sert bir süzgecimiz vardır:

  - Başvuran geliştiricilere projenin teknik dökümanları iletilir.
  - Kendilerine tek bir soru sorulur: "Bundan ne anladın?"
  - Mantığı ve mimariyi kavrayabilen geliştiricilerle 1 aylık pratik deneme sürecine geçilir.
#
📝 Atıf ve İtibar Hakkı: Ekibe katılan geliştiricilerin yaptığı tüm katkılar portfolyo, CV ve LinkedIn kullanımı için serbesttir. Emeğe saygı esastır; "o geliştirmedi" demek yasaktır. Ancak projenin bütünlüğü ve hakları koruma altındadır.
#
⚖️ Lisans Notu (License)
Öğrenciler ve Hobi Geliştiricileri: MicraP'i bireysel eğitim, deneme ve ticari olmayan hobi projeleriniz için tamamen ücretsiz ve izinsiz olarak kullanabilirsiniz.

Kurumsal ve Ticari Kullanım: Birden fazla kişiden oluşan ekiplerin, oyun stüdyolarının kullanımı, projenin forklanması veya ticari oyunlarda dağıtılması kurucunun yazılı iznine tabidir.

Ticari izinler, kopyalanamaz ve taklit edilemez Kriptografik Dijital İmzalar (Şifreli Anahtarlar) ile doğrulanır.

Detaylar için LISANS.txt dosyasını inceleyebilirsiniz.
#
📬 İletişim (Contact)
Proje hakkında sorularınız, iş birliği veya turnike başvuruları için:

Discord: micracer_51620

E-Posta: isletmekanal40@gmail.com
