---
title: Beş Harfli Kelime Bulucu - Puzly.Co
layout: default
body_class: page-home
show_language_options: true
---

{% include dictionary-loader-tr.html %}
{% include form-row-template-en.html %}
{% include five-letter-helper.html %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">FIVE-LETTER TURKISH WORD FINDER</span>
		<div class="button-container">
			<button type="button" onclick="addRow()">ADD ROW</button>
			<button type="button" onclick="handleSuggestionRequest()">SUGGEST WORDS</button>
			<button type="button" onclick="resetForm()">CLEAR</button>
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
			<span class="title">SUGGESTED WORDS</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
