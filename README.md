# Gün Projesi: Arama Özelliği

Bir ekip AramaCubugu component'inin UI'ını hazırladı ve projeye ekledi. Biz de buna search özelliği ekleyerek aktive edeceğiz.

Bunun için App.jsx'de aramaKriter'i state'i var. AramaCubugu'na bu state'i ve yazacağımız bir change handler fonksiyonunu prop olarak iletmeli, AramaCubugu'nda da alıp kullanmalıyız.

[ ] Öncelikle, App.jsx'de input alanı için bir change handler fonksiyonu yazalım. Bu fonksiyon 3 şey yapmalı:

1. event'i almalı ve ilgili element'e erişip value değerini kullanabilmeli
2. input alanındaki metne göre aramaKriteri state'ini değiştirmeli
3. gönderiler state'ine ilgili verileri -aramaKriterine göre- sahteVeri'den alıp, aktarmalı.

[ ] sonra, AramaCubugu'nda bu fonksiyonu ve aramaKriterini input alanına doğru şekilde eklemeliyiz.

- İpucu: event.target ile event'in tetiklendiği element'i seçebilirsin
- İpucu: .filter() metodunu kullanabilirsin.
- İpucu: onChange event'ini kullanabilirsin.
- İpucu: input alanına value olarak aramaKriteri'ni ekleyebilirsin.
- İpucu: state'leri değiştirmek için setter'larını kullanmaya dikkat.

## Önemli Notlar

- Proje dizinindeki `user.json` dosyasını bulun ve `user_id` alanını NextGen proje ekranında görünen kendi `user_id` değeriniz ile güncelleyin.
- Geliştirme sırasında testleri izlemek için `npm test` komutunu kullanın.
- Testleri çalıştırıp skoru NextGen'e kaydetmek için `npm run sendresults` komutunu kullanın.
