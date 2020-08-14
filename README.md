# covid19_ua

### Відкриті дані по захворюваності на COVID-19  в Україні.

##### Первинні дані отримані від Центру громадського здоров'я.
##### Трансформовані та агреговані Національною службою здоров'я України.

**Візуалізацію на основі цих даних можна переглянути тут:** https://nszu.gov.ua/covid/dashboard

**Пряме посилання на  версію для смартфону**📱 - https://cutt.ly/COVID19_mobile
  
---
+ **covid19_by_settlement_actual** -  актуальна інформація про всі випадки в розрізі  областей, районів та населених пунктів (за місцем реєстрації випадку).

+ **covid19_by_settlement_dynamics** - поденна динаміка випадків в розрізі  областей, районів та населених пунктів (за місцем реєстрації  випадку).

+ **covid19_by_area_type_hosp_dynamics** - поденна динаміка випадків в розрізі областей, госпіталізації/самоізоляції, віку та статі (за областю реєстрації та госпіталізації).

* Важливо! 
  * Інформація в розрізі днів агрегується безпосередньо по даті реєстрації підозр, даті  тестування/одужання/смерті та не  залежить від дати, коли ці дані було оприлюднено. В разі отримання нових додаткових відомостей або уточнень за попередні періоди, розподіл всіх показників актуалізується автоматично (**оновлюється ретроспективно**).
  * Для випадків госпіталізації/самоізоляції (covid19_by_area_type_hosp_dynamics) дані наведено за місцем реєстрації та додатково за місцем госпіталізації. Розподіл випадків за областю реєстрації або госпіталізації може не співпадати, оскільки є випадки госпіталізації в ЗОЗ в межах іншої області. (ЦГЗ щоденно звітує за місцем реєстрації випадку).Якщо аналізувати дані в розрізі окремих місць госпіталізації (ЗОЗ або самоізоляції), то показник "Виявлено" може бути відмінним від суми "Хворіє" + "Летальні" + "Одужали". Це пов'язано з тим, що протягом лікування пацієнт може із ЗОЗ переходити на самоізоляцію та навпаки.На загальному рівні (області або країни) показник "Виявлено" = "Хворіє" + "Летальні" + "Одужали" у випадку розподілу за областями (область реєстрації).
  
   --- 
  **Код для вбудовування візуалізації на сайті/порталі:**
  ```javascript 
  <iframe width="1280" height="760" src="https://app.powerbi.com/view?r=eyJrIjoiN2M1MTY1MDktZTY5Mi00OTE0LWFiMDAtMjM4NTY0YWU2MmI3IiwidCI6IjI4OGJmYmNmLTVhYjItNDk2MS04YTM5LTg2MDYxYWFhY2Q4NiIsImMiOjl9&amp;fbclid=IwAR3vOXvEK0l3SaGSAxZGgNyc4cNSi17wegJwcFX4oPefbVgUR16RsWDxGjg" frameborder="0" allowfullscreen="true"></iframe>

