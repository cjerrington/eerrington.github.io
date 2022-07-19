---
layout: page
title: Services
---

<p>What do I get?
What do you get when you hire me as your birth doula?

I am always willing to add to packages according to a clients needs but here is a snapshot of the typical services I offer.

<ul>
    <li>Two prenatal meetings together.</li>
    <li>One prenatal meeting with your provider (OB or midwife)</li>
    <li>Writing a birth plan together and putting together your birth team.</li>
    <li>Walking through labor positions and education on how we can help baby move into a good position for birth. </li>
    <li>On Call 24/7 leading up to your birth. </li>
    <li>Back-up doula on call if needed or requested</li>
    <li>Attendance at your labor and birth (at home, birth center or hospital or a combination of these.)</li>
    <li>1-2 hours of immediate postpartum support.</li>
    <li>1-2 post partum visits. </li>
    <li>List of local resources for prenatal and postpartum care.</li>
</ul>
</p>
    
<section>    
{% for service in site.data.services %}
    <article>
        <div class="content">
            <h3>{{ service.title }}</h3>
            <p>{{ service.desc }}</p>
        </div>
    </article>
 {% endfor %}
</section>