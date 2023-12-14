---
title: Five-Letter Word Finder - Puzly.Co
layout: default
body_class: page-home
show_language_options: true
---

{% include dictionary-loader-en.html %}
{% include form-row-template-en.html %}
{% include five-letter-helper.html %}

<section class="helper-content">
	<div class="form-container">
		<span class="title">FIVE-LETTER ENGLISH WORD FINDER</span>
		<div class="button-container">
			<button type="button" onclick="addRow()">ADD ROW</button>
			<button type="button" onclick="handleSuggestionRequest()">SUGGEST WORDS</button>
			<button type="button" onclick="resetForm()">CLEAR</button>
		</div>
		<form id="word_form"></form>
		<div class="suggestions-container">
			<span class="title">SUGGESTED WORDS</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
