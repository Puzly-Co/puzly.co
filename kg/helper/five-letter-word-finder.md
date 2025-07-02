---
title: Beş Harfli İngilizce Kelime Bulucu - Puzly.Co
layout: default_kg
body_class: page-home
show_language_options: true
---

{% include dictionary-loader.html dictionaryFilePath='/data/en/en_5_dictionary.json' %}
{% include form-row-template.html numLetters=5 correctPlaceText='doğru yerde' wrongPlaceText='var ama burada değil' absentText='kelimede yok' %}
{% include helper-script.html numLetters=5 %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">БЕШ ТАМГАЛУУ АНГЛИЧЕ СӨЗ ТАПКЫЧ</span>
		<div class="button-container">
			<button type="button" onclick="addRow()">САП КОШ</button>
			<button type="button" onclick="handleSuggestionRequest()">СӨЗ СУНУШТОО</button>
			<button type="button" onclick="resetForm()">ТАЗАЛОО</button>
		</div>
		<div class="usage-guide-container">
			<div>
				<div class="status-box correct-place-box"></div>
				<span class="usage-guide-text">Эгер тамга сөздө бар болсо жана туура жерде болсо, бул кутучаны тандаңыз.</span>
			</div>
			<div>
				<div class="status-box wrong-place-box"></div>
				<span class="usage-guide-text">Эгер тамга сөздө бар болсо, бирок туура эмес жерде болсо, бул кутучаны тандаңыз.</span>
			</div>
			<div>
				<div class="status-box absent-box"></div>
				<span class="usage-guide-text">Эгер тамга сөздүн ичинде жок болсо, бул кутучаны тандаңыз.</span>
			</div>
		</div>
		<form id="word_form"></form>
		<div class="suggestions-container">
			<span class="title">СУНУШТАЛГАН СӨЗДӨР</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
