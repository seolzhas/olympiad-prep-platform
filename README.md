# Olympiad Prep Platform

A free, open source platform that helps students aged 13–18 from low-income families in Kazakhstan prepare for mathematics olympiads.

Many talented students cannot pay for tutors or books, use old phones and have slow internet. This platform gives them structured olympiad preparation at no cost: no ads, no paid access, ever.

> Status: early stage (MVP). This repository is part of a student project at KBTU.

## Features (MVP)

1. **Sign-up / sign-in** — minimal profile, no unnecessary personal data.
2. **Theory modules** — core olympiad topics (number theory, algebra, geometry, combinatorics) explained step by step.
3. **Short videos** — one per theory module.
4. **Practice problems** — tasks on the material just covered, with step-by-step solutions.

Planned: Russian and Kazakh interface, light pages that work on weak internet and old phones.

## Who it is for

| User | What they get |
| --- | --- |
| Students 13–18 | Free theory, videos and practice |
| Teachers and volunteers | Ready materials to use in class or clubs |
| Contributors | A friendly project to improve code and content |

## Tech stack

The platform is built only on open, platform-independent technologies:

- Web app (Progressive Web App): HTML, CSS, JavaScript / React — runs in any modern browser on Android, iOS, Windows, macOS or Linux.
- Database: PostgreSQL (open source).
- Content: Markdown files, so lessons can be edited without special software.
- Hosting: any standard server or cloud; no vendor lock-in.

## Getting started (for users)

Open the website in any browser, create an account and start with the first module. You can install it on your phone's home screen ("Add to Home Screen").

## Getting started (for developers)

```bash
git clone https://github.com/<your-username>/olympiad-prep-platform.git
cd olympiad-prep-platform
```

The MVP code is in progress. Setup commands (install, run, test) will be added here with the first code release. Until then you can already contribute lessons and problems in the `content/` folder.

## Contributing

We welcome code, new problems, translations and bug reports. Read [CONTRIBUTING.md](CONTRIBUTING.md) first. Everyone must follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Privacy

We collect as little data as possible and never sell it or show ads. See [PRIVACY.md](PRIVACY.md).

## License

- Code: [MIT License](LICENSE)
- Educational content (theory, problems, videos): [CC BY-SA 4.0](LICENSE-CONTENT.md)

## Ownership and maintainers

This project is owned and maintained by its student team:

- Olzhas Sengaliyev — business, finance, project coordination
- Dmitriy Cherepkov — research and product

Copyright © 2026 the Olympiad Prep Platform team. Contact: open an issue in this repository.

## Supported goals

This project contributes to UN Sustainable Development Goal 4 (Quality Education) and Goal 10 (Reduced Inequalities).
