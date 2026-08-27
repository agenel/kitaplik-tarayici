# Kitaplık Tarayıcı 📚

Telefon kamerasıyla kitap barkodu (ISBN) okuyup Google Sheet'teki kitaplık listesiyle karşılaştıran, listede olmayan kitapları tek dokunuşla ekleyen web uygulaması.

**Kullanım:** https://agenel.github.io/kitaplik-tarayici/ adresini aç, ilk açılışta kendi Google Apps Script web uygulamanın `/exec` adresini yapıştır (adres yalnızca senin tarayıcında saklanır, bu repoda yer almaz).

- Canlı kamera taraması (`BarcodeDetector`, eski tarayıcılarda ZXing)
- Fotoğraftan barkod çözme ve elle ISBN girişi
- Kitap bilgisi: Google Books → Open Library
- Türkçe ad normalizasyonu ile benzerlik eşleştirme, ISBN öğrenme (E sütunu)
