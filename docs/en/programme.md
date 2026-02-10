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
      <th style="width: 15%;">Time</th>
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
        <em>(B.307)</em>
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
              <strong>Workshop #2</strong><br>
              <em>(C.412)</em><br>
              Using Generative AI for Qualitative Research in the Montreal Joint PhD Program
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>15:30–16:00</strong></td>
      <td><strong>Refreshment</strong> <em>(B.307)</em></td>
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
              <strong>Workshop #3</strong><br>
              <em>(C.406)</em><br>
              Paul and Karl’s
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
      <th style="width: 15%;">Time</th>
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
        <strong>Workshop #4</strong><br>
        <em>(A.505)</em><br>
        Managérialisme, culture de performance et santé psychologique : Comment s'inspirer du slow scholarship pour survivre et s'épanouir aux études supérieures?
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
              <strong>Workshop #5</strong><br>
              <em>(C.412)</em><br>
              Ebbs and flows of the doctoral journey
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
      <td><strong>Refreshment</strong> <em>(D.726)</em></td>
    </tr>

    <tr>
      <td><strong>15:30–17:00</strong></td>
      <td>
        <table class="parallel">
          <tr>
            <td>
              <strong>Workshop #6</strong><br>
              <em>(C.505)</em><br>
              Individual and collective resistance strategies of doctoral students to power dynamics at the university, in particular in supervisory relationships
            </td>
            <td>
              <strong>Workshop #7</strong><br>
              <em>(C.515)</em><br>
              Understanding and practicing bibliographic snowballing from open data: methodological principles, tools and limitations
            </td>
            <td>
              <strong>Workshop #8</strong><br>
              <em>(C.551)</em><br>
              Boundless Era: A Collaborative Open Innovation Game
            </td>
          </tr>
        </table>
      </td>
    </tr>

    <tr>
      <td><strong>17:00–17:30</strong></td>
      <td>
        <strong>Closing speeches</strong><br>
        <em>(A.878)</em>
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