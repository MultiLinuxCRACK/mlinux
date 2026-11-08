# MLinux

**Multi Script Linux** — MLinux işletim sistemi projesi.

## İlk ISO

İlk önyüklenebilir masaüstü ISO'su Debian 13 (Trixie), amd64 ve XFCE tabanıyla hazırlanır. Bu taban, MLinux'un kendi Multi Script bileşenleri ve masaüstü özelleştirmeleri için başlangıç altyapısıdır.

## ISO üretimi

1. GitHub deposunda **Actions** sekmesini aç.
2. **Build MLinux ISO** iş akışını seç.
3. **Run workflow** düğmesine bas.
4. İşlem tamamlanınca **MLinux-amd64-ISO** artifact'ini indir.

Çıktı: `MLinux-amd64.iso` ve SHA256 kontrol dosyası.

Bu ilk sürüm temel masaüstü canlı ISO'sudur. Multi Script yorumlayıcısı, Mhrome ve MLinux kurulum sihirbazı henüz dahil değildir; sonraki geliştirme adımlarıdır.
