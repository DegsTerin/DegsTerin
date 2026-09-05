# Bruno Araújo · DegsTerin

**Full Stack Developer · Backend, databases and applied AI**

[LinkedIn](https://www.linkedin.com/in/brunnaraujo/) · [GitHub projects](https://github.com/DegsTerin?tab=repositories) · [Sponsor my work](https://github.com/sponsors/DegsTerin)

I build applications that connect operational workflows, databases and clear user interfaces. My background in IT operations and server networking shapes how I approach persistence, failure handling and deployment.

My current work centres on **C#/.NET, TypeScript, React and PostgreSQL**, with projects in workforce operations, retrieval-augmented generation and database observability. The examples below link directly to demonstrations, implementation and tests.

## Featured projects

### [Shift-Flow](https://github.com/DegsTerin/Shift-Flow) · Operations management

**TypeScript · Next.js · React · Express · PostgreSQL · Prisma**

A workspace for coordinating shifts, activities, ownership and reporting. Dashboards, Kanban views and audit records connect daily operations with permission-aware administration.

The repository includes company-scoped access rules, transactional user management and automated browser checks. An ASP.NET Core compatibility host explores incremental migration through a separate local runtime profile.

[**Try the demonstration**](https://shift-flow-degsterin.onrender.com/) · [Architecture and setup](https://github.com/DegsTerin/Shift-Flow#architecture) · [Release checks](https://github.com/DegsTerin/Shift-Flow/actions/workflows/release-gates.yml)

*The public demonstration uses Next.js, Express and PostgreSQL with synthetic data and a restricted shared account.*

<details>
<summary>Preview the product walkthrough</summary>

![Shift-Flow walkthrough showing the operations dashboard and activity views with synthetic data.](https://raw.githubusercontent.com/DegsTerin/Shift-Flow/main/docs/assets/shift-flow-demo.gif)

</details>

### [RAG-Challenge](https://github.com/DegsTerin/RAG-Challenge) · Answers grounded in documentation

**C# · ASP.NET Core · React · TypeScript · SQLite · OpenAI**

A documentation assistant that retrieves evidence, produces answers with page-level citations and returns an explicit insufficient-evidence outcome when the eligible sources cannot support an answer.

The implementation brings together immutable index generations, source provenance, citation validation and bounded provider access. The public demonstration queries PostgreSQL documentation in English or Portuguese.

[**Try the demonstration**](https://rag-challenge-ac09.onrender.com/) · [Architecture and setup](https://github.com/DegsTerin/RAG-Challenge#architecture-and-technology) · [CI checks](https://github.com/DegsTerin/RAG-Challenge/actions/workflows/ci.yml)

*The public interface is query-only. Its current corpus and operating limits are documented in the repository.*

<details>
<summary>Preview a grounded answer and its citations</summary>

![RAG-Challenge showing a PostgreSQL answer, evaluated source coverage and page-level citations.](https://raw.githubusercontent.com/DegsTerin/RAG-Challenge/main/docs/assets/demo/rag-challenge-grounded-answer-en-gb.png)

</details>

### [DB-Notifier](https://github.com/DegsTerin/DB-Notifier) · Database observability

**C# · .NET · WPF · React · TypeScript · SQLite · PostgreSQL**

An evolving database observability project with a Windows desktop application, provider adapters and a Web dashboard. It builds on the operational problem explored in my earlier PG-Notifier utility.

The code explores authenticated PostgreSQL probes, durable observation delivery and recovery after interruptions, with focused tests for atomic persistence and concurrent writes.

[**Explore the dashboard preview**](https://db-notifier-demo.onrender.com/) · [Architecture and current scope](https://github.com/DegsTerin/DB-Notifier#readme) · [Source and tests](https://github.com/DegsTerin/DB-Notifier/tree/main/tests)

*The hosted dashboard uses synthetic data. Provider support and end-to-end operational validation remain under development.*

<details>
<summary>Preview the synthetic dashboard</summary>

![DB-Notifier dashboard preview displaying synthetic database observations and status information.](https://raw.githubusercontent.com/DegsTerin/DB-Notifier/main/docs/assets/db-notifier-demo.png)

</details>

## Engineering in the code

| Area | Concrete example |
| --- | --- |
| **Backend and data integrity** | [Shift-Flow's PostgreSQL regression tests](https://github.com/DegsTerin/Shift-Flow/blob/main/prisma/users-tenant-isolation.postgres.test.mjs) exercise company isolation, aggregate transactions and concurrent changes. |
| **Applied AI and retrieval** | [RAG-Challenge's answer-policy tests](https://github.com/DegsTerin/RAG-Challenge/blob/main/tests/RagChallenge.UnitTests/QuestionAnsweringServiceTests.cs) cover insufficient evidence, unsupported citations and bilingual responses. |
| **Persistence and failure handling** | [DB-Notifier's observation-outbox tests](https://github.com/DegsTerin/DB-Notifier/blob/main/tests/DBNotifier.UnitTests/AgentObservationOutboxTests.cs) exercise atomic SQLite writes, ordering and concurrent persistence. |
| **Frontend and user journeys** | [Shift-Flow's browser tests](https://github.com/DegsTerin/Shift-Flow/blob/main/tests/e2e/state07-homologation.spec.ts) cover sign-in, session restoration, dashboard metrics, themes and mobile navigation. |
| **Delivery and automation** | [Shift-Flow's release workflow](https://github.com/DegsTerin/Shift-Flow/blob/main/.github/workflows/release-gates.yml) combines Node.js and .NET checks with disposable PostgreSQL and browser validation. |

## More work

| Project | What it explores |
| --- | --- |
| [Maths-Quiz-Game](https://github.com/DegsTerin/Maths-Quiz-Game) | An Arduino maths game and a browser edition: embedded C++, display constraints and a testable JavaScript game engine. |
| [PG-Notifier](https://github.com/DegsTerin/PG-Notifier) | PostgreSQL monitoring from the Windows tray, with PowerShell health checks, restart detection and [packaged releases](https://github.com/DegsTerin/PG-Notifier/releases). |
| [Interactive-Data-Analytics](https://github.com/DegsTerin/Interactive-Data-Analytics) | IT salary exploration with Python, Pandas, Streamlit and Plotly. |
| [Theotimus](https://github.com/DegsTerin/Theotimus) | A bilingual e-commerce project exploring Node.js, Express, PostgreSQL and Stripe checkout integration. |

[Browse all public projects →](https://github.com/DegsTerin?tab=repositories)

<details>
<summary>GitHub activity</summary>

<p>
  <img width="98%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=DegsTerin&amp;theme=dracula" alt="GitHub contribution activity for DegsTerin" />
</p>
<p>
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=DegsTerin&amp;theme=dracula" alt="GitHub repository statistics for DegsTerin" />
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=DegsTerin&amp;theme=dracula" alt="Languages across DegsTerin's public repositories" />
</p>

</details>

---

Interested in backend development, database tooling or applied AI? [Connect with me on LinkedIn](https://www.linkedin.com/in/brunnaraujo/).
