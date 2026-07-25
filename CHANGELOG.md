# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.0](https://github.com/sillytortoises/shreddit/compare/v1.1.8...v1.2.0) - 2026-07-25

### Added

- support relative timestamps in --after filters
- add `--after` flag ([#90](https://github.com/sillytortoises/shreddit/pull/90))
- support relative datetime notation for --before flag ([#141](https://github.com/sillytortoises/shreddit/pull/141))
- add `only-subreddits` option ([#144](https://github.com/sillytortoises/shreddit/pull/144))

### Fixed

- handle error ([#271](https://github.com/sillytortoises/shreddit/pull/271))
- test ([#237](https://github.com/sillytortoises/shreddit/pull/237))
- fix compilation due to breaking types ([#236](https://github.com/sillytortoises/shreddit/pull/236))
- use oauth for listing posts/comments ([#235](https://github.com/sillytortoises/shreddit/pull/235))
- use consistent sorting to ensure all comments captured ([#180](https://github.com/sillytortoises/shreddit/pull/180))
- make --before filter optional
- make --after filter optional
- reddit link
- lint
- lint
- fix
- fix
- fix workflow
- fix version
- fix workflow
- fix workflow
- fix release-plz workflow
- fix mac-latest target

### Other

- bump clap from 4.5.54 to 4.5.57 ([#268](https://github.com/sillytortoises/shreddit/pull/268))
- bump jiff from 0.2.18 to 0.2.19 ([#269](https://github.com/sillytortoises/shreddit/pull/269))
- release v1.1.8 ([#267](https://github.com/sillytortoises/shreddit/pull/267))
- bump serde_json from 1.0.145 to 1.0.149 ([#261](https://github.com/sillytortoises/shreddit/pull/261))
- bump tokio from 1.48.0 to 1.49.0 ([#262](https://github.com/sillytortoises/shreddit/pull/262))
- bump clap from 4.5.53 to 4.5.54 ([#264](https://github.com/sillytortoises/shreddit/pull/264))
- bump reqwest from 0.12.26 to 0.12.28 ([#263](https://github.com/sillytortoises/shreddit/pull/263))
- bump jiff from 0.2.16 to 0.2.18 ([#265](https://github.com/sillytortoises/shreddit/pull/265))
- bump bytes from 1.10.1 to 1.11.1 ([#266](https://github.com/sillytortoises/shreddit/pull/266))
- release v1.1.7 ([#260](https://github.com/sillytortoises/shreddit/pull/260))
- compile for macOS arm64 ([#248](https://github.com/sillytortoises/shreddit/pull/248))
- release v1.1.6 ([#255](https://github.com/sillytortoises/shreddit/pull/255))
- bump actions/checkout from 5 to 6 ([#252](https://github.com/sillytortoises/shreddit/pull/252))
- bump jiff from 0.2.15 to 0.2.16 ([#247](https://github.com/sillytortoises/shreddit/pull/247))
- bump parse_datetime from 0.13.1 to 0.13.3 ([#251](https://github.com/sillytortoises/shreddit/pull/251))
- bump tracing-subscriber from 0.3.20 to 0.3.22 ([#253](https://github.com/sillytortoises/shreddit/pull/253))
- bump actions/cache from 4 to 5 ([#257](https://github.com/sillytortoises/shreddit/pull/257))
- bump reqwest from 0.12.24 to 0.12.26 ([#258](https://github.com/sillytortoises/shreddit/pull/258))
- bump tracing from 0.1.43 to 0.1.44 ([#259](https://github.com/sillytortoises/shreddit/pull/259))
- bump clap from 4.5.49 to 4.5.53 ([#250](https://github.com/sillytortoises/shreddit/pull/250))
- bump tracing from 0.1.41 to 0.1.43 ([#254](https://github.com/sillytortoises/shreddit/pull/254))
- release v1.1.5 ([#242](https://github.com/sillytortoises/shreddit/pull/242))
- Change default branch from 'master' to 'main'
- bump csv from 1.3.1 to 1.4.0 ([#241](https://github.com/sillytortoises/shreddit/pull/241))
- remove unused
- release v1.1.4 ([#238](https://github.com/sillytortoises/shreddit/pull/238))
- release v1.1.3 ([#224](https://github.com/sillytortoises/shreddit/pull/224))
- bump serde from 1.0.223 to 1.0.228 ([#229](https://github.com/sillytortoises/shreddit/pull/229))
- bump clap from 4.5.47 to 4.5.49 ([#232](https://github.com/sillytortoises/shreddit/pull/232))
- bump parse_datetime from 0.11.0 to 0.13.1 ([#231](https://github.com/sillytortoises/shreddit/pull/231))
- bump reqwest from 0.12.23 to 0.12.24 ([#233](https://github.com/sillytortoises/shreddit/pull/233))
- bump tokio from 1.47.1 to 1.48.0 ([#234](https://github.com/sillytortoises/shreddit/pull/234))
- bump serde_json from 1.0.143 to 1.0.145 ([#221](https://github.com/sillytortoises/shreddit/pull/221))
- release v1.1.2 ([#184](https://github.com/sillytortoises/shreddit/pull/184))
- bump amannn/action-semantic-pull-request from 5 to 6 ([#211](https://github.com/sillytortoises/shreddit/pull/211))
- bump async-trait from 0.1.88 to 0.1.89 ([#210](https://github.com/sillytortoises/shreddit/pull/210))
- bump serde_json from 1.0.142 to 1.0.143 ([#213](https://github.com/sillytortoises/shreddit/pull/213))
- bump clap from 4.5.44 to 4.5.47 ([#217](https://github.com/sillytortoises/shreddit/pull/217))
- bump actions/checkout from 4 to 5 ([#212](https://github.com/sillytortoises/shreddit/pull/212))
- bump chrono from 0.4.41 to 0.4.42 ([#218](https://github.com/sillytortoises/shreddit/pull/218))
- bump tracing-subscriber from 0.3.19 to 0.3.20 ([#216](https://github.com/sillytortoises/shreddit/pull/216))
- bump reqwest from 0.12.22 to 0.12.23 ([#208](https://github.com/sillytortoises/shreddit/pull/208))
- bump parse_datetime from 0.9.0 to 0.11.0 ([#205](https://github.com/sillytortoises/shreddit/pull/205))
- bump serde_json from 1.0.140 to 1.0.142 ([#203](https://github.com/sillytortoises/shreddit/pull/203))
- bump clap from 4.5.43 to 4.5.44 ([#207](https://github.com/sillytortoises/shreddit/pull/207))
- bump clap from 4.5.37 to 4.5.43 ([#206](https://github.com/sillytortoises/shreddit/pull/206))
- bump tokio from 1.45.0 to 1.47.1 ([#204](https://github.com/sillytortoises/shreddit/pull/204))
- bump reqwest from 0.12.15 to 0.12.22 ([#196](https://github.com/sillytortoises/shreddit/pull/196))
- bump tokio from 1.44.2 to 1.45.0 ([#183](https://github.com/sillytortoises/shreddit/pull/183))
- release v1.1.1 ([#161](https://github.com/sillytortoises/shreddit/pull/161))
- Update usage output to document valid arguments ([#179](https://github.com/sillytortoises/shreddit/pull/179))
- bump chrono from 0.4.40 to 0.4.41 ([#182](https://github.com/sillytortoises/shreddit/pull/182))
- bump parse_datetime from 0.8.0 to 0.9.0 ([#181](https://github.com/sillytortoises/shreddit/pull/181))
- bump tokio from 1.44.1 to 1.44.2 ([#173](https://github.com/sillytortoises/shreddit/pull/173))
- bump clap from 4.5.36 to 4.5.37 ([#177](https://github.com/sillytortoises/shreddit/pull/177))
- bump clap from 4.5.33 to 4.5.36 ([#174](https://github.com/sillytortoises/shreddit/pull/174))
- bump clap from 4.5.32 to 4.5.33 ([#170](https://github.com/sillytortoises/shreddit/pull/170))
- bump reqwest from 0.12.14 to 0.12.15 ([#168](https://github.com/sillytortoises/shreddit/pull/168))
- bump async-trait from 0.1.87 to 0.1.88 ([#167](https://github.com/sillytortoises/shreddit/pull/167))
- bump reqwest from 0.12.13 to 0.12.14 ([#165](https://github.com/sillytortoises/shreddit/pull/165))
- bump tokio from 1.44.0 to 1.44.1 ([#166](https://github.com/sillytortoises/shreddit/pull/166))
- bump reqwest from 0.12.12 to 0.12.13 ([#164](https://github.com/sillytortoises/shreddit/pull/164))
- bump clap from 4.5.31 to 4.5.32
- bump serde from 1.0.218 to 1.0.219 ([#160](https://github.com/sillytortoises/shreddit/pull/160))
- release v1.1.0 ([#159](https://github.com/sillytortoises/shreddit/pull/159))
- update doc comment for relative timestamps
- rename variable
- release v1.0.2 ([#158](https://github.com/sillytortoises/shreddit/pull/158))
- Revert "ci: allow workflow_dispatch trigger for release"
- release v1.0.1 ([#157](https://github.com/sillytortoises/shreddit/pull/157))
- allow workflow_dispatch trigger for release
- use bash for windows release
- update checks workflow
- release 1.0 ([#156](https://github.com/sillytortoises/shreddit/pull/156))
- fix
- bump edition
- Update checks.yml
- lock
- Update Cargo.toml
- release v0.10.0 ([#154](https://github.com/sillytortoises/shreddit/pull/154))
- add workflow dispatch
- fmt
- bump actions/checkout from 2 to 4 ([#148](https://github.com/sillytortoises/shreddit/pull/148))
- bump async-trait from 0.1.86 to 0.1.87 ([#149](https://github.com/sillytortoises/shreddit/pull/149))
- bump tokio from 1.43.0 to 1.44.0 ([#150](https://github.com/sillytortoises/shreddit/pull/150))
- bump serde_json from 1.0.139 to 1.0.140 ([#151](https://github.com/sillytortoises/shreddit/pull/151))
- test
- lints
- lint PR titles
- dependabot
- use pull_request_target
- CI
- CI
- Bump ring from 0.17.8 to 0.17.13 ([#146](https://github.com/sillytortoises/shreddit/pull/146))
- Bump chrono from 0.4.39 to 0.4.40 ([#142](https://github.com/sillytortoises/shreddit/pull/142))
- Bump clap from 4.5.30 to 4.5.31 ([#143](https://github.com/sillytortoises/shreddit/pull/143))
- Bump serde from 1.0.217 to 1.0.218 ([#139](https://github.com/sillytortoises/shreddit/pull/139))
- Bump clap from 4.5.29 to 4.5.30 ([#138](https://github.com/sillytortoises/shreddit/pull/138))
- Bump serde_json from 1.0.138 to 1.0.139 ([#140](https://github.com/sillytortoises/shreddit/pull/140))
- Bump clap from 4.5.28 to 4.5.29 ([#137](https://github.com/sillytortoises/shreddit/pull/137))
- Bump clap from 4.5.27 to 4.5.28 ([#136](https://github.com/sillytortoises/shreddit/pull/136))
- Bump async-trait from 0.1.85 to 0.1.86 ([#135](https://github.com/sillytortoises/shreddit/pull/135))
- Bump serde_json from 1.0.137 to 1.0.138 ([#134](https://github.com/sillytortoises/shreddit/pull/134))
- Bump clap from 4.5.26 to 4.5.27 ([#132](https://github.com/sillytortoises/shreddit/pull/132))
- Bump serde_json from 1.0.134 to 1.0.137 ([#131](https://github.com/sillytortoises/shreddit/pull/131))
- Bump tokio from 1.42.0 to 1.43.0 ([#129](https://github.com/sillytortoises/shreddit/pull/129))
- Bump clap from 4.5.23 to 4.5.26 ([#128](https://github.com/sillytortoises/shreddit/pull/128))
- Bump async-trait from 0.1.83 to 0.1.85 ([#127](https://github.com/sillytortoises/shreddit/pull/127))
- release v0.9.11 ([#121](https://github.com/sillytortoises/shreddit/pull/121))
- debug
- debug
- debug
- cache
- release v0.9.10 ([#120](https://github.com/sillytortoises/shreddit/pull/120))
- debug
- debug
- debug
- release v0.9.9 ([#119](https://github.com/sillytortoises/shreddit/pull/119))
- debug
- debug
- release v0.9.8 ([#118](https://github.com/sillytortoises/shreddit/pull/118))
- more fix workflow
- more fix workflow
- Revert "more fix"
- more fix
- release v0.9.7 ([#117](https://github.com/sillytortoises/shreddit/pull/117))
- release v0.9.6 ([#116](https://github.com/sillytortoises/shreddit/pull/116))
- update deps
- release v0.9.5 ([#115](https://github.com/sillytortoises/shreddit/pull/115))
- remove release drafter
- fix clippy warnings
- use release-plz
- Update Cargo.toml
- Fix GitHub actions workflow ([#102](https://github.com/sillytortoises/shreddit/pull/102))
- Revert "fix mac-latest target"
- Bump async-stream from 0.3.5 to 0.3.6 ([#110](https://github.com/sillytortoises/shreddit/pull/110))
- Bump futures-core from 0.3.30 to 0.3.31 ([#111](https://github.com/sillytortoises/shreddit/pull/111))
- Bump clap from 4.5.18 to 4.5.23 ([#112](https://github.com/sillytortoises/shreddit/pull/112))
- Bump reqwest from 0.11.27 to 0.12.12 ([#113](https://github.com/sillytortoises/shreddit/pull/113))
- Bump tracing-subscriber from 0.3.18 to 0.3.19 ([#114](https://github.com/sillytortoises/shreddit/pull/114))
- Create dependabot.yml
- update deps
- Add flags to skip posts/comments ([#100](https://github.com/sillytortoises/shreddit/pull/100))
- Add option to skip subreddits ([#99](https://github.com/sillytortoises/shreddit/pull/99))
- Update Cargo.toml
- allow hyphen values in cli ([#94](https://github.com/sillytortoises/shreddit/pull/94))
- Update Cargo.toml
- Remove use of deprecated DateTime function ([#89](https://github.com/sillytortoises/shreddit/pull/89))
- Update dependencies ([#88](https://github.com/sillytortoises/shreddit/pull/88))
- Use dotenvy instead of dotenv ([#87](https://github.com/sillytortoises/shreddit/pull/87))
- Update README.md with link to first step ([#86](https://github.com/sillytortoises/shreddit/pull/86))
- bump version
- Avoid panic when API doesn't return comment data ([#74](https://github.com/sillytortoises/shreddit/pull/74))
- cleanup
- Update README.md
- Update dependencies
- Update Cargo.lock
- Update Cargo.toml
- Add ability to shred saved posts and comments ([#68](https://github.com/sillytortoises/shreddit/pull/68))
- Update README.md
- Fix panic when running into posts which cannot be retrieved from the API during GDPR run ([#70](https://github.com/sillytortoises/shreddit/pull/70))
- Update Cargo.toml
- Fix rate limit for remainder of June 2023 ([#69](https://github.com/sillytortoises/shreddit/pull/69))
- Update Cargo.toml
- Update README.md
- Custom replacement comment text ([#59](https://github.com/sillytortoises/shreddit/pull/59))
- Add edit-only option ([#66](https://github.com/sillytortoises/shreddit/pull/66))
- Rate limit update ([#65](https://github.com/sillytortoises/shreddit/pull/65))
- Update README.md
- Update dependencies ([#56](https://github.com/sillytortoises/shreddit/pull/56))
- Update Cargo.toml
- Add log to show if config file is loaded ([#55](https://github.com/sillytortoises/shreddit/pull/55))
- Create LICENSE
- Fix posts failing due to different API response ([#48](https://github.com/sillytortoises/shreddit/pull/48))
- Update release-drafter.yml
- Update release-drafter.yml
- Bump version ([#47](https://github.com/sillytortoises/shreddit/pull/47))
- Add User-Agent to all requests ([#46](https://github.com/sillytortoises/shreddit/pull/46))
- Log unexpected access token response ([#37](https://github.com/sillytortoises/shreddit/pull/37))
- Update Cargo.toml
- Update README.md
- Add ability to shred saved comments using GDPR export ([#33](https://github.com/sillytortoises/shreddit/pull/33))
- Add ability to shred saved posts using GDPR export ([#32](https://github.com/sillytortoises/shreddit/pull/32))
- Update dependencies ([#31](https://github.com/sillytortoises/shreddit/pull/31))
- Check if comments were removed by moderator if edit fails ([#30](https://github.com/sillytortoises/shreddit/pull/30))
- Update Cargo.toml
- Fix logs to include item being shredded ([#29](https://github.com/sillytortoises/shreddit/pull/29))
- Update README.md
- Update shreddit.env.example
- Update Cargo.toml
- Add ability to use GDPR export for shredding posts, comments, and friends ([#28](https://github.com/sillytortoises/shreddit/pull/28))
- Rename shreddit.env ([#27](https://github.com/sillytortoises/shreddit/pull/27))
- Update Cargo.toml
- Allow custom User-Agent ([#26](https://github.com/sillytortoises/shreddit/pull/26))
- Update and rename release.yml to draft-release.yml
- Fix pagination starting from beginning when not all posts are deleted ([#22](https://github.com/sillytortoises/shreddit/pull/22))
- Update dependencies ([#21](https://github.com/sillytortoises/shreddit/pull/21))
- Fix Clippy lints ([#20](https://github.com/sillytortoises/shreddit/pull/20))
- Update Cargo.toml
- Fix posts causing panic due to posts not being able to be edited ([#17](https://github.com/sillytortoises/shreddit/pull/17))
- Use single threaded Tokio runtime ([#16](https://github.com/sillytortoises/shreddit/pull/16))
- Update Cargo.toml
- Improve deserialization of responses to surface errors ([#15](https://github.com/sillytortoises/shreddit/pull/15))
- Update release-drafter.yml
- Update Cargo.toml
- Fix pagination ([#13](https://github.com/sillytortoises/shreddit/pull/13))
- Prettify logs ([#12](https://github.com/sillytortoises/shreddit/pull/12))
- update deps ([#11](https://github.com/sillytortoises/shreddit/pull/11))
- Update release-drafter.yml
- Fix delete requests ([#8](https://github.com/sillytortoises/shreddit/pull/8))
- Update Cargo.toml
- Display error for invalid credentials instead of panicking ([#10](https://github.com/sillytortoises/shreddit/pull/10))
- Update Cargo.toml
- Update publish.yml
- Update Cargo.toml
- Fix Linux build architecture
- Update README.md
- Add max score example to env file ([#6](https://github.com/sillytortoises/shreddit/pull/6))
- Update README.md
- Fix README ([#5](https://github.com/sillytortoises/shreddit/pull/5))
- Update release-drafter.yml
- Add ability to filter by max score ([#4](https://github.com/sillytortoises/shreddit/pull/4))
- Create check.yml
- Update release-drafter.yml
- Update .gitignore
- Add ability to preserve items created after date ([#3](https://github.com/sillytortoises/shreddit/pull/3))
- Update release.yml
- Rename release.yml to build.yml
- Update release.yml
- init

## [1.1.8](https://github.com/andrewbanchich/shreddit/compare/v1.1.7...v1.1.8) - 2026-02-04

### Other

- bump serde_json from 1.0.145 to 1.0.149 ([#261](https://github.com/andrewbanchich/shreddit/pull/261))
- bump tokio from 1.48.0 to 1.49.0 ([#262](https://github.com/andrewbanchich/shreddit/pull/262))
- bump clap from 4.5.53 to 4.5.54 ([#264](https://github.com/andrewbanchich/shreddit/pull/264))
- bump reqwest from 0.12.26 to 0.12.28 ([#263](https://github.com/andrewbanchich/shreddit/pull/263))
- bump jiff from 0.2.16 to 0.2.18 ([#265](https://github.com/andrewbanchich/shreddit/pull/265))

## [1.1.7](https://github.com/andrewbanchich/shreddit/compare/v1.1.6...v1.1.7) - 2026-01-11

### Other

- compile for macOS arm64 ([#248](https://github.com/andrewbanchich/shreddit/pull/248))

## [1.1.6](https://github.com/andrewbanchich/shreddit/compare/v1.1.5...v1.1.6) - 2026-01-11

### Other

- bump actions/checkout from 5 to 6 ([#252](https://github.com/andrewbanchich/shreddit/pull/252))
- bump jiff from 0.2.15 to 0.2.16 ([#247](https://github.com/andrewbanchich/shreddit/pull/247))
- bump parse_datetime from 0.13.1 to 0.13.3 ([#251](https://github.com/andrewbanchich/shreddit/pull/251))
- bump tracing-subscriber from 0.3.20 to 0.3.22 ([#253](https://github.com/andrewbanchich/shreddit/pull/253))
- bump actions/cache from 4 to 5 ([#257](https://github.com/andrewbanchich/shreddit/pull/257))
- bump reqwest from 0.12.24 to 0.12.26 ([#258](https://github.com/andrewbanchich/shreddit/pull/258))
- bump tracing from 0.1.43 to 0.1.44 ([#259](https://github.com/andrewbanchich/shreddit/pull/259))
- bump clap from 4.5.49 to 4.5.53 ([#250](https://github.com/andrewbanchich/shreddit/pull/250))
- bump tracing from 0.1.41 to 0.1.43 ([#254](https://github.com/andrewbanchich/shreddit/pull/254))

## [1.1.5](https://github.com/andrewbanchich/shreddit/compare/v1.1.4...v1.1.5) - 2025-10-19

### Other

- Change default branch from 'master' to 'main'
- bump csv from 1.3.1 to 1.4.0 ([#241](https://github.com/andrewbanchich/shreddit/pull/241))
- remove unused

## [1.1.4](https://github.com/andrewbanchich/shreddit/compare/v1.1.3...v1.1.4) - 2025-10-19

### Fixed

- test ([#237](https://github.com/andrewbanchich/shreddit/pull/237))

## [1.1.3](https://github.com/andrewbanchich/shreddit/compare/v1.1.2...v1.1.3) - 2025-10-19

### Fixed

- use oauth for listing posts/comments ([#235](https://github.com/andrewbanchich/shreddit/pull/235))

### Other

- bump serde from 1.0.223 to 1.0.228 ([#229](https://github.com/andrewbanchich/shreddit/pull/229))
- bump clap from 4.5.47 to 4.5.49 ([#232](https://github.com/andrewbanchich/shreddit/pull/232))
- bump parse_datetime from 0.11.0 to 0.13.1 ([#231](https://github.com/andrewbanchich/shreddit/pull/231))
- bump reqwest from 0.12.23 to 0.12.24 ([#233](https://github.com/andrewbanchich/shreddit/pull/233))
- bump tokio from 1.47.1 to 1.48.0 ([#234](https://github.com/andrewbanchich/shreddit/pull/234))
- bump serde_json from 1.0.143 to 1.0.145 ([#221](https://github.com/andrewbanchich/shreddit/pull/221))

## [1.1.2](https://github.com/andrewbanchich/shreddit/compare/v1.1.1...v1.1.2) - 2025-09-11

### Other

- bump amannn/action-semantic-pull-request from 5 to 6 ([#211](https://github.com/andrewbanchich/shreddit/pull/211))
- bump async-trait from 0.1.88 to 0.1.89 ([#210](https://github.com/andrewbanchich/shreddit/pull/210))
- bump serde_json from 1.0.142 to 1.0.143 ([#213](https://github.com/andrewbanchich/shreddit/pull/213))
- bump clap from 4.5.44 to 4.5.47 ([#217](https://github.com/andrewbanchich/shreddit/pull/217))
- bump actions/checkout from 4 to 5 ([#212](https://github.com/andrewbanchich/shreddit/pull/212))
- bump chrono from 0.4.41 to 0.4.42 ([#218](https://github.com/andrewbanchich/shreddit/pull/218))
- bump tracing-subscriber from 0.3.19 to 0.3.20 ([#216](https://github.com/andrewbanchich/shreddit/pull/216))
- bump reqwest from 0.12.22 to 0.12.23 ([#208](https://github.com/andrewbanchich/shreddit/pull/208))
- bump parse_datetime from 0.9.0 to 0.11.0 ([#205](https://github.com/andrewbanchich/shreddit/pull/205))
- bump serde_json from 1.0.140 to 1.0.142 ([#203](https://github.com/andrewbanchich/shreddit/pull/203))
- bump clap from 4.5.43 to 4.5.44 ([#207](https://github.com/andrewbanchich/shreddit/pull/207))
- bump clap from 4.5.37 to 4.5.43 ([#206](https://github.com/andrewbanchich/shreddit/pull/206))
- bump tokio from 1.45.0 to 1.47.1 ([#204](https://github.com/andrewbanchich/shreddit/pull/204))
- bump reqwest from 0.12.15 to 0.12.22 ([#196](https://github.com/andrewbanchich/shreddit/pull/196))
- bump tokio from 1.44.2 to 1.45.0 ([#183](https://github.com/andrewbanchich/shreddit/pull/183))

## [1.1.1](https://github.com/andrewbanchich/shreddit/compare/v1.1.0...v1.1.1) - 2025-04-30

### Fixed

- use consistent sorting to ensure all comments captured ([#180](https://github.com/andrewbanchich/shreddit/pull/180))

### Other

- Update usage output to document valid arguments ([#179](https://github.com/andrewbanchich/shreddit/pull/179))
- bump chrono from 0.4.40 to 0.4.41 ([#182](https://github.com/andrewbanchich/shreddit/pull/182))
- bump parse_datetime from 0.8.0 to 0.9.0 ([#181](https://github.com/andrewbanchich/shreddit/pull/181))
- bump tokio from 1.44.1 to 1.44.2 ([#173](https://github.com/andrewbanchich/shreddit/pull/173))
- bump clap from 4.5.36 to 4.5.37 ([#177](https://github.com/andrewbanchich/shreddit/pull/177))
- bump clap from 4.5.33 to 4.5.36 ([#174](https://github.com/andrewbanchich/shreddit/pull/174))
- bump clap from 4.5.32 to 4.5.33 ([#170](https://github.com/andrewbanchich/shreddit/pull/170))
- bump reqwest from 0.12.14 to 0.12.15 ([#168](https://github.com/andrewbanchich/shreddit/pull/168))
- bump async-trait from 0.1.87 to 0.1.88 ([#167](https://github.com/andrewbanchich/shreddit/pull/167))
- bump reqwest from 0.12.13 to 0.12.14 ([#165](https://github.com/andrewbanchich/shreddit/pull/165))
- bump tokio from 1.44.0 to 1.44.1 ([#166](https://github.com/andrewbanchich/shreddit/pull/166))
- bump reqwest from 0.12.12 to 0.12.13 ([#164](https://github.com/andrewbanchich/shreddit/pull/164))
- bump clap from 4.5.31 to 4.5.32
- bump serde from 1.0.218 to 1.0.219 ([#160](https://github.com/andrewbanchich/shreddit/pull/160))

## [1.1.0](https://github.com/andrewbanchich/shreddit/compare/v1.0.2...v1.1.0) - 2025-03-09

### Added

- support relative timestamps in --after filters

### Other

- update doc comment for relative timestamps
- rename variable

## [1.0.2](https://github.com/andrewbanchich/shreddit/compare/v1.0.1...v1.0.2) - 2025-03-09

### Fixed

- make --before filter optional
- make --after filter optional
- reddit link

### Other

- Revert "ci: allow workflow_dispatch trigger for release"

## [1.0.1](https://github.com/andrewbanchich/shreddit/compare/v1.0.0...v1.0.1) - 2025-03-09

### Other

- allow workflow_dispatch trigger for release
- use bash for windows release
- update checks workflow
