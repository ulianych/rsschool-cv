# Ulyana Ihnatchyk
## Contacts:
* e-mail: uliana.ignatchik@gmail.com
## Personal information:
My motto:
> Not all wheels are invented yet.
> - Richard Branson
So I'm always open to the idea of developing both hard and soft skills. I can characterize myself as an ambitious problem solver with a passion for online businesses, and who would like to join a team of like-minded developers. 
### Strength:
* Always positive, regardless of the challenge ahead.
* Good communication and personal-interaction skills.
* Willingness to develop.
* Enthusiastic approach to work.
* Need little time to learn and adaptate.
## Skills:
* HTML
* CSS
* JavaScript
## Code examples:
HTML:
`` ''
<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <title>Blog</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <h1 class="page-title">Beginner front end developper</h1>
    </header>
    <main>
      <div class="avatar-container">
        <img class="avatar" src="img/raccoon.svg" width="80" height="80" alt="Аватарка">
      </div>
      <nav class="blog-navigation">
        <h2>Notes</h2>
        <ul>
          <li><a href="day-1.html">Day one</a></li>
          <li><a href="day-2.html">Day two</a></li>
          <li><a href="day-3.html">Day three</a></li>
          <li><a href="day-4.html">Day four</a></li>
          <li><a href="day-5.html">Day five</a></li>
        </ul>
      </nav>
      <section>
        <h2>Skills</h2>
        <dl class="skills">
          <dt>HTML</dt>
          <dd><div class="skills-level skills-level-ok" style="width: 60%;">60%</div></dd>
          <dt>CSS</dt>
          <dd><div class="skills-level" style="width: 20%;">20%</div></dd>
          <dt>JS</dt>
          <dd><div class="skills-level" style="width: 10%;">10%</div></dd>
        </dl>
      </section>
    </main>
`` ''
CSS:
`` ''
body {
  padding: 0 30px;
  font-size: 16px;
  line-height: 26px;
  font-family: "Arial", sans-serif;
  color: #222222;

  background: #ffffff url("img/bg-page.png") no-repeat top center;
}

h1 {
  font-weight: 400;
  font-size: 24px;
  line-height: normal;
}

h2 {
  font-size: 20px;
  line-height: normal;
}

aside {
  margin: 20px 0;
  color: #c4c4c4;
}
`` ''
JavaScript:
`` ''
function place (coordinate) {
                return Math.floor(Math.random() * coordinate);
            }

            function receiveDistance (event, target) {
                return Math.sqrt((target.x - event.offsetX) * (target.x - event.offsetX) + (target.y - event.offsetY) * (target.y - event.offsetY));
            }

            function editMessage (dist) {
                if (dist < 8 && dist !== null) {
               alert("Клад найден! Количество попыток: " + clicks);
               contin = confirm ("Желаете повторить?");
               
               if (contin === true) {
                   clicks = 0;
                target = {
                "x": place(width),
                "y": place(height)
            }
               }
                }
                if (dist < 10) {
                    return "Ну точно где-то рядом";
                }
                if (dist < 20) {
                    return "Ооочень горячо";
                }
                if (dist < 40) {
                    return "Горячо";
                }
                if (dist < 80) {
                    return "Тепло";
                }
                if (dist < 160) {
                    return "Холодно";
                }
                if (dist < 320) {
                    return "Очень холодно";
                }
                else {
                    return "Холоднее и не придумаешь"
                }
            }

            var height = 600;
            var width = 600;
            var target = {
                "x": place(width),
                "y": place(height)
            }

            var clicks = 0;
            var dist = null;
            var finalMessage = null;
            var contin = null;

            $("#map").click(function (event) {
                clicks++;
                dist = receiveDistance(event, target);
                finalMessage = editMessage(dist);
                $("#message").text(finalMessage);
            })
`` ''
## Work experience
I haven't experienced in working with real projects yet, but I'm always ready.
## Education
I graduated from kindergarten and basic scholl. Now I'm styding in a secondary school. Also I've got education in national children's technopark where I've mastered the robotics course program. There I used to program using C language.
## English
B2