### Ibrahim Mansour — Flutter Developer

📍 Cairo, Egypt

I build and ship cross-platform mobile apps with Flutter — 25+ apps for 13+ clients across fintech, delivery, travel, retail and education. On most of them I was the primary developer, owning the app end to end: architecture, implementation, test strategy and release automation.

#### 📱 Shipped

[Money Basket Exchange](https://play.google.com/store/apps/details?id=com.mis.mbex) — remittance and FX for a Kuwait-licensed exchange house, 10K+ installs

[Tayara](https://play.google.com/store/apps/details?id=com.ibrahim.tayara) — three-role food delivery platform

**Onvaca** — 15-module travel and rental booking platform, pre-launch

#### 🏗️ Selected client work

Most of what I ship lives in private repositories. A sample of what I built and the decisions behind it:

**Al Malek Exchange** — money transfer and FX for a Kuwait-licensed exchange house. Feature-first clean architecture across seven modules — authentication, send money, beneficiary management, live transfer rates, transaction history, user profile — each with its own data, domain and presentation layers so features stay independently testable. Firebase backend, full Arabic/English localization with generated ARB and RTL support.

**Market** — two-sided marketplace with separate client and worker experiences sharing one codebase. Real-time chat, push notifications, Cloud Functions for server-side logic, and Firestore security rules written to enforce role boundaries at the data layer rather than in the UI.

**POS** — point-of-sale app for retail, built end to end. A shared `core` layer carrying its own dependency-injection container, networking and typed error handling, with seven feature modules composed on top: authentication, home, cart, navigation shell, settings, splash and welcome.

**Murafiq** — multi-role logistics app split into shared internal packages, so customer and driver builds reuse one domain layer instead of diverging.

**Greenz** — grocery delivery as three coordinated apps: customer ordering, driver dispatch and store pickup, sharing a common domain model across the fleet.

**Stanford-Binet** — digital administration and scoring for a psychological assessment battery. Session flow, child records and automated report generation, on the same clean-architecture structure.

**Nibni** — construction management app built on a documented in-house design system, so screens compose from shared primitives instead of one-off widgets.

#### 🧪 Engineering practice

Unit and widget tests with `flutter_test`, end-to-end flows with Maestro and Patrol, release automation with Fastlane and GitHub Actions — tagged builds straight to TestFlight and Play internal tracks.

#### 🛠️ Stack

Flutter · Dart · BLoC / Cubit · Riverpod · Clean Architecture · GraphQL · REST · Firebase · Supabase · Drift · Hive · Fastlane · GitHub Actions

#### 🔗 Links

[Portfolio](https://ibrahimmansour1.github.io/Portfolio/) · [LinkedIn](https://www.linkedin.com/in/ibrahim-mansour-52146b171/)
