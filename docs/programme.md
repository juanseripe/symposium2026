---
layout: default
title: Programme
---

## {{ page.title }}

---

<h3>Jeudi 12 mars</h3>

<table class="program">
  <thead>
    <tr>
      <th style="width: 15%;">Heure</th>
      <th>Activité</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>11 h 30 – 13 h 30</strong></td>
      <td>
        <strong>Arrivée et distribution des cocardes</strong><br>
        <em>(B.307 – Salle multifonctionnelle)</em><br>
        Rafraîchissements et collations servis
      </td>
    </tr>

    <tr>
      <td><strong>13 h 30 – 14 h 00</strong></td>
      <td>
        <strong>Mot d’ouverture</strong><br>
        <em>(B.307 – Salle multifonctionnelle)</em>
      </td>
    </tr>

    <tr>
      <td><strong>14 h 00 – 15 h 30</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-1" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-2" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-1" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-2" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>15 h 30 – 16 h 00</strong></td>
      <td>
        <strong>Pause</strong><br>
        <em>(B.307 – Salle multifonctionnelle)</em>
      </td>
    </tr>

    <tr>
      <td><strong>16 h 00 – 17 h 30</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-3" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-4" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-3" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>17 h 30 – 20 h 30</strong></td>
      <td>
        <strong>Cocktail</strong> et allocution de la direction du programme de doctorat de HEC Montréal<br>
        <em>(A.878 – Guy-Fréchette)</em>
      </td>
    </tr>
  </tbody>
</table>

<hr>

<h3>Vendredi 13 mars</h3>

<table class="program">
  <thead>
    <tr>
      <th style="width: 15%;">Heure</th>
      <th>Activité</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>08 h 00 – 09 h 00</strong></td>
      <td>
        <strong>Petit-déjeuner d’accueil</strong><br>
        <em>(D.726 – Salle de créativité)</em>
      </td>
    </tr>

    <tr>
      <td><strong>09 h 00 – 10 h 30</strong></td>
      <td>
        {% assign workshop = site.workshops | where: "slug", "atelier-4" | first %}
        <strong>
          <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
        </strong><br>
        <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
        {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
      </td>
    </tr>

    <tr>
      <td><strong>10 h 30 – 10 h 45</strong></td>
      <td><strong>Pause</strong> (15 minutes)</td>
    </tr>

    <tr>
      <td><strong>10 h 45 – 12 h 15</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              <strong>Table ronde</strong><br>
              <em>(A.551)</em>
            </td>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-5" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-5" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>12 h 15 – 13 h 30</strong></td>
      <td>
        <strong>Dîner</strong><br>
        <em>(D.726 – Salle de créativité)</em>
      </td>
    </tr>

    <tr>
      <td><strong>13 h 30 – 15 h 00</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-6" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign session = site. sessions | where: "slug", "presentation-7" | first %}
              <strong>
                <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>15 h 00 – 15 h 30</strong></td>
      <td>
        <strong>Pause</strong>
        <em>(D.726 – Salle de créativité)</em>
      </td>
    </tr>

    <tr>
      <td><strong>15 h 30 – 17 h 00</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-6" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-7" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign workshop = site.workshops | where: "slug", "atelier-8" | first %}
              <strong>
                <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>par {{ workshop.facilitator }}</em>
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>17 h 00 – 17 h 30</strong></td>
      <td>
        <strong>Mots de clôture</strong><br>
        <em>(A.878 – Guy-Fréchette)</em>
      </td>
    </tr>

    <tr>
      <td><strong>17 h 30 – 20 h 30</strong></td>
      <td>
        <strong>Cocktail</strong><br>
        <em>(A.878 – Guy-Fréchette)</em>
      </td>
    </tr>
  </tbody>
</table>