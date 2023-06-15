---
title: Puzly.Co
layout: default
body_class: page-home
---

<template id="guess-row-element-template">
	<style>
		input.letter-input {
			height: 48px;
			width: 48px;
			border-style: solid;
			border-width: 1px;
			border-radius: 4px;
			box-sizing: border-box;
			text-align: center;
			text-transform: capitalize;
			font-size: 2em;
			font-weight: bolder;
		}
		.letter-input-container {
			display: inline-block;
			width: 48px;
			padding: 0;
		}
		.radio-container {
			display: grid;
			grid-template-columns: 1fr 1fr 1fr;
		}
		.letter-input-container label {
			display: block;
			margin: 0;
			padding: 0;
			height: 13px;
			box-sizing: border-box;
			background-color: white;
			border-style: solid;
			border-width: 1px;
		}
		.letter-input-container input[type="radio"] {
			visibility: hidden;
			display: none;
		}
		.letter-input-container input[value="correct"] + label {
			border-color: greenyellow;
		}
		.letter-input-container input[value="exists"] + label {
			border-color: yellow;
		}
		.letter-input-container input[value="absent"] + label {
			border-color: gray;
		}
		.letter-input-container input[value="correct"]:checked + label {
			background-color: greenyellow;
		}
		.letter-input-container input[value="exists"]:checked + label {
			background-color: yellow;
		}
		.letter-input-container input[value="absent"]:checked + label {
			background-color: gray;
		}
		.letter-input-container:has(> .radio-container > input[value="correct"]:checked) > input[type="text"] {
			background-color: greenyellow;
			border-color: greenyellow;
		}
		.letter-input-container:has(> .radio-container > input[value="exists"]:checked) > input[type="text"] {
			background-color: yellow;
			border-color: yellow;
		}
		.letter-input-container:has(> .radio-container > input[value="absent"]:checked) > input[type="text"] {
			color: white;
			background-color: gray;
			border-color: gray;
		}
		/* Tooltip text */
		.tooltip + .tooltip-text {
			visibility: hidden;
			margin-top: 12px;
			margin-left: -10px;
			padding: 2px 5px;
			color: #fff;
			text-align: center;
			border-radius: 6px;
			/* Position the tooltip text - see examples below! */
			position: absolute;
			z-index: 1;
		}
		/* Show the tooltip text when you mouse over the tooltip container */
		.tooltip:hover + .tooltip-text {
			visibility: visible;
			background-color: #888;
		}
	</style>
	<div class="row-container">
		<div class="letter-input-container">
			<input type="text" maxlength="1" placeholder=" " class="letter-input" name="letter_1"/>
			<div class="radio-container">
				<input type="radio" name="state_1" value="correct" id="letter_1_correct">
				<label for="letter_1_correct" class="tooltip"></label>
				<span class="tooltip-text">doğru yerde</span>
				<input type="radio" name="state_1" value="exists" id="letter_1_exists">
				<label for="letter_1_exists" class="tooltip"></label>
				<span class="tooltip-text">var ama burada değil</span>
				<input type="radio" name="state_1" value="absent" id="letter_1_absent">
				<label for="letter_1_absent" class="tooltip"></label>
				<span class="tooltip-text">kelimede yok</span>
			</div>
		</div>
		<div class="letter-input-container">
			<input type="text" maxlength="1" placeholder=" " class="letter-input" name="letter_2"/>
			<div class="radio-container">
				<input type="radio" name="state_2" value="correct" id="letter_2_correct">
				<label for="letter_2_correct" class="tooltip"></label>
				<span class="tooltip-text">doğru yerde</span>
				<input type="radio" name="state_2" value="exists" id="letter_2_exists">
				<label for="letter_2_exists" class="tooltip"></label>
				<span class="tooltip-text">var ama burada değil</span>
				<input type="radio" name="state_2" value="absent" id="letter_2_absent">
				<label for="letter_2_absent" class="tooltip"></label>
				<span class="tooltip-text">kelimede yok</span>
			</div>
		</div>
		<div class="letter-input-container">
			<input type="text" maxlength="1" placeholder=" " class="letter-input" name="letter_3"/>
			<div class="radio-container">
				<input type="radio" name="state_3" value="correct" id="letter_3_correct">
				<label for="letter_3_correct" class="tooltip"></label>
				<span class="tooltip-text">doğru yerde</span>
				<input type="radio" name="state_3" value="exists" id="letter_3_exists">
				<label for="letter_3_exists" class="tooltip"></label>
				<span class="tooltip-text">var ama burada değil</span>
				<input type="radio" name="state_3" value="absent" id="letter_3_absent">
				<label for="letter_3_absent" class="tooltip"></label>
				<span class="tooltip-text">kelimede yok</span>
			</div>
		</div>
		<div class="letter-input-container">
			<input type="text" maxlength="1" placeholder=" " class="letter-input" name="letter_4"/>
			<div class="radio-container">
				<input type="radio" name="state_4" value="correct" id="letter_4_correct">
				<label for="letter_4_correct" class="tooltip"></label>
				<span class="tooltip-text">doğru yerde</span>
				<input type="radio" name="state_4" value="exists" id="letter_4_exists">
				<label for="letter_4_exists" class="tooltip"></label>
				<span class="tooltip-text">var ama burada değil</span>
				<input type="radio" name="state_4" value="absent" id="letter_4_absent">
				<label for="letter_4_absent" class="tooltip"></label>
				<span class="tooltip-text">kelimede yok</span>
			</div>
		</div>
		<div class="letter-input-container">
			<input type="text" maxlength="1" placeholder=" " class="letter-input" name="letter_5"/>
			<div class="radio-container">
				<input type="radio" name="state_5" value="correct" id="letter_5_correct">
				<label for="letter_5_correct" class="tooltip"></label>
				<span class="tooltip-text">doğru yerde</span>
				<input type="radio" name="state_5" value="exists" id="letter_5_exists">
				<label for="letter_5_exists" class="tooltip"></label>
				<span class="tooltip-text">var ama burada değil</span>
				<input type="radio" name="state_5" value="absent" id="letter_5_absent">
				<label for="letter_5_absent" class="tooltip"></label>
				<span class="tooltip-text">kelimede yok</span>
			</div>
		</div>
	</div>
</template>

<script>
	class GuessRow extends HTMLElement {
		constructor() {
			super();
			const template = document.getElementById(
				"guess-row-element-template"
			).content;
			const shadowRoot = this.attachShadow({ mode: "open" });
			shadowRoot.appendChild(template.cloneNode(true));
		}
  
		connectedCallback() {
			this.shadowRoot.addEventListener('keyup', this.handleKeyup.bind(this));
		}

		disconnectedCallback() {
			this.shadowRoot.removeEventListener('keyup', this.handleKeyup.bind(this));
		}
		
		handleKeyup(e) {
			var target = e.srcElement || e.target;
			var maxLength = parseInt(target.attributes["maxlength"].value, 10);
			var myLength = target.value.length;
			if (myLength >= maxLength) {
				var next = target.parentNode;
				while (next = next.nextElementSibling) {
					if (next == null)
						break;
					if (next.classList.contains("letter-input-container")) {
						next.firstElementChild.focus();
						break;
					}
				}
			}
			// Move to previous field if empty (user pressed backspace)
			else if (myLength === 0) {
				var previous = target;
				while (previous = previous.previousElementSibling) {
					if (previous == null)
						break;
					if (previous.tagName.toLowerCase() === "input") {
						previous.focus();
						break;
					}
				}
			}
		}
	}

	customElements.define("guess-row-element", GuessRow);

	function addRow() {
		document.getElementById("word_form").appendChild(new GuessRow);
	}

	async function handleSuggestionRequest() {
		var rowMap = readFormData();
		var result = analyzeData(rowMap);
		
		var suggestions = await generateSuggestion(result.get("correctLetters"), result.get("existingLetters"), result.get("absentLetters"));
		displaySuggestions(suggestions);
	}

	function readFormData() {
		var rowMap = new Map();
		var rowNum = 1;
		Array.prototype.slice.call(document.getElementById("word_form").childNodes).forEach(function (el) {
			if (!!el.shadowRoot) {
				rowMap.set(rowNum, this.readRowData(el.shadowRoot.childNodes));
				rowNum++;
			}
		}.bind(this));
		return rowMap;
	}

	function analyzeData(rowMap) {
		// analyze data
		let result = new Map();
		var correctLetters = new Map();
		var existingLetters = new Map();
		var absentLetters = new Array();
		result.set("correctLetters", correctLetters);
		result.set("existingLetters", existingLetters);
		result.set("absentLetters", absentLetters);
		for (let [rowNumber, fieldMap] of rowMap) {
			// loop over each letter
			for (let i = 1; i <= 5; i++) {
				let letterValue = fieldMap.get(`letter_${i}`).toUpperCase();
				if (letterValue.length == 1) {
					let stateValue = fieldMap.get(`state_${i}`);
					if (stateValue === "correct") {
						correctLetters.set(i, letterValue);
					}
					else if (stateValue === "exists") {
						if (!existingLetters.has(i)) {
							existingLetters.set(i, new Array());
						}
						let arr = existingLetters.get(i);
						if (!arr.includes(letterValue)) {
							arr.push(letterValue);
						}
					}
					else if (stateValue === "absent") {
						if (!absentLetters.includes(letterValue)) {
							absentLetters.push(letterValue);
						}
					}
				}
			}
		}
		return result;
	}

	async function generateSuggestion(correctLetters, existingLetters, absentLetters) {
		// load dictionary data
		const response = await fetch('/data/bhko/dictionary.json');
		const jsonData = await response.json();
		const dictionaryData = new Map(Object.entries(jsonData));

		let suggestions = [...dictionaryData.keys()];
		
		// filter dictionary by correct letters
		for (let [letterIndex, letterValue] of correctLetters) {
			let i = suggestions.length;
			while (i--) {
				if (!(suggestions[i].charAt(letterIndex-1) === letterValue)) { 
					suggestions.splice(i, 1);
				}
			}
		}
		
		// filter dictionary by existing letters
		for (let [letterIndex, letterArray] of existingLetters) {
			let i = suggestions.length;
			while (i--) {
				if (letterArray.includes(suggestions[i].charAt(letterIndex-1)) || !letterArray.every(item => suggestions[i].includes(item))) { 
					suggestions.splice(i, 1);
				}
			}
		}
		
		// filter dictionary by absent letters
		for (let letterValue of absentLetters) {
			let i = suggestions.length;
			while (i--) {
				if (suggestions[i].includes(letterValue)) { 
					suggestions.splice(i, 1);
				}
			}
		}
		return suggestions;
	}

	function readRowData(elements) {
		var result = new Map();
		Array.prototype.slice.call(elements).forEach(function (el) {
			if (!el.name || el.disabled || ['file', 'reset', 'submit', 'button'].indexOf(el.type) > -1) {
				if (el.childElementCount > 0) {
					result = new Map([...result, ...this.readRowData(el.childNodes)]);
				}
			}
			else if (el.type === 'select-multiple') {
				Array.prototype.slice.call(el.options).forEach(function (option) {
					if (!option.selected) return;
					result.set(el.name, option.value);
				});
			}
			else if (['checkbox', 'radio'].indexOf(el.type) >-1 && !el.checked) {
				return result;
			}
			else {
				result.set(el.name, el.value);
			}
		}.bind(this));
		return result;
	}

	function displaySuggestions(suggestions) {
		let containerDiv = document.getElementById("suggestions_slot");
		containerDiv.innerHTML = suggestions.join(", ");
	}
</script>

<section class="helper-content">
	<div class="form-container">
		<span class="title">BEŞ HARFLİ KELİME BULUCU</span>
		<form id="word_form">
			<guess-row-element></guess-row-element>
		</form>
		<div class="button-container">
			<button type="button" onclick="addRow()">SIRA EKLE</button>
			<button type="button" onclick="handleSuggestionRequest()">KELİME ÖNER</button>
		</div>
		<div class="suggestions-container">
			<span class="title">ÖNERİLEN KELİMELER</span>
			<br />
			<span id="suggestions_slot"></span>
		</div>
	</div>
</section>
