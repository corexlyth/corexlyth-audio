# CoreXLyth Audio

CoreXLyth blogunda kullanılan arka plan müziklerinin barındırıldığı ses deposu.

Müzikler GitHub Pages üzerinden servis edilir ve CoreXLyth temasındaki global müzik oynatıcısı tarafından kullanılır.

## Müzik Havuzu

CoreXLyth artık tek bir global müzik havuzu kullanır:

`core/`

Bu klasörde bulunan müzikler kategori, yazı türü veya sayfa türü ayrımı yapılmadan CoreXLyth genelinde kullanılabilir.

Tema tarafında ayrı PHONK, HISTORY veya sayfa bazlı müzik havuzları kullanılmaz.

Ana sayfa, blog yazıları, statik sayfalar ve diğer uygun CoreXLyth sayfaları aynı global oynatma sistemini kullanır.

## Oynatma Sistemi

Global oynatıcı:

- `core/` klasöründeki parçaları tek playlist olarak kullanır.
- İlk girişte playlist içerisinden rastgele bir parçayla başlayabilir.
- Sonraki parçalar playlist sırasına göre devam edebilir.
- Kullanıcının müzik açık / kapalı tercihini koruyabilir.
- Sayfa geçişlerinde mevcut parça ve oynatma konumunun korunması tema tarafından yönetilebilir.

Playlist davranışı CoreXLyth tema sürümüne göre değişebilir.

## GitHub Pages

Ana ses adresi:

`https://corexlyth.github.io/corexlyth-audio/`

Global müzik havuzu:

`https://corexlyth.github.io/corexlyth-audio/core/`

Örnek:

`https://corexlyth.github.io/corexlyth-audio/core/the_mountain-phonk-496452.mp3`

## Kaynak ve Lisanslar

Bu depodaki üçüncü taraf müzikler için tek bir genel lisans uygulanmaz.

Her ses dosyası kendi kaynak lisansına tabidir.

Sanatçı, kaynak, kaynak kimliği ve lisans bilgileri `SOURCES.md` içerisinde dosya bazında kayıt altında tutulur.

> Bir ses dosyasının bu depoda bulunması, CoreXLyth'in o eserin telif hakkı sahibi olduğu veya eseri yeniden lisansladığı anlamına gelmez.

Pixabay kaynaklı parçaların CoreXLyth içerisinde arka plan müziği olarak kullanılması ile ham MP3 dosyalarının public bir GitHub deposunda yeniden dağıtılması aynı lisans konusu değildir.

Pixabay Content License, içeriğin yaratıcı projelerde kullanılmasına izin verir ancak içeriğin esasen orijinal hâliyle standalone olarak yeniden dağıtılmasına sınırlamalar getirir.

Bu nedenle yeni bir müzik eklenmeden önce kaynağı ve kullanım koşulları kontrol edilmelidir.

Yeni bir ses dosyası eklendiğinde `SOURCES.md` kaydı da güncellenmelidir.

---

CoreXLyth Audio Repository
