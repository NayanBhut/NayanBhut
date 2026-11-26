# Nayan Bhut

**Senior iOS Engineer** — Swift, SwiftUI, UIKit · CI/CD · developer tooling

[Portfolio](https://nayanbhut.github.io) · [LinkedIn](https://www.linkedin.com/in/nayan-bhut-4318b199) · [Résumé (PDF)](https://nayanbhut.github.io/resume.pdf) · [Shipyard Connect on the Mac App Store](https://apps.apple.com/us/app/shipyard-connect-for-asc/id6820384178?mt=12)

---

I ship iOS apps for retail brands with large catalogues and high traffic. For the last eight years that has meant Swift, UIKit and SwiftUI, careful performance work under Instruments, and release pipelines that make shipping boring.

Currently Senior Software Engineer at **Brainvire Infotech**, leading iOS for **Nike ME**, **Under Armour ME** and **Sun & Sand Sports**.

Outside work I build the developer tools I was missing: a native macOS client for the App Store Connect API, a JSON:API inspector, and mobile clients for Azure Pipelines and Bitrise.

## Experience at a glance

| | |
| :-- | :-- |
| **8+ years** | Swift and Objective-C, in production since 2018 |
| **2.1% → 0.3%** | Nike ME crash rate, through Instruments profiling and defensive coding |
| **60 FPS** | scrolling on catalogues of 1,000+ products |
| **−50%** | deployment time with fastlane and Bitrise pipelines |
| **20+** | production releases for Under Armour ME with no critical post-release bugs |
| **5+** | developers mentored on MVVM, VIPER and review practice |

## Selected work

| Project | What it is | Links |
| :-- | :-- | :-- |
| **Shipyard Connect for ASC** | Native macOS 15+ client for the App Store Connect API: TestFlight builds, release notes across 50 locales with a completeness check, beta groups, customer reviews and team resources. 37 merged pull requests in the public source. | [App Store](https://apps.apple.com/us/app/shipyard-connect-for-asc/id6820384178?mt=12) · [Source](https://github.com/NayanBhut/TestFlightReleaseNotes) |
| **PipelineDeck: CI/CD Monitor** | Azure DevOps client for iPhone and iPad: projects and pipelines, searchable build logs, run control and release approvals. | [App Store](https://apps.apple.com/us/app/pipelinedeck-ci-cd-monitor/id6828979702) |
| **JSON:API Lens** | Browser-based viewer and validator for JSON:API — recursive `included` expansion, 1.1 structural validation, resolved JSON export and a relationship graph. | [Live](https://nayanbhut.github.io/jsonapi-lens/) · [Source](https://github.com/NayanBhut/jsonapi-lens) |
| **Azure Pipeline Mobile** | Unofficial Azure DevOps client for iOS and Android in React Native: project list, pipeline triggering and live build status. | [Source](https://github.com/NayanBhut/Azure-PipeLine-Mobile) |
| **Bitrise Mobile** | Unofficial Bitrise client: multi-workspace app list, build control, custom workflow parameters. | [Source](https://github.com/NayanBhut/Bitrise-Mobile) |
| **Read Along** | Chrome/Brave MV3 extension that reads any page aloud with word-level highlighting and auto-scroll. | [Chrome Web Store](https://chromewebstore.google.com/detail/read-along/daidbadgjkeambnjhaafphcbjcpngf) · [Site](https://nayanbhut.github.io/read-along-site/) |

## Open source contributions

- **open-telemetry/opentelemetry-swift** · [PR #1307](https://github.com/open-telemetry/opentelemetry-swift/pull/1307) (merged) — `fix(URLSession)`: record `error.type` for stable HTTP error responses. Under stable HTTP semantic conventions, 4xx/5xx responses set `error.type` to the string status code and drop the redundant status description, with old-convention behaviour unchanged. Added tests for 200/404/500 and a regression test (+180/−5 across 8 files). Fixes [#1203](https://github.com/open-telemetry/opentelemetry-swift/issues/1203).

## Shipped apps

| App | Role | Store |
| :-- | :-- | :-- |
| Under Armour ME | Lead iOS Developer | [App Store](https://apps.apple.com/ae/app/under-armour-me-shop-online/id1591394964) |
| Nike ME | Senior iOS Developer | [App Store](https://apps.apple.com/ae/app/nike-sportswear-sneakers/id6444790147) |
| Sun & Sand Sports | Senior iOS Developer | [App Store](https://apps.apple.com/us/app/sun-sand-sports-shop-online/id1163601891) |
| PipelineDeck: CI/CD Monitor | iOS Developer | [App Store](https://apps.apple.com/us/app/pipelinedeck-ci-cd-monitor/id6828979702) |
| Medznat · Trophy Cloud · Anco Turf | iOS Developer | [Medznat](https://apps.apple.com/in/app/medznat/id1111506408) · [Trophy Cloud](https://apps.apple.com/us/app/trophy-cloud/id1399027300) · [Anco Turf](https://apps.apple.com/au/app/anco-turf/id1477293063) |

## Toolkit

```text
Language      Swift, Objective-C
UI            SwiftUI, UIKit, AppKit, Catalyst, Auto Layout, SnapKit
Concurrency   async/await, actors, Sendable, @MainActor, strict concurrency checking
Architecture  MVVM, Clean Swift, VIPER
Data          CoreData, SwiftData, CloudKit, SQLite, Keychain
Networking    URLSession, Alamofire, REST, GraphQL, gRPC, JSON:API, WebSockets
Testing       XCTest, XCUITest, TDD, Instruments (Time Profiler, Leaks)
CI/CD         fastlane, Bitrise, GitHub Actions, Azure Pipelines, Jenkins, TestFlight
AI tooling    MCP servers in Swift, Ollama, Claude, Cursor, GitHub Copilot
Infra         Docker, AWS EC2, Oracle Cloud, Unix
```

## Writing

Blog posts and case studies on the portfolio site:

- [JSON:API is not JSON: resolving relationships you cannot see](https://nayanbhut.github.io/blog/jsonapi-is-not-json/)
- [Reviewing a 237k-character PR diff without truncation](https://nayanbhut.github.io/blog/reviewing-a-237k-character-pr-diff/)
- [Shipyard Connect: shipping a Mac App Store tool for App Store Connect](https://nayanbhut.github.io/work/shipyard-connect/)
- [A strict-concurrency and security audit of a SwiftUI app](https://nayanbhut.github.io/open-source/swift6-security-audit/)
- [Reviewing every line of a 237k-character pull request](https://nayanbhut.github.io/open-source/pr-review-chunking/)

[All writing →](https://nayanbhut.github.io/blog/)

## Contact

[nayanbhut989@gmail.com](mailto:nayanbhut989@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nayan-bhut-4318b199) · [nayanbhut.github.io](https://nayanbhut.github.io)

Ahmedabad, India · open to remote and relocation across India
