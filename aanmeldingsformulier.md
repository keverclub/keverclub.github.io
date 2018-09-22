---
layout: page
title: Aanmeldingsformulier
description: In te vullen aanmeldingsformulier
sitemap:
    priority: 0.7
    lastmod: 2018-09-22
    changefreq: weekly
---
<h2 align="center">Aanmeldingsformulier</h2>

<section>
    <form method="POST" action="https://formspree.io/{{site.email}}">
      <div class="field">
        <label for="name">Je naam (verplicht)</label>
        <input type="text" name="name" id="name" />
      </div>
      <div class="field">
        <label for="name">Roepnaam</label>
        <input type="text" name="roepname" id="roepname" />
      </div>
      <div class="field">
        <label for="email">Je email (verplicht)</label>
        <input type="text" name="email" id="email" />
      </div>
      <div class="field">
        <label for="name">Je telefoon</label>
        <input type="text" name="tel" id="tel" />
      </div>
      <div class="field">
        <label for="name">Geslacht</label>
        <input list="geslacht" name="geslacht">
        <datalist id="geslacht">
            <option value="Mannelijk"></option>
            <option value="Vrouwelijk"></option>
        </datalist>
      </div>
      <div class="field">
        <label for="message">Geboorte Datum</label>
        <form>
            <input type="date" name="bday" max="2010-01-02">
        </form>
      </div>
      <div class="field">
        <label for="name">Straatnaam</label>
        <input type="text" name="straatname" id="straatname" />
      </div>
      <div class="field">
        <label for="name">Huisnummer</label>
        <input type="text" name="huisnummer" id="huisnummer" />
      </div>
      <div class="field">
        <label for="name">Postcode</label>
        <input type="text" name="postcode" id="postcode" />
      </div>
      <div class="field">
        <label for="name">Plaats</label>
        <input type="text" name="plaats" id="plaats" />
      </div>
      
      <h3>Gegevens Auto</h3>
      
      <div class="field">
        <label for="name">Merk</label>
        <input type="text" name="merk" id="merk" />
      </div>
      <div class="field">
        <label for="name">Type</label>
        <input type="text" name="type" id="type" />
      </div>
      <div class="field">
        <label for="name">Bouwjaar</label>
        <input type="text" name="bouwjaar" id="bouwjaar" />
      </div>
      <div class="field">
        <label for="name">Kleur</label>
        <input type="text" name="kleur" id="kleur" />
      </div>
      <div class="field">
        <label for="name">Kenteken</label>
        <input type="text" name="kenteken" id="kenteken" />
      </div>
      
      <div class="field">
        <label for="message">Bijzonderheden</label>
        <textarea name="message" id="message" rows="3"></textarea>
      </div>
      <h3>Contributiebedragen</h3>
halfjaar € 25,-- ; kalenderjaar € 50,--
over te maken op rekeningnummer NL18RABO0174106777 t.n.v. Keverclub Roermond

KvK Limburg Noord 40.17.74.29
      <ul class="actions">
        <li><input type="submit" value="Verstuur Bericht" /></li>
      </ul>
    </form>
  </section>
