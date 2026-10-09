# Yankı herkese açık sayfaları

Mağazaların ve KVKK'nın istediği sayfaların **taslakları**. Yayından önce bir avukat (KVKK) tarafından
gözden geçirilmeli; köşeli parantezli alanlar doldurulmalı.

| Dosya | Adres (önerilen) | Kim istiyor |
| --- | --- | --- |
| `index.md` | / | — |
| `gizlilik.md` | /gizlilik | App Store, Google Play, KVKK (aydınlatma metni) |
| `kosullar.md` | /kosullar | Apple (abonelik ekranı bağlantısı), Google Play |
| `hesap-silme.md` | /hesap-silme | Google Play (hesap silme için web yolu) |
| `destek.md` | /destek | App Store (destek adresi) |

Yayın: herkese açık `OptimalYazilim/yanki-site` deposu, GitHub Pages ile
https://optimalyazilim.github.io/yanki-site/ adresinde. Kaynak bu klasördür; değişiklikten sonra ana depoda kaydedip
şununla gönderilir:

```powershell
git subtree push --prefix=site site main
```

(`site` uzak deposu bir kez eklenir: `git remote add site https://github.com/OptimalYazilim/yanki-site.git`.)
Adresler uygulamada `mobile/src/constants/links.ts` içinde.
