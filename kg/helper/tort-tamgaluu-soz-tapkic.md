---
title: Dört Harfli Kırgızca Kelime Bulucu - Puzly.Co
layout: default_kg
body_class: page-home
show_language_options: true
---

{% include dictionary-loader.html dictionaryFilePath='/data/kg/kg_4_dictionary.json' %}
{% include form-row-template.html numLetters=4 correctPlaceText='doğru yerde' wrongPlaceText='var ama burada değil' absentText='kelimede yok' %}
{% include helper-script.html numLetters=4 %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">ТӨРТ ТАМГАЛУУ СӨЗ ТАПКЫЧ</span>
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
		<div>
			<div class="keyboard-container">
				<button type="button" onclick="enterLetter('А')">А</button>
				<button type="button" onclick="enterLetter('Б')">Б</button>
				<button type="button" onclick="enterLetter('В')">В</button>
				<button type="button" onclick="enterLetter('Г')">Г</button>
				<button type="button" onclick="enterLetter('Д')">Д</button>
				<button type="button" onclick="enterLetter('Е')">Е</button>
				<button type="button" onclick="enterLetter('Ё')">Ё</button>
				<button type="button" onclick="enterLetter('Ж')">Ж</button>
				<button type="button" onclick="enterLetter('З')">З</button>
				<button type="button" onclick="enterLetter('И')">И</button>
				<button type="button" onclick="enterLetter('Й')">Й</button>
				<button type="button" onclick="enterLetter('К')">К</button>
			</div>
			<div class="keyboard-container">
				<button type="button" onclick="enterLetter('Л')">Л</button>
				<button type="button" onclick="enterLetter('М')">М</button>
				<button type="button" onclick="enterLetter('Н')">Н</button>
				<button type="button" onclick="enterLetter('О')">О</button>
				<button type="button" onclick="enterLetter('Ө')">Ө</button>
				<button type="button" onclick="enterLetter('П')">П</button>
				<button type="button" onclick="enterLetter('Р')">Р</button>
				<button type="button" onclick="enterLetter('С')">С</button>
				<button type="button" onclick="enterLetter('Т')">Т</button>
				<button type="button" onclick="enterLetter('У')">У</button>
				<button type="button" onclick="enterLetter('Ү')">Ү</button>
				<button type="button" onclick="enterLetter('Ф')">Ф</button>
			</div>
			<div class="keyboard-container">
				<button type="button" onclick="enterLetter('Х')">Х</button>
				<button type="button" onclick="enterLetter('Ц')">Ц</button>
				<button type="button" onclick="enterLetter('Ч')">Ч</button>
				<button type="button" onclick="enterLetter('Ш')">Ш</button>
				<button type="button" onclick="enterLetter('Щ')">Щ</button>
				<button type="button" onclick="enterLetter('Ъ')">Ъ</button>
				<button type="button" onclick="enterLetter('Ы')">Ы</button>
				<button type="button" onclick="enterLetter('Ь')">Ь</button>
				<button type="button" onclick="enterLetter('Э')">Э</button>
				<button type="button" onclick="enterLetter('Ю')">Ю</button>
				<button type="button" onclick="enterLetter('Я')">Я</button>
			</div>
		</div>
		<div class="suggestions-container">
			<span class="title">СУНУШТАЛГАН СӨЗДӨР</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
