## Hello!
I'm Jonathan, a computer science student enrolled at the University of North Florida.

I'm focused on building clean, efficient and reliable backend systems using **Java, Spring Boot, and PostgreSQL.** I enjoy architecture design, structuring API data flows, and deploying scalable services to the cloud.

### [brewed](https://github.com/mrfunkey/brewed)
A full-stack blog platform for long-form album reviews, styled around a "crate-digging" browsing experience.                           
* **Backend:** Spring Boot REST API with Spring Security session-based auth, BCrypt password hashing, and a PostgreSQL/Hibernate data layer for posts and author profiles.
* **Frontend:** Plain JavaScript and CSS, no framework, communicating with the API entirely through `fetch`.                               
* **Auth:** Full account system; signup, login, and session persistence, with post authorship derived server-side from the logged-in user rather than trusted from the client.

### [Visualify](https://github.com/mrfunkey/Visualify)
A full-stack web app that turns Spotify listening history into a personalized generative art piece.
* Backend: Spring Boot REST API secured with Spotify OAuth2, pulling and analyzing a user's top tracks.
* AI: Gemini API integration to classify each track's mood (valence/arousal) from song metadata, using structured, JSON-constrained prompting.
* Rendering: Custom Java2D engine mapping mood scores to procedurally generated gradients and vector shapes, rendered as unique "mood mandalas.
                                 
### [CoverCollector](https://github.com/mrfunkey/CoverCollector-API)
A simple web app for finding and downloading high-quality album cover art.
* **Backend:** Spring Boot app that fetches data from an external API and strips out unneeded information.
* **Frontend:** Clean layout built with plain JavaScript and CSS Grid.
* **Hosting:** Deployed to a live server using AWS Elastic Beanstalk.

### Mock Banking Application
A financial application built with a team to act like a real bank database.
* **Stack:** Core Java, JDBC, PostgreSQL.
* **Features:** Handles user login, manages balances for multiple accounts, tracks deposits and withdrawals, and logs transactions.
