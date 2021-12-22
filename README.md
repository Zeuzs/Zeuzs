### Selamlar 👋


Git nedir ve nasıl çalışır?
Git versiyon kontrol sistemidir, yazdığımız programı kodu veya herhangi bir dosya topluluğunu, versiyonlara ayırararak ve tekrarlama halinde geliştirmek istiyorsak kullanacağımız sistemdir.
Git yerel olarak bilgisayarda bulunan bir uygulamadır, Github ise Git ile yazılan projeler için bir depolama servisidir.

Repository Nedir?
Repository, projelerimizin dosyalarının depolandığı bir dizindir. Github’ın alanında veya bilgisayarımızdaki yerel bir depoda bulunabilir.

Git Nasıl Oluşturulur
Windows’a kurulum için gerekli dosyayı resmi web sayfasından indirmemiz gerekiyor.
Bunun için https://git-scm.com/downloads adresine tıklıyoruz.
İndirdiğimiz setup’ın gerekli adımlarını yaptıktan sonra Git’in başarılı bir şekilde çalışıp, çalışmadığını kontrol etmemiz gerekiyor.
Bunun için “Başlat” menüsünden “Git Bash” kısayolunu bulup, çalıştırıyoruz.
Açılan pencerede aşağıda ki komutu uyguluyoruz.

![1_hGv_-plrBx-cx7ZKkOoSVg](https://user-images.githubusercontent.com/96534233/147117797-41e4de42-1121-4d0f-a233-9d663b0e59df.png)

Resimde de görüldüğü üzere komutu uyguladıktan sonra Git sürümü hakkında bilgi veriyorsa, her şey yolunda demektir.

Git Github’a nasıl yüklenir
Github’a kayıt yaptırın ve yeni bir repository oluşturun.
Bilgisayarınıza yüklediğiniz Git Bash’ı çalıştırıp aşağıda gördüğünüz kodları sırasıyla yazarak yapılandırma işlemlerini yapınız.
![1_E2gwT3ik0V1WjbOuk-SvDg](https://user-images.githubusercontent.com/96534233/147117942-005fd7f0-42ff-4de1-9771-e73eeac9a278.png)

3. deneme adında bir repository oluşturduğunuzu düşünün.Github ta yeni bir repo oluştururken aşağıdakini işaretlediyseniz.
![1__tWT-OiuylPy0OdN-rx8sQ](https://user-images.githubusercontent.com/96534233/147117994-9347ca31-d3f8-4057-a65c-616b855c3d2b.png)

![1_g1NYS9P5_a9f4JhDSbM2Uw](https://user-images.githubusercontent.com/96534233/147118007-92a3fa7b-7634-4682-a83b-3a498e05ec6b.png)

İşaretlemediyseniz bu adımı es geçebilirsiniz.

4.Bilgisayarınızda bir proje oluşturun.

![1_Qwk5bAPPSmhTJ03h5kPCkQ](https://user-images.githubusercontent.com/96534233/147118053-ab5b8bac-f132-4565-8b33-e44f0aa6a785.png)

5. Üçüncü adımı işaretlediyseniz.Aşağıdaki komutu kullanınız.

![1_4WvEIX9-LeQ--HcGFTueHg](https://user-images.githubusercontent.com/96534233/147118078-397624a9-b4d0-4ddc-833d-5430131f8e47.png)

Aşağıdaki komutla bütün dosyalarınızı yerel repoya ekleyebilirsiniz.

![1_3jyuHy3XDZK6z54-Z10hTA](https://user-images.githubusercontent.com/96534233/147119621-0ed1ef08-03ec-401e-a9e9-e0d90b257f38.png)

6. Aşağıdaki komutla ilk commit(yorum) işleminizi gerçekleştiriniz.

![1_3jyuHy3XDZK6z54-Z10hTA](https://user-images.githubusercontent.com/96534233/147118101-ba949e32-9bbb-492f-97e9-1ff13a9a520e.png)

7.Aşağıdaki kod parçası isimli bir uzak repository olan github a göndermenize yarar.

![1_4tMgzbcnuS3dMokEhzRxKA](https://user-images.githubusercontent.com/96534233/147119658-b309a3ee-da7f-4b9c-b53b-5f242d16ba11.png)

8.Son olarak aşağıdaki komutla githuba projenizi gönderiniz.

![1_TlLm1Ug3J3qxjExlKEbFsQ](https://user-images.githubusercontent.com/96534233/147119866-64960287-15b5-4be4-afb1-db99f457ea73.png)

Yeni Bir Branch Oluşturmak
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.
Şimdi yeni bir klasör oluşturup aşağıdaki komutu verelim.

![1_Eo7ZK6Z6Gc8ETYKhCm36zw](https://user-images.githubusercontent.com/96534233/147119899-a06e0e82-de3e-4477-99da-7e27a92f1230.png)

Örneğin, basit bir toplama işlemi yapan bir PHP (islemler.php) dosyamız olsun. Biz bu kodumuza eklenti olarak çarpma işlemi de hesaplamasını istiyoruz. Fakat, bu eklentiyi yaparken toplama işlemi fonksiyonunun işleyişini bozabiliriz. Bu yüzden eklentimizi güvenli ortamda geliştirmek için önce toplama işlemi dosyamızı Git’e ekleyip commit yapalım.

![1_gMZ3lJps6rEhJbTbotoq9g](https://user-images.githubusercontent.com/96534233/147119928-d470e03a-9a0b-4b64-8040-d9e154793e9b.png)
![1_MHQos2u7-oIE_AQ3mH1xEg](https://user-images.githubusercontent.com/96534233/147120367-20525fe3-f61f-48e5-b0fe-8a8afc8bc044.png)

Yukarıdaki işlemleri gerçekleştirdikten sonra toplama işlemi yapan kodumuzu güvenli bir şekilde kaydettik. Şimdi ise rahatlıkla çarpma işlemi eklentisi üzerinde çalışabiliriz.
Yeni Bir Branch Oluşturmak
Git’de iki farklı şekilde branch oluşturabiliriz. Bu yollardan bir tanesi git branch komutunu kullanmak, diğeri ise git checkout -b parametresi vermek. Git branch komutu sadece yeni bir branch oluştururken, git checkout -b “…” komutu yazdığınız isimde branch yoksa onu oluşturur ve bulunduğunuz branch değiştirilir.

![1_bTwtgNpQSLFIvNcU215qZw](https://user-images.githubusercontent.com/96534233/147120392-b1a0c04a-4f54-4083-aee4-3507c4cc6dd0.png)

Bu komuttan sonra aşağıdaki yazıyı görüyorsanız doğru yoldasınız demektir.

![1_CxHe8jsvVAB5DaMNStAGTA](https://user-images.githubusercontent.com/96534233/147120413-696f6102-e123-4953-9937-6626621d6396.png)

Şimdi yeni bir branch oluşturduğumuza ve çalışma branchimizi değiştirdiğimize göre önceden yarattığımız toplama.php dosyasını açıp çarpma işlemi eklentimizi ekleyebiliriz. Bundan sonra yapacağımız değişiklik carpma_islemi adındaki branchimize kaydedilecektir.

![1_v_gwvWgCx15sKga89bWx0A](https://user-images.githubusercontent.com/96534233/147120562-c492bb76-7675-468e-b626-a4a634b98520.png)

