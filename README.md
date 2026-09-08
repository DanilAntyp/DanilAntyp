<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Hi, I’m Danil. Software developer building open-source tools, web apps, and experiments." src="assets/header-light.svg" width="100%">
</picture>

I build developer tools and applications with **C# / .NET**, **React / TypeScript**, and **Python**. My projects range from database testing to mobile apps and motion-controlled games.

**Currently building [QueryShape](https://github.com/DanilAntyp/QueryShape)** — making EF Core query behavior something you can test.

### QueryShape

Tests can pass while database queries do more work as the data grows. QueryShape brings query snapshots, growth checks, and before/after result comparisons into integration tests.

One experiment with eShopOnWeb kept the SQL command count at **4**, while returned rows grew from **25 to 1,007**. Query count alone missed the growth.

<sub>Synthetic SQLite fixtures running the application’s services; cache excluded. Complete lookup lists can be intentional. This measures returned rows, not production latency.</sub>

**[Explore the project →](https://github.com/DanilAntyp/QueryShape)** · [Try the source preview](https://github.com/DanilAntyp/QueryShape/blob/main/docs/installation.md) · [Read the experiments](https://github.com/DanilAntyp/QueryShape/blob/main/docs/validation/README.md)

### Selected projects

| Project | What’s inside | Built with |
| :--- | :--- | :--- |
| **[Triki Arcade](https://github.com/DanilAntyp/Triki-Games)** | Three desktop games with a Bluetooth motion controller, keyboard fallback, and motion recording/playback. | C# · .NET · WPF |
| **[Movie App](https://github.com/DanilAntyp/Movie_app)** | A mobile movie app built with Expo and React Native. | TypeScript · React Native · Expo |
| **[Vero.nikadent](https://github.com/DanilAntyp/veronikadent)** | A website for a children’s and family dental practice. | React · JavaScript · Vite |
| **[Retinal Image Classification](https://github.com/DanilAntyp/PRO)** | A machine-learning experiment comparing image classifiers, with evaluation plots and error analysis. | Python · PyTorch |

### What I work with

**Backend & testing** — C#, .NET, EF Core, SQL, integration tests, GitHub Actions  
**Web & mobile** — React, TypeScript, JavaScript, React Native, Expo  
**Experiments** — Python, PyTorch, Bluetooth LE

---

Found something useful? Try a project and tell me what worked—or what broke. [QueryShape feedback and ideas →](https://github.com/DanilAntyp/QueryShape/issues)
