# wpbomber
Bu Python betiği, PyAutoGUI kütüphanesini kullanarak belirli bir aralıkta otomatik mesaj gönderen basit bir betiktir.

Nasıl Kullanılır
Öncelikle, projeyi klonlayın veya kopyalayın:

bash
Copy code
git clone https://github.com/ByFisher/wpbomber
PyAutoGUI kütüphanesini yükleyin:

bash
Copy code
pip install pyautogui
Kodu çalıştırın:

bash
Copy code
python mesaj_gonder.py
Açıklama
Bu betik, belirli aralıklarla "selam" mesajını göndermek için oluşturulmuştur. mesaj() fonksiyonu, mesajı yazmak ve göndermek için pyautogui.write() ve pyautogui.press('enter') işlevlerini kullanır. while döngüsü, belirli bir süre bekledikten sonra bu işlevi sürekli olarak çağırır.

Önemli Notlar
Bu betiği kullanırken, bilgisayarınızda fare ve klavye kontrollerini otomatik olarak yaptığına emin olun. Otomatik mesaj gönderme işlevi, bilgisayarınızı kullanılamaz hale getirebilir veya beklenmedik davranışlara neden olabilir.
Bu betiği kullanmadan önce, mesajların nereye gönderileceğini ve ne sıklıkla gönderileceğini dikkatlice belirleyin. Uygunsuz kullanım, istenmeyen sonuçlara yol açabilir.
Katkılar
Her türlü katkı ve geri bildirimleri memnuniyetle karşılıyoruz. Lütfen bir sorun oluşturun veya bir istek gönderin.

