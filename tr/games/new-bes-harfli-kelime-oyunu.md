---
title: Beş Harfli Kelime Oyunu - Puzly.Co
layout: default_tr
body_class: page-home
show_language_options: true
---


{% capture page_url %}{{ site.url }}{{ site.baseUrl }}{{ page.url }}{% endcapture %}
{% capture game_title %}{{ page.title | remove: " - Puzly.Co" }}{% endcapture %}
{% include share-script.html shareUrl=page_url shareText='Haydi bu harika bulmaca oyununu oynayalım!' shareTitle=game_title %}
{% include mobile-os-script.html %}


<section id="games" class="section games-section game-1-section">
	<div class="container">
		<div class="section-content">
			<div class="section-title">
				Yeni <span>Beş Harfli Kelime Oyunu</span>, dokuz oyunu tek bir çatı altında toplayan bir kelime bulmaca oyunudur.
			</div>
			<div class="section-text">
				Geliştirilmiş <span>Beş Harfli Kelime Oyunu</span>, her yaştan bulmaca tutkunu için yaratılmış zorlu ama eğlenceli bir kelime bulmaca oyunudur. Daha önce ayrı ayrı sunulan dokuz oyunu bir araya getiren oyunumuzda İngilizce, Türkçe ve Kırgızca dillerinde dört ila altı kelimelik bulmacaları çözmenin yanı sıra, artık üç farklı zorluk seviyesinden birini de seçebiliyorsunuz. Eğlenceli bir Türkçe, Kırgızca veya İngilizce kelime bulmacasının çözmenin gururunu yaşamaya hazır olduğunuzu düşünüyorsanız, aşağıdaki bağlantıdan <span>Beş Harfli Kelime Oyunu</span>'nu ücretsiz olarak indirebilirsiniz.
			</div>
			<div class="section-badge">
				<a href="https://play.google.com/store/apps/details?id=co.puzly.xhko" target="_blank"><img alt="Google Play'den indirin" id="gp-logo-img" width="188" height="56" src="/images/google-play-badge-tr.png" /></a>
				<a href="https://apps.apple.com/app/be%C5%9F-harfli-kelime-oyunu/id6596769905" target="_blank"><img alt="App Store'dan indirin" id="as-logo-img" width="188" height="56" src="/images/app-store-badge-tr.png" /></a>
			</div>
			<button class="share-button" />
		</div>
	</div>
</section>


<section id="games" class="section games-section development-story" id="story">
	<div class="container">
		<div class="section-content">
			<div class="section-title">
				<span>Beş Harfli Kelime Oyunu</span>’nun ardındaki hikâye
			</div>
			<div class="section-text">
				<span>Beş Harfli Kelime Oyunu</span>'nun tasarımı, <strong>Kelime Bulmaca</strong> kategorisindeki oyunların yüksek eğlence potansiyelini fark etmem ve bu alanda kaliteli bir mobil uygulamanın olmamasını görmemle başladı. İlk fikir, mobil oyunu mümkün olduğunca basit ve minimalist tutmak ve kullanıcı deneyimini tek bir ekran üzerinde barındırmaktı. Konsept o kadar basitti ki oyunu yalnızca tek bir dille sınırlandırmıyor, o dilin daha da alt kümesine, yalnızca beş harfli kelimelere odaklanmayı hedefliyordu.
			</div>
			<div class="section-text">
				Başlıca geliştirme aracı olarak açık kaynak kodlu yapısı, geniş topluluğu, kapsamlı dokümantasyonu ve her iki mobil platforma güçlü desteğinden dolayı <a target="_blank" href="https://godotengine.org/"><strong>Godot Engine</strong></a>'i seçtim. İhtiyacım olan her şeyi sağlıyor muydu? Hayır. Ancak bunu geri adım atmak için bir bahane değil, aksine, Godot topluluğuna katkıda bulunmak ve eksik platforma özel özellikleri çeşitli <a target="_blank" href="https://github.com/cengiz-pz?tab=repositories"><strong>Godot eklentileri</strong></a> geliştirerek bu boşlukları doldurmak için bir fırsat olarak gördüm.
			</div>
			<div class="section-text">
				Aylar süren geliştirme ve kalite kontrol aşamalarından sonra, <span>Beş Harfli Kelime Oyunu</span> Android platformunda yayınlandı ve kullanıcılarını beş harfli Türkçe kelime bulmacaları dünyasında keyifli bir yolculuğa çıkardı.
			</div>
			<div class="section-text">
				<span>Beş Harfli Kelime Oyunu</span>'nun yayınlanmasından kısa süre sonra, altı ve daha sonra dört harfli Türkçe kelimeleri destekleyen ek oyunlar geliştirme planları geldi ve <span>Altı Harfli Kelime Oyunu</span> ile <span>Dört Harfli Kelime Oyunu</span> ortaya çıktı.
			</div>
			<div class="section-text">
				Üç harfli kelimeler çok kolay, yedi harfli kelimeler ise çok zor olduğu için Türkçe’deki bulmaca macerası tamamlanmış görünüyordu – en azından bu özel bulmaca türü için. Artık başka bir dilde maceraya atılmanın zamanı gelmişti. Hangi dil daha iyi olurdu ki? Elbette eşimin ana dili olan Kırgızca! Bu dilde neredeyse hiç mobil bulmaca oyunu yoktu! Sözlüğünü oluşturmakta bir süre zorlansam da <span>Беш Тамгалуу Сөз Оюну</span> yayınlandı, ardından <span>Алты Тамгалуу Сөз Оюну</span> ve <span>Төрт Тамгалуу Сөз Оюну</span> geldi.
			</div>
			<div class="section-text">
				Peki yolun sonuna gelmiş miydik? Android platformunda yayınlanan altı mobil oyun yeterli miydi? Herkesin konuştuğu veya öğrenmek istediği dili, yani İngilizceyi desteklemeyecek miydik? Hayır, İngilizce ihmal edilemezdi ve <span>Five-Letter Word Puzzle</span> doğdu, ardından da kardeşleri <span>Six-Letter Word Puzzle</span> ve <span>Four-Letter Word Puzzle</span> geldi.
			</div>
			<div class="section-text">
				Dokuz oyunun hepsi hazırdı ve Android cihazı olan tüm arkadaşlarımız ve ailemize bu oyunları denetmek için sabırsızlanıyorduk! İlk tepkiler olumluydu, ancak birçok kişi bulmacaları tamamlamada zorlandığını belirtti. Bu geri bildirimi not ettik, ancak oyunlarımızı Apple cihazlarda da sunmaya hazır olduğumuzu düşündük.
			</div>
			<div class="section-text">
				İlk adım <span>Beş Harfli Kelime Oyunu</span>'nun iOS versiyonuydu ve her şey planlandığı gibi gitti 👍👍. Sıradaki <span>Altı Harfli Kelime Oyunu</span> idi ve büyük bir şok yaşadık 😨! Daha önce farkında olmadığımız <a target="_blank" href="https://developer.apple.com/app-store/review/guidelines/#spam"><strong>Tasarım Spami</strong></a> adlı bir App Store inceleme kuralına takıldık. Bu, minimalist arayüze sahip birden fazla yalın oyunu sunma planımızı – en azından iOS platformunda – imkânsız hâle getirdi 🙁.
			</div>
			<div class="section-text">
				iOS platformundaki planlarımızdan vaz mı geçecektik yoksa dokuz oyunun tamamını iPhone kullanıcıları için tek bir uygulamada birleştirecek miydik? Elbette cevap, dokuz oyunu tek çatı altında birleştirmekti! Bu, yeni ve genişletilmiş <span>Beş Harfli Kelime Oyunu</span>'nun doğuşuydu! <i>Evet, ismi koruduk.</i> İlk başta Frankenstein’a benzese de, yeni <span>Beş Harfli Kelime Oyunu</span> zamanla dokuz modunun hepsinde kusursuz çalışan bir rock yıldızına dönüştü.
			</div>
			<div class="section-text">
				Peki işimiz bitmiş miydi? Hayır! Yeni <span>Beş Harfli Kelime Oyunu</span>'na diğerlerinden ayıracak bir şeyler vermemiz gerekiyordu ve arkadaşlarımız ile ailemizden gelen geri bildirimleri dikkate almak bunu sağlamanın en iyi yoluydu! Evet, daha önce varsayılan zorluk seviyesi olan ve şimdi ‘Zor’ olarak yeniden adlandırılan seviyede zorlananlar için yeni bir ‘Kolay’ zorluk seviyesi ekledik. Ama bununla yetinmedik; ‘Kolay’dan bile daha kolay olan ve ismini <a target="_blank" href="https://www.trt1.com.tr/programlar/lingo-turkiye"><strong>TRT'de yayınlanan popüler TV programı</strong></a>'ndan alan ‘Lingo’ zorluk seviyesini de ekledik. ‘Lingo’ zorluk seviyesinde, bulmaca başladığında ilk harf doğrudan veriliyor ve bulmacayı başarılı bir şekilde tamamlama hedefine oyuncularımızı daha da yaklaştırıyor.
			</div>
			<div class="section-text">
				<strong>- Cengiz</strong><br/>
				<strong>[Tasarımcı & Geliştirici]</strong>
			</div>
		</div>
	</div>
</section>
