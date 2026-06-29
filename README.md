<h3 align="center">👋 WELCOME TO MY GITHUB PROFILE!
</h3>

---

<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=500&color=58AAC4&center=true&vCenter=true&repeat=false&width=600&height=45&lines=Anastasia+Belova+%7C+QA+Automation+Engineer" alt="Typing SVG" /></a>
</p>
<p align="center">
<img src="https://shields.io/badge/Automation_progress-60%25-blue" width="165" height=20>
  <img src="https://shields.io/badge/Manual_progress-100%25-violet" width="150" height=20>
</p>  

<h6 aligh=left>Нi! I'm a junior QA Automation engineer and a certified manual testing specialist. My main goal is to develop my automation skills (API/Backend & UI). I'm currently actively exploring automation tools and creating functional pet projects to test my skills.<br>This portfolio proves my transition into QA Automation (JavaScript/ Postman/ Newman etc.) demonstrating that I don't just follow test scripts, but understand architecture, backend logic, performance constraints, and security risks.
</h6>

## <p align="center">🧠 my tech stack</p> 
**api testing** &nbsp; <img src="https://img.shields.io/badge/-Postman-282C34?style=plastic&logo=postman&logoColor=FF6C37"/>  <img src="https://img.shields.io/badge/-DevTools-282C34?style=plastic&logo=googlechrome&logoColor=4285F4"/> <img src="https://img.shields.io/badge/-OpenAPI-282C34?style=plastic&logo=openapiinitiative&logoColor=6BA539"/>  <img src="https://img.shields.io/badge/-Swagger-282C34?style=plastic&logo=swagger&logoColor=85EA2D"/> <img src="https://img.shields.io/badge/-CharlesProxy-282C34?style=plastic&logo=charles&logoColor=F3F5F5"/>

**web & lang** &nbsp; <img src="https://img.shields.io/badge/-Python-282C34?style=plastic&logo=python&logoColor=3776AB"/> <img src="https://img.shields.io/badge/-JavaScript-282C34?style=plastic&logo=javascript&logoColor=F7DF1E"/> <img src="https://img.shields.io/badge/-HTML5-282C34?style=plastic&logo=HTML5&logoColor=E34F26"/> <img src="https://img.shields.io/badge/-Json-282C34?style=plastic&logo=json&logoColor=FFFFFF"/> <img src="https://img.shields.io/badge/-CSS3-282C34?style=plastic&logo=CSS3&logoColor=1572B6"/>


**automation** &nbsp; <img src="https://img.shields.io/badge/-Selenium-282C34?style=plastic&logo=selenium&logoColor=43B02A"/> <img src="https://img.shields.io/badge/-NPM-282C34?style=plastic&logo=NPM&logoColor=CB3837"/> <img src="https://img.shields.io/badge/-Node.js-282C34?style=plastic&logo=nodedotjs&logoColor=5FA04E"/> 


**management** &nbsp; <img src="https://img.shields.io/badge/-Jira-282C34?style=plastic&logo=jira&logoColor=0052CC"/> <img src="https://img.shields.io/badge/-TestRail-282C34?style=plastic&logo=testRail&logoColor=#65C179"/> <img src="https://img.shields.io/badge/-Confluence-282C34?style=plastic&logo=confluence&logoColor=00599C"/> <img src="https://img.shields.io/badge/-Figma-282C34?style=plastic&logo=figma&logoColor=F24E1E"/>


**ci/cd & os** &nbsp; <img src="https://img.shields.io/badge/-AndroidStudio-282C34?style=plastic&logo=androidstudio&logoColor=3DDC84"/>
 <img src="https://img.shields.io/badge/-Jenkins-282C34?style=plastic&logo=jenkins&logoColor=D24939"/> <img src="https://img.shields.io/badge/-Bash-282C34?style=plastic&logo=gnubash&logoColor=4EAA25"/> 

**ide & git** &nbsp; <img src="https://img.shields.io/badge/-PyCharm-282C34?style=plastic&logo=pycharm&logoColor=FF0007"/> <img src="https://img.shields.io/badge/-Github-282C34?style=plastic&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/-Git-282C34?style=plastic&logo=Git&logoColor=F44D27"/>  <img src="https://img.shields.io/badge/-VS%20Code-282C34?style=plastic&logo=Visual%20Studio%20Code&logoColor=white"/>


**security** &nbsp; <img src="https://img.shields.io/badge/-KaliLinux-282C34?style=plastic&logo=kalilinux&logoColor=FFFFFF"/> 
<img src="https://img.shields.io/badge/-BurpSuite-282C34?style=plastic&logo=burpsuite&logoColor=FF6633"/> <img src="https://img.shields.io/badge/-Wireshark-282C34?style=plastic&logo=wireshark&logoColor=1679A7"/>

**databases** &nbsp; <img src="https://img.shields.io/badge/-PostgreSql-282C34?style=plastic&logo=postgresql&logoColor=4169E1"/> <img src="https://img.shields.io/badge/-Mysql-282C34?style=plastic&logo=mysql&logoColor=F68315"/>


## <p align="center">🛡️ software testing rojects<p>

### 🌀 Project 1: [API Automation Framework: Security Audit, Stress & Logic | Oort Depot](https://github.com)
<h6>Комплексная система автоматизированного тестирования для крупного бэкенд-приложения (Система управления складом).</h6>
<details>
<summary><b>⚡️ core architecture & advanced scripting scope</b></summary>
<br>
  
*   **Архитектура фреймворка:** Полный **Zero Hardcode** (динамический подхват и передача токенов и ID по всей цепочке запросов). Интегрирован Postman Mock Server для симуляции внешних интеграций.
*   **QA Security Audit:** Внедрена автоматизированная проверка критических уязвимостей на основе стандартов OWASP Top 10 (включая BOLA, SQLi, Broken Authentication etc.). По результатам аудита сформирован Security Verdict и заведены дефекты в Jira.
*   **Инфраструктурные тесты:** Нагрузка сервера до точки отказа (`ECONNRESET`) через параллельный CLI-запуск.
*   **BDD подход (Gherkin):** Сценарии написаны как исполняемые спецификации (`Given / When / Then`), что делает их прозрачными для бизнеса и готовыми к миграции на Cucumber/SpecFlow.
*   **Smart Scripting:** Циклы `forEach` на JavaScript для глубокой проверки массивов данных и валидации JSON-схем (Contract Testing на соответствие Swagger).
*   **Reporting:** Генерация кастомных HTML-дашбордов с глубокой аналитикой через htmlextra.
*   **CI/CD Ready:** Полная автономность коллекции для запуска в пайплайнах.
*   🔗 **Перейти к проекту:** [api-automation-oort-depot](https://github.com)
</details>


### 🌐 Project 2: [UI Manual QA Suite: Registration Service | Globbing Shopping Solutions](https://github.com)
<h6>Ручное тестирование функционала сервиса регистрации в рамках программы по повышению квалификации "Специалист по тестированию ПО" (ТГУ).</h6>
<details>
<summary><b>📋 core qa scope & testing artifacts</b></summary>
<br>

*   **Что внутри:** Разработаны: чек-лист, тест-кейсы, заведены баг-репорты. В заключении составлен отчет о результатах тестирования (Test Summary Report).
*   **Дополнение:** Защита итоговой проектной работы в формате скрин-каста (.mp4)
*   🔗 **Перейти к проекту:** [ui-manual-qa-globbing](https://github.com)
</details>

### 🕵️‍♂️ Cybersecurity Lab: [Web-pentest: Penetration Testing | White Hat](https://github.com)
<h6>Комплексный аудит безопасности веб-ресурсов и симуляция целевых атак по методологии OWASP Top 10.</h6>
<details>
<summary><b>🔓 security audit & vulnerability analysis</b></summary>
<br>
  
*   **Что внутри:** Выполнены лабораторные работы, составлены отчеты по исследованию уязвимостей веб-приложений (OWASP Top 10) и тестам на проникновение в рамках профильного обучения (SkillFactory).
*   🔗 **Перейти в репозиторий:** [web-pentest-cybersecurity-labs](https://github.com)
</details>

### 🗄️ Databases:  [SQL Practice: Interactive SQL Simulator | SQL Academy](https://github.com)
<h6>Скрипты со сложными SQL-запросами, демонстрирующие навыки работы с реляционными БД.</h6>
<details>
<summary><b>🗄️ database manipulation & complex query logic</b></summary>
<br>
  
*   **Что внутри:** Решение комплексных задач на специализированных тренажерах (работа со срезами данных, математические агрегации, многотабличные `JOIN` операции, вложенные запросы).
*   *   🔗 **Перейти в репозиторий:** [sql-simulator-practice](https://github.com)
</details>

## 📫 Как со мной связаться
*   **Telegram:** [@C]
*   **Email:** [bel.test.qa@gmail.com]
*   **LinkedIn:** [(https://www.linkedin.com/in/anastasia-belova-aqa/)]
telegram













---

