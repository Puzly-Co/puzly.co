---
title: Beş Harfli Kelime Oyunu - Puzly.Co
layout: default_kg
body_class: page-home
show_language_options: true
---


{% capture page_url %}{{ site.url }}{{ site.baseUrl }}{{ page.url }}{% endcapture %}
{% capture game_title %}{{ page.title | remove: " - Puzly.Co" }}{% endcapture %}
{% include share-script.html shareUrl=page_url shareText='Келиңиз, бул сонун табышмак оюнун ойнойлу!' shareTitle=game_title %}


<section id="games" class="section games-section game-1-section">
	<div class="container">
		<div class="section-content">
			<div class="section-title">
				Жаңы <span>Beş Harfli Kelime Oyunu</span> — тогуз оюнду бириктирген сөз табуучу оюн.
			</div>
			<div class="section-text">
				Жакшыртылган <span>Beş Harfli Kelime Oyunu</span> — ар кандай жаштагы табышмак сүйүүчүлөр үчүн жаратылган, татаал бирок кызыктуу сөз оюн. Буга чейин өз-өзүнчө сунушталган тогуз оюнду бириктирген бул колдонмодо кыргыз, түрк жана англис тилдеринде төрттөн алтыга чейинки сөздөрдү табууга болот. Ошондой эле эми үч түрдүү кыйынчылык деңгээлин тандасаңыз болот. Эгерде кызыктуу кыргыз, түрк же англис тилиндеги сөз оюнун ойноого даяр болсоңуз, төмөндөгү шилтеме аркылуу <span>Beş Harfli Kelime Oyunu</span>'н бекер жүктөп алсаңыз болот.
			</div>
			<div class="section-badge">
				<a href="https://play.google.com/store/apps/details?id=co.puzly.xhko" target="_blank"><img alt="Google Playден жүктөп алыңыз" id="gp-logo-img" width="188" height="56" src="/images/google-play-badge-kg.png" /></a>
				<a href="https://apps.apple.com/app/be%C5%9F-harfli-kelime-oyunu/id6596769905" target="_blank"><img alt="App Storeдон жүктөп алыңыз" id="as-logo-img" width="188" height="56" src="/images/app-store-badge-kg.png" /></a>
			</div>
			<button class="share-button" />
		</div>
	</div>
</section>

<section id="games" class="section games-section development-story" id="story">
	<div class="container">
		<div class="section-content">
			<div class="section-title">
				<span>Beş Harfli Kelime Oyunu</span> оюнуна болгон тарых
			</div>
			<div class="section-text">
				<span>Beş Harfli Kelime Oyunu</span> оюну <strong>Сөз табышмак</strong> категориясындагы оюндардын чоң көңүл ачуучу потенциалын байкап, бирок жакшы сапаттагы мобилдик версиясы жок экенин көргөнүмдө жаралган. Баштапкы идея мобилдик оюнду мүмкүн болушунча жөнөкөй жана минималист кылуу жана бардык колдонуучу тажрыйбасын бир эле экранда камтууу болчу. Концепция ушунчалык жөнөкөй болчу: оюн бир гана тилге эмес, ошол тилдеги беш тамгадан турган сөздөрдүн жыйнагына багытталган.
			</div>
			<div class="section-text">
				Оюнду иштеп чыгуу үчүн мен негизги курал катары <a target="_blank" href="https://godotengine.org/"><strong>Godot Engine</strong></a>'ди тандадым. Себеби ал ачык булактуу, чоң коомчулукка ээ, кеңири документтелген жана мобилдик платформалар үчүн мыкты колдоого ээ. Баары бар беле? Жок. Бирок бул чектөө тоскоол болбостон, Godot коомчулугуна кайтарым кылып, менин дизайнымда жетишпеген функцияларды камсыздаган бир нече ачык жеткиликтүү <a target="_blank" href="https://github.com/cengiz-pz?tab=repositories"><strong>Godot плагиндерин</strong></a> иштеп чыгууга мүмкүнчүлүк берди.
			</div>
			<div class="section-text">
				Айлап иштеп чыгуу жана тестирлөө процесстеринен кийин, <span>Beş Harfli Kelime Oyunu</span> Android платформасында жарык көрдү жана колдонуучуларды беш тамгалуу түркчө сөз табышмактар дүйнөсүнө кубанычтуу сапарга алып чыкты.
			</div>
			<div class="section-text">
				<span>Beş Harfli Kelime Oyunu</span> чыккандан көп өтпөй, алты тамгадан жана кийин төрт тамгадан турган түркчө сөздөрдү камтыган кошумча оюндарды жасоо пландары жаралып, <span>Altı Harfli Kelime Oyunu</span> жана <span>Dört Harfli Kelime Oyunu</span> түзүлдү.
			</div>
			<div class="section-text">
				Үч тамгалуу сөздөр өтө жеңил, жети тамгалуулар өтө оор болгондуктан, түрк тилиндеги бул табышмактуу саякат аягына чыккандай болду – жок эле дегенде бул оюн түрү үчүн. Эми башка тилде жаңы саякат баштоонун убагы келген эле. Эң ылайыктуу тил – жубайымдын эне тили болгон кыргыз тили! Бул тилде дээрлик эч кандай мобилдик табышмак оюн жок болчу! Сөздүгүн түзүүдө бир топ кыйынчылыктар болгон соң, <span>Беш Тамгалуу Сөз Оюну</span> жарык көрдү, артынан <span>Алты Тамгалуу Сөз Оюну</span> жана <span>Төрт Тамгалуу Сөз Оюну</span> чыкты.
			</div>
			<div class="section-text">
				Баары бүттүбү? Android үчүн чыгарылган алты оюн жетиштүүбү? Бардык адамдар сүйлөгөн же үйрөнгүсү келген тилди – англис тилин – колдобой койобузбу? Жок, англис тили унутулбашы керек болчу жана <span>Five-Letter Word Puzzle</span> жаралып, артынан <span>Six-Letter Word Puzzle</span> жана <span>Four-Letter Word Puzzle</span> кошулду.
			</div>
			<div class="section-text">
				Бардык тогуз оюн даяр болуп, Android телефону бар бардык досторубуз жана үй-бүлөбүз менен аларды бөлүшүүгө кубанып жаттык! Алгачкы жооптор оң болду, бирок көптөр табышмактарды бүтүрүүдө кыйналып жатышканын айтышты. Бул пикирлерди эске алдык, бирок Apple түзмөктөрүнө да оюндарды чыгарууга даяр элек.
			</div>
			<div class="section-text">
				Биринчи кадам <span>Beş Harfli Kelime Oyunu</span>'нун iOS версиясы болду жана баары пландагыдай өттү 👍👍. Кийинкиси <span>Altı Harfli Kelime Oyunu</span> эле жана күтүлбөгөн чоң тоскоолдукту жолуктурдук 😨! Буга чейин кабарыбыз болбогон <a target="_blank" href="https://developer.apple.com/app-store/review/guidelines/#spam"><strong>Дизайн Спам</strong></a> аттуу App Store эрежесине каршы келдик. Бул iOS платформасында көптөгөн жөнөкөй оюндарды өз-өзүнчө чыгаруу пландарын мүмкүн эместей кылды 🙁.
			</div>
			<div class="section-text">
				iOS пландарынан баш тартабызбы же бардык тогуз оюнду iPhone колдонуучулары үчүн бириктиребизби? Албетте, жообу — бириктиребиз! Жаңы жана кеңейтилген <span>Beş Harfli Kelime Oyunu</span>'нун таң атканы эле! <i>Ооба, аталышын өзгөртпөдүк.</i> Башында Франкенштейн сымал көрүнгөнү менен, жаңы <span>Beş Harfli Kelime Oyunu</span> акырындап тогуз режимде да сонун иштеген жылдызга айланды.
			</div>
			<div class="section-text">
				Бардыгы бүттүбү? Жок! Жаңы <span>Beş Harfli Kelime Oyunu</span>'на өзгөчөлүк кошушубуз керек болчу, бул үчүн досторубуз менен үй-бүлөбүздүн пикирлерин угуу эң жакшы жол болчу! Ооба, мурдагы “Кыйын” деңгээлде кыйналгандар үчүн “Жеңил” деңгээлин коштук. Бирок бул менен токтогон жокпуз; “Жеңил”ден да оңой деңгээл коштук — бул <a target="_blank" href="https://www.trt1.com.tr/programlar/lingo-turkiye"><strong>TRT телеканалында көрсөтүлгөн</strong></a> популярдуу шоудан атын алган “Линго” болду. “Линго” деңгээлинде табышмак башталганда алгачкы тамга дароо берилет, бул болсо табышмакты ийгиликтүү бүтүрүүнү ого бетер жеңилдетет.
			</div>
			<div class="section-text">
				<strong>- Cengiz</strong><br/>
				<strong>[Дизайнер жана Иштеп чыгуучу]</strong>
			</div>
		</div>
	</div>
</section>
