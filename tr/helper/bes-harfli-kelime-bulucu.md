---
title: Beş Harfli Kelime Bulucu - Puzly.Co
layout: default_tr
body_class: page-home
show_language_options: true
---

{% include dictionary-loader.html dictionaryFilePath='/data/tr/dictionary.json' %}
{% include form-row-template.html correctPlaceText='doğru yerde' wrongPlaceText='var ama burada değil' absentText='kelimede yok' %}
{% include five-letter-helper.html %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">BEŞ HARFLİ TÜRKÇE KELİME BULUCU</span>
		<div class="button-container">
			<button type="button" onclick="addRow()">SIRA EKLE</button>
			<button type="button" onclick="handleSuggestionRequest()">KELİME ÖNER</button>
			<button type="button" onclick="resetForm()">TEMİZLE</button>
		</div>
		<div class="usage-guide-container">
			<div>
				<div class="status-box correct-place-box"></div>
				<span class="usage-guide-text">Harf kelimede mevcutsa ve doğru yerdeyse bu kutuyu seçin.</span>
			</div>
			<div>
				<div class="status-box wrong-place-box"></div>
				<span class="usage-guide-text">Harf sözcükte mevcutsa ancak yanlış yerdeyse bu kutuyu seçin.</span>
			</div>
			<div>
				<div class="status-box absent-box"></div>
				<span class="usage-guide-text">Kelime içerisinde ilgili harf bulunmadığında bu kutuyu seçin.</span>
			</div>
		</div>
		<form id="word_form"></form>
		<div class="keyboard-container">
			<button type="button" onclick="enterLetter('Ç')">Ç</button>
			<button type="button" onclick="enterLetter('Ğ')">Ğ</button>
			<button type="button" onclick="enterLetter('İ')">İ</button>
			<button type="button" onclick="enterLetter('Ö')">Ö</button>
			<button type="button" onclick="enterLetter('Ş')">Ş</button>
			<button type="button" onclick="enterLetter('Ü')">Ü</button>
		</div>
		<div class="suggestions-container">
			<span class="title">ÖNERİLEN KELİMELER</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
