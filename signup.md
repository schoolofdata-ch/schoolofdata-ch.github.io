---
layout: page
title: Anmelden
---

<section>
	<form method="post" action="#">
		<div class="row uniform">
			<div class="6u 12u$(xsmall)">
				<input type="text" name="demo-name" id="demo-name" value="" placeholder="Name" />
			</div>
			<div class="6u$ 12u$(xsmall)">
				<input type="email" name="demo-email" id="demo-email" value="" placeholder="Email" />
			</div>
			<div class="12u$">
				<div class="select-wrapper">
					<select name="participant-category" id="participant-category">
						<option value="">- Ich bin ein/eine.. -</option>
						<option value="1">Daten-anfanger</option>
						<option value="1">Excel fiend</option>
						<option value="1">Pivot wrangler</option>
						<option value="1">JSON monster</option>
					</select>
				</div>
			</div>
			<!--<div class="4u 12u$(small)">
				<input type="radio" id="participant-when-low" name="participant-when" checked>
				<label for="participant-when-low">1 Monat+</label>
			</div>
			<div class="4u 12u$(small)">
				<input type="radio" id="participant-when-normal" name="participant-when">
				<label for="participant-when-normal">2-4 Wochen</label>
			</div>
			<div class="4u$ 12u$(small)">
				<input type="radio" id="participant-when-high" name="participant-when">
				<label for="participant-when-high">Sofort möglich</label>
			</div>
			<div class="6u 12u$(small)">
				<input type="checkbox" id="demo-copy" name="demo-copy">
				<label for="demo-copy">Email me a copy</label>
			</div>
			<div class="6u$ 12u$(small)">
				<input type="checkbox" id="demo-human" name="demo-human" checked>
				<label for="demo-human">Not a robot</label>
			</div>-->
			<div class="12u$">
				<textarea name="demo-message" id="demo-message" placeholder="Sonstige Fragen oder wünschen?" rows="6"></textarea>
			</div>
			<div class="12u$">
				<ul class="actions">
					<li><input type="submit" value="Senden" class="special" /></li>
					<li><input type="reset" value="Reset" /></li>
				</ul>
			</div>
		</div>
	</form>
</section>
