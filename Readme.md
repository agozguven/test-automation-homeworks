readme dosyası
ilk git repo oluşturma
CMD üzerinde ilk git commit işlemi yapılırken alınabilecek hatalar için yapılması gereken işlemler:
windows "ls" komutunun çalışması için ;
1.Git exe dosyası ilgili indirilen pathden bulunarak Git ->usr->bin pathine gidilir.
2.usr->bin içinde iken path kopyalanır.
3.Windows ->  Ayarlar -> Sistem Ortam Değişkenlerini Düzenle seçeneği seçilir.
4.Burada Sistem Değişkenleri alanındaki Path'e tıklanır ve Düzenle butonuna tıklanır.
5.Açılan pop upta "Yeni" butonuna tıklanır ve 2. adımda kopyalanan path yapıştırılır ve kaydedilir.

Böylelikle komut satırında "ls"  komutu kullanılabilir hale getirilir.

git commit -m "commit mesajı" komutu çalışmıyor ise ;

1.cmd'de 
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

komutları kullanılara email ve user ismi kaydedilir.
2.Daha sonra "git commit -m "commit mesajı" çalıştırdığınızda commit yapabildiğinizi görmüş olursunuz.

git add . -> tüm dosyaları staging area'ya atar
git commit -m "commit mesajı" -> staging area'daki dosyaları commitler
git log -> yapılan commitleri gösterir
git checkout -> istenilen branche gitmesini saglar
