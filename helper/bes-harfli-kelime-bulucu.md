---
title: Beş Harfli Kelime Bulucu - Puzly.Co
layout: default
body_class: page-home
show_language_options: true
---

{% include dictionary-loader.html dictionaryFilePath='/data/tr/dictionary.json' %}
{% include form-row-template.html correctPlaceText='correct place' wrongPlaceText='wrong place' absentText='absent' %}
{% include five-letter-helper.html %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">FIVE-LETTER TURKISH WORD FINDER</span>
		<div class="button-container">
			<button type="button" onclick="addRow()">ADD ROW</button>
			<button type="button" onclick="handleSuggestionRequest()">SUGGEST WORDS</button>
			<button type="button" onclick="resetForm()">CLEAR</button>
		</div>
		<div class="usage-guide-container">
			<div>
				<div class="status-box correct-place-box"></div>
				<span class="usage-guide-text">Select this box when the letter exists in the word and is in the correct place.</span>
			</div>
			<div>
				<div class="status-box wrong-place-box"></div>
				<span class="usage-guide-text">Select this box when the letter exists in the word, but is in the wrong place.</span>
			</div>
			<div>
				<div class="status-box absent-box"></div>
				<span class="usage-guide-text">Select this box when the letter does not exist in the word.</span>
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
			<span class="title">SUGGESTED WORDS</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
