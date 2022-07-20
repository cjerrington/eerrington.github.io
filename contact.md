---
layout: page
title: Contact Me
---

<p>Feel free to reach out to me with your questions and I'll get back to you with you.</p>
<div class="row">
	<div class="6u 12u$(small)">
		<!-- Form -->
			<form name="survey-form" accept-charset="utf-8" action="https://formspree.io/f/mzbonrrl" method="post">
				<div class="row uniform">
					<div class="6u 12u$(xsmall)">
						<input type="text" name="name" id="name" value="" placeholder="Name" required="" />
					</div>
					<div class="6u$ 12u$(xsmall)">
						<input type="email" name="email" id="email" value="" placeholder="Email" required="" />
					</div>
					<div class="12u$">
						<input type="tel" name="telephone" id="telephone" placeholder="555-234-5678" required="">
					</div>
					<!-- Break -->
					<div class="12u$">
						<div class="select-wrapper">
							<select name="pregnancy" id="pregnancy" required="">
								<option value="" selected="" disabled="">How far along in you pregnancy are you?</option>
								<option value="Not Pregnant">Not Pregnant</option>
								<option value="1st Trimester">1st Trimester</option>
								<option value="2nd Trimester">2nd Trimester</option>
								<option value="3rd Trimester">3rd Trimester</option>
							</select>
						</div>
					</div>
					<!-- Break -->
					<div class="12u$">
						<textarea name="message" id="message" placeholder="Enter your message" rows="6"></textarea>
					</div>
					<!-- Break -->
					<div class="12u$">
						<ul class="actions">
							<li><input type="submit" value="Send Message" class="special" /></li>
							<li><input type="reset" value="Reset" /></li>
							<input type="hidden" name="_subject" id="email-subject" value="Contact From My Website">
						</ul>
					</div>
				</div>
			</form>
		</div>