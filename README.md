Proje Yazarı: [Arda Güven]

Projenin Adı: Kod-Asistan v0.1 

Projenin Amacı
Kullanıcılara günlük işlerinde (hesaplama, selamlama vb.) yardımcı olacak bir dijital asistan tasarlamak.

> Kritik Eşik Kontrolü (Sözde Kod Mantığı):**
> Başlangıç
>  Kullanıcıdan girdi al (`girdi_degeri`)
>  Eğer `girdi_degeri` boş veya tanımsız ise:
>    `Hata: Lütfen geçerli bir değer giriniz!` uyarısı ver
>    Yeniden girdi iste
>  Değilse:
>    `Anlık_Yük = Hesapla(girdi_degeri)`
> Eğer `Anlık_Yük > KRITIK_ESIK_DEGERI` (Örn: 100 birim):
>      `Uyarı: Sistem kritik eşiğe ulaştı, işlem güvenli modda sınırlandırılıyor.` mesajını göster
>    Değilse:
>      İşlemi normal akışında çalıştır ve sonucu ekrana yazdır
>  Bitiş

 Kaynakça

* Millî Eğitim Bakanlığı, *Programlama Temelleri ve Algoritmalar Ders Kitabı*, Ankara.
* Yazılım Geliştirme Temelleri ve En İyi Uygulamalar Kılavuzu.
