# Router Control — Mac çevrimiçi test kanalı

Bu depo yalnız ayrı Mac test cihazında çevrimiçi güncelleme kabulü içindir. Genel kararlı yayın kanalı değildir. macOS Intel ve Apple Silicon için mevcut kaynak tabanlı, yayıncı imzalı güncelleme paketini sunar.

Mac panelinde Ayarlar > Güncelleme > Geri alma ve kaynak ayarları > Güncelleme kaynağı (GitHub) bölümünden Depo alanına `hakanyaz27-sudo/internet-panel-preview` yazılır. Mevcut panel şifresi yalnız Mac panelinin görünür şifre alanına girilir. Açık depo için erişim jetonu gerekmez. Ardından Güncellemeleri denetle > Şimdi güncelle kullanılır; elle ZIP indirmek/seçmek gerekmez.

1.6.72 paketleri kullanıcının imzaladığı dosyaların aynı baytlarıdır. Genel Mac kaynağı internet-panel ve Windows native kaynağı router-control-releases değiştirilmez. Bu Mac test deposunda Windows native ZIP veya Setup sunulmaz. Birleşik imzalı manifest değiştirilmeden korunur.

Mac/NAS gerçek cihaz kabulü tamamlanmamıştır. Windows'taki son zorla kapatma denemesinde yeni işçi yaklaşık 73,3 saniye sonra doğmuş, 60 saniyelik toparlanma kabulü geçmemiştir. Bu sonuç genel kararlı yayına izin vermez; Mac test güncellemesinin sonucu ayrıca bildirilmelidir.

Eski 1.6.68 güncelleyici yalnız releases/latest okuduğu için bu ayrı test deposundaki sürüm GitHub'da yayımlanmış ve prerelease=false olmak zorundadır. Bu teknik işaret genel kararlı kanala terfi anlamına gelmez. GitHub'ın otomatik kaynak arşivleri güncelleme paketi değildir.
