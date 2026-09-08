<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-light.svg">
  <img alt="Danylo Antypenko — C# / .NET backend developer. Backend systems, developer tools, and audio experiments." src="assets/profile-light.svg" width="100%">
</picture>

I’m a **C# / .NET backend developer** based in Warsaw, with freelance and internship experience building REST APIs, database-backed applications, and third-party integrations. I also work with React and Python.

I study **Computer Science, specializing in Machine Learning, at PJAIT**. My current projects bring together the things I enjoy working on: database behavior, reliable backend systems, and creative tools.

**[LinkedIn](https://www.linkedin.com/in/danylo-antypenko-a83170368/)** · **[Try QueryShape](https://github.com/DanilAntyp/QueryShape)**

### What I’m building

#### [QueryShape](https://github.com/DanilAntyp/QueryShape) · EF Core query regression testing

Tests can pass while database queries do more work as the data grows. QueryShape brings query snapshots, growth checks, and before/after result comparisons into integration tests.

In an eShopOnWeb experiment, the SQL command count stayed at **4** while returned rows grew from **25 to 1,007**. Query count alone missed the growth.

<sub>Synthetic SQLite fixtures running the application’s services; cache excluded. Complete lookup lists can be intentional. This measures returned rows, not production latency.</sub>

[Get started →](https://github.com/DanilAntyp/QueryShape/blob/main/docs/installation.md) · [Read the experiments](https://github.com/DanilAntyp/QueryShape/blob/main/docs/validation/README.md)

#### VEX · Prepaid AI-credit platform

An ASP.NET Core platform for buying credits and spending them on AI chat, image, and video generation. The backend combines an append-only double-entry ledger, integer money accounting, idempotent payment flows, and a provider-independent AI gateway.

Stripe handles checkout; PostgreSQL stores the ledger. Integration tests exercise money-moving flows against a real database.

<sub>C# · ASP.NET Core · EF Core · PostgreSQL · Stripe · Redis · React</sub>

#### UnMix · A local audio studio

A music tool for separating vocals and instruments, converting and trimming audio, and creating karaoke videos with synchronized lyrics. Demucs handles stem separation; Whisper provides word timing and transcription. Audio processing runs on your machine.

I’m developing UnMix in a private repository.

<sub>Python · Demucs · Whisper · FFmpeg</sub>

### More projects

| Project | What I built |
| :--- | :--- |
| **[Triki Arcade](https://github.com/DanilAntyp/Triki-Games)** | Three C# / WPF games with Bluetooth motion controls, keyboard fallback, and motion recording/playback. |
| **[Movie App](https://github.com/DanilAntyp/Movie_app)** | A mobile movie app using TypeScript, React Native, and Expo. |
| **[Retinal Image Classification](https://github.com/DanilAntyp/PRO)** | A Python / PyTorch experiment comparing image classifiers, with evaluation plots and error analysis. |

### Experience & toolkit

**Freelance backend development** — ASP.NET Core and Django APIs, relational schema design, and integrations.<br>
**Vortex Solution** — backend internship working on a Django social-media scheduling application.<br>
**Avista** — backend internship building Python pipelines for internal reporting.

**Backend:** C#, ASP.NET Core, EF Core, LINQ, REST APIs, SignalR<br>
**Data:** PostgreSQL, SQL Server, MySQL, Redis<br>
**Delivery:** Docker, GitHub Actions, xUnit, Google Cloud Run<br>
**Web & experiments:** React, TypeScript, Python, PyTorch

---

Have a query regression worth catching, or an idea for an audio tool? [Connect on LinkedIn](https://www.linkedin.com/in/danylo-antypenko-a83170368/) or [open a QueryShape issue](https://github.com/DanilAntyp/QueryShape/issues).
