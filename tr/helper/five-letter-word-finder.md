---
title: Five-Letter Word Finder - Puzly.Co
layout: default_tr
body_class: page-home
show_language_options: true
---

{% include dictionary-loader-tr.html %}
{% include form-row-template-tr.html %}
{% include five-letter-helper.html %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">BEŞ HARFLİ İNGİLİZCE KELİME BULUCU</span>
		<div class="button-container">
			<button type="button" onclick="addRow()">SIRA EKLE</button>
			<button type="button" onclick="handleSuggestionRequest()">KELİME ÖNER</button>
			<button type="button" onclick="resetForm()">TEMİZLE</button>
		</div>
		<form id="word_form"></form>
		<div class="suggestions-container">
			<span class="title">ÖNERİLEN KELİMELER</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
