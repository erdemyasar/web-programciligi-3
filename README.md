# 1. Hafta – Git ve GitHub

## Araştırma
* **Git Nedir?:** Bilgisayarda yerel çalışan, projedeki kod ve dosya değişikliklerini adım adım takip eden dağıtık bir versiyon kontrol sistemidir.
* **GitHub Nedir?:** Git projelerinin bulutta saklanmasını, paylaşılmasını ve ortak geliştirilmesini sağlayan web barındırma platformudur.
* **Git ile GitHub Arasındaki Fark:** Git yerelde çalışan bir yazılım/araçtır; GitHub ise bu depoların tutulduğu bulut tabanlı servistir.
* **Repository:** Projenin tüm dosyalarını ve geçmiş değişiklik kayıtlarını içeren ana depodur.
* **Commit:** Dosyalarda yapılan değişikliklerin açıklama mesajıyla birlikte Git geçmişine kalıcı olarak kaydedilmesidir.
* **Branch:** Ana kod tabanını bozmadan yeni özellik geliştirmek veya hata çözmek için açılan bağımsız çalışma koludur.
* **Merge:** Farklı bir daldaki geliştirmelerin ana dalla birleştirilmesidir.
* **Clone:** Uzak bir reponun yerel bilgisayara tam kopyasının indirilmesidir.
* **Pull:** Uzak depodaki güncellemeleri yerel koda çekip birleştirme işlemidir.
* **Push:** Yereldeki commitlerin uzak depoya (GitHub'a) yüklenmesidir.
* **.gitignore:** Git tarafından takip edilmemesi gereken hassas veya gereksiz dosyaları hariç tutan yapılandırma dosyasıdır.

## Sektörde Kullanımı
Yazılım sektöründe Git ve GitHub; ekiplerin çakışma yaşamadan paralel kod geliştirmesini, Pull Request süreçleriyle kod incelemesi yapmasını ve CI/CD süreçleriyle test ve dağıtımı otomatikleştirmesini sağlar.

## İncelediğim Projeler
1. **Strapi:** TypeScript tabanlı açık kaynaklı Headless CMS altyapısı sunar. Monorepo yapısı ve modüler eklenti dizinleri barındırır (~30.000 commit).
2. **Supabase:** Firebase alternatifi açık kaynaklı BaaS (veritabanı, auth, realtime depolama) platformudur. Go ve Next.js mikroservisleri kullanır (~13.000 commit).
3. **Discourse:** Modern topluluk ve tartışma platformu motorudur. Ruby on Rails MVC mimarisini kullanır (~60.000 commit).

## Yaptığım Uygulama
Yönergeye uygun olarak `web-programciligi-3` reposu altında `hafta-01-git-github` klasörü oluşturulmuş, 5 adımlı anlamlı commit yapısıyla temel bir web sitesi (HTML, CSS, form yapısı) inşa edilmiştir.

## Karşılaştığım Problemler
* İlk depoda commit oluşturulmadan push denenmesi sonucu alınan `src refspec main does not match any` hatası yerelde `git add` ve `git commit` adımları tamamlanarak çözüldü.
* Terminale markdown işaretleri girildiğinde oluşan çok satırlı girdi takılması `Ctrl + C` ile sonlandırıldı.

## Öğrendiklerim
* Git komutlarının yerel çalışma döngüsü (add, commit) ile uzak sunucu iletişimi (push, pull) arasındaki farkı.
* Standartlara uygun anlamlı commit mesajı yazmanın proje takibindeki önemi.
* Profesyonel açık kaynak projelerin dizin ve README dokümantasyon yapıları.

## Kaynaklar
1. Git Resmi Dokümantasyonu – https://git-scm.com/doc
2. GitHub Docs – https://docs.github.com
3. Strapi Repository – https://github.com/strapi/strapi
4. Supabase Repository – https://github.com/supabase/supabase
5. Discourse Repository – https://github.com/discourse/discourse