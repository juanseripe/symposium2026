---
layout: default
title: Program
---

## {{ page.title }}

---

<h3>Thursday, March 12</h3>

<table class="program">
  <thead>
    <tr>
      <th style="width: 20%;">Time</th>
      <th>Activity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>11:30–13:30</strong></td>
      <td>
        <strong>Arrival and distribution of name tags</strong><br>
        <em>(B.307 – Multipurpose room)</em><br>
        Refreshments and snacks will be served
      </td>
    </tr>

    <tr>
      <td><strong>13:30–14:00</strong></td>
      <td>
        <strong>Opening speech</strong><br>
        <em>(B.307 – Multipurpose room)</em>
      </td>
    </tr>

    <tr>
      <td><strong>14:00–15:30</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-1" | first %}
              <strong>
               <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-2" | first %}
              <strong>
               <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign workshop = site.workshops_en | where: "slug", "atelier-1" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign workshop = site.workshops_en | where: "slug", "atelier-2" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>15:30–16:00</strong></td>
      <td>
        <strong>Refreshment</strong> <br>
        <em>(B.307 – Multipurpose room)</em>
      </td>
    </tr>

    <tr>
      <td><strong>16:00–17:30</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-3" | first %}
              <strong>
               <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-4" | first %}
              <strong>
               <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign workshop = site.workshops_en | where: "slug", "atelier-3" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>17:30–20:30</strong></td>
      <td>
        <strong>Cocktail reception</strong> and speech by the HEC PhD Program Director<br>
        <em>(A.878 – Guy-Fréchette)</em>
      </td>
    </tr>
  </tbody>
</table>

---

<h3>Friday, March 13</h3>

<table class="program">
  <thead>
    <tr>
      <th style="width: 20%;">Time</th>
      <th>Activity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>08:00–09:00</strong></td>
      <td>
        <strong>Welcome Breakfast</strong><br>
        <em>(D.726 – Creativity room)</em>
      </td>
    </tr>

    <tr>
      <td><strong>09:00–10:30</strong></td>
      <td>
        {% assign workshop = site.workshops_en | where: "slug", "atelier-4" | first %}
        <strong>
        <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
        </strong><br>
        <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
        {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
      </td>
    </tr>

    <tr>
      <td><strong>10:30–10:45</strong></td>
      <td><strong>Break</strong> (15 minutes)</td>
    </tr>

    <tr>
      <td><strong>10:45–12:15</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              <strong>Roundtable session</strong><br>
              <em>(A.551)</em>
            </td>
            <td>
              {% assign workshop = site.workshops_en | where: "slug", "atelier-5" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-5" | first %}
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
      <td><strong>12:15–13:30</strong></td>
      <td>
        <strong>Lunch</strong><br>
        <em>(D.726 – Creativity room)</em>
      </td>
    </tr>

    <tr>
      <td><strong>13:30–15:00</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-6" | first %}
              <strong>
               <a href="{{ session.url | relative_url }}">{{ session.title }}</a>
              </strong><br>
              <em>({{ session.room_code }} — {{ session.room_name }})</em><br>
              {{ session.theme }}
            </td>
            <td>
              {% assign session = site.sessions_en | where: "slug", "presentation-7" | first %}
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
      <td><strong>15:00–15:30</strong></td>
      <td>
        <strong>Refreshment</strong><br>
        <em>(D.726 – Creativity room)</em>
      </td>
    </tr>

    <tr>
      <td><strong>15:30–17:00</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              {% assign workshop = site.workshops_en | where: "slug", "atelier-6" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
            <td>
              {% assign workshop = site.workshops_en | where: "slug", "atelier-7" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
            <td>
              <{% assign workshop = site.workshops_en | where: "slug", "atelier-8" | first %}
              <strong>
               <a href="{{ workshop.url | relative_url }}">{{ workshop.title }}</a>
              </strong><br>
              <em>({{ workshop.room_code }} — {{ workshop.room_name }})</em><br>
              {{ workshop.theme }} <em>by {{ workshop.facilitator }}</em>
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>17:00–17:30</strong></td>
      <td>
        <strong>Closing speeches</strong><br>
        <em>(A.878 – Guy-Fréchette)</em>
      </td>
    </tr>

    <tr>
      <td><strong>17:30–20:30</strong></td>
      <td>
        <strong>Cocktail</strong><br>
        <em>(A.878 – Guy-Fréchette)</em>
      </td>
    </tr>
  </tbody>
</table>