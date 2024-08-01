# Changelog

fnksjdnfkjdsn

## [1.4.6](https://github.com/currents-dev/currents-playwright/compare/v1.4.5...v1.4.6) (2024-07-26)

### Bug Fixes

- show correct count of failed flaky tests ([2f26bd2](https://github.com/currents-dev/currents-playwright/commit/2f26bd2036ec98158e1a84ed0d63b40c283a525a))

## [1.4.5](https://github.com/currents-dev/currents-playwright/compare/v1.4.3...v1.4.5) (2024-07-10)

### Bug Fixes

- add CURRENTS_PWCP_DRY_RUN ([c2b6777](https://github.com/currents-dev/currents-playwright/commit/c2b6777eb07b0478064a02782deaaf7d4c4564f7))

## [1.4.4](https://github.com/currents-dev/currents-playwright/compare/v1.4.4...v1.4.3) (2024-06-25)

### Misc

- pwc: Auto generate ciBuildId when not detected

## [1.4.3](https://github.com/currents-dev/currents-playwright/compare/v1.4.3-beta.1...v1.4.3) (2024-06-25)

### Bug Fixes

- use proxy-from-env ([10816fa](https://github.com/currents-dev/currents-playwright/commit/10816fa9bb107ad7103b0fd6c6dfe5a9d6a11ddb))
- use https-proxy-agent ([3da0e47](https://github.com/currents-dev/currents-playwright/commit/3da0e475d622df72b4fa0333bd1f4ec798a2c68c))

### Misc

- update dependencies to patch vulnerabilities

## [1.4.3-beta.1](https://github.com/currents-dev/currents-playwright/compare/v1.4.3-beta.0...v1.4.3-beta.1) (2024-06-24)

### Bug Fixes

- use proxy for uploads ([75aa154](https://github.com/currents-dev/currents-playwright/commit/75aa154227736169452c0d0627d4b3e82104bba7))

## [1.4.3-beta.0](https://github.com/currents-dev/currents-playwright/compare/v1.4.1...v1.4.3-beta.0) (2024-06-24)

### Bug Fixes

- use https-proxy-agent ([3da0e47](https://github.com/currents-dev/currents-playwright/commit/3da0e475d622df72b4fa0333bd1f4ec798a2c68c))

## [1.4.2](https://github.com/currents-dev/currents-playwright/compare/v1.4.1...v1.4.2) (2024-06-21)

### Bug Fixes

- Arg parsing side-effect that was duplicating tests CSR-1276 ([#170](https://github.com/currents-dev/currents-playwright/issues/170)) ([05cfd4b](https://github.com/currents-dev/currents-playwright/commit/05cfd4b80a89f547a1a36951e34a9586fb54cb54))

## [1.4.1](https://github.com/currents-dev/currents-playwright/compare/v1.4.0...v1.4.1) (2024-06-18)

### Bug Fixes

- move to config function and set in onBegin ([60bbe2a](https://github.com/currents-dev/currents-playwright/commit/60bbe2a553ee300c3c49b5527f30bcfa4c1b3308))
- remove warning from discovery reporter and add it to orchestration reporter ([18a9030](https://github.com/currents-dev/currents-playwright/commit/18a90303db5d26d9ced761c7761355396d970e92))

# [1.4.0](https://github.com/currents-dev/currents-playwright/compare/v1.3.3...v1.4.0) (2024-06-10)

### Features

- Enable passing additional reporters on the cli ([#164](https://github.com/currents-dev/currents-playwright/issues/164)) ([07e9bee](https://github.com/currents-dev/currents-playwright/commit/07e9bee8a78088479268a6db833305d1e88f52ca))

### Bug Fixes

- Allow pwc-p to read config from the environment ([#160](https://github.com/currents-dev/currents-playwright/issues/160)) ([47effc3](https://github.com/currents-dev/currents-playwright/commit/47effc37aa3c06ca2629613118f1434f454c0122))
- drop sourcemaps-support register for reporters ([#165](https://github.com/currents-dev/currents-playwright/issues/165)) ([70174bf](https://github.com/currents-dev/currents-playwright/commit/70174bf1b0572a672d053c998bf5e04bcdf21d1a))

## [1.3.3](https://github.com/currents-dev/currents-playwright/compare/v1.3.2...v1.3.3) (2024-06-03)

### Bug Fixes

- fullConfig finding failed in playwright v1.32 and below ([d09e946](https://github.com/currents-dev/currents-playwright/commit/d09e946b22268daae4e6c0d5570fc8163fb238bd))

## [1.3.2](https://github.com/currents-dev/currents-playwright/compare/v1.3.1...v1.3.2) (2024-05-29)

### Bug Fixes

- filter playwright options from undesired arguments ([e6e412d](https://github.com/currents-dev/currents-playwright/commit/e6e412df7e4f28ceb580dee7b069ed7bdc611f39))

## [1.3.1](https://github.com/currents-dev/currents-playwright/compare/v1.3.0...v1.3.1) (2024-05-17)

### Bug Fixes

- pwc-p - don't allow task groupId to be overridden by cli args ([e727f5b](https://github.com/currents-dev/currents-playwright/commit/e727f5b8bb552fac423d4bbbc54b45a9130807a0))
- use -- to separate the playwright command cli options and arguments ([8ea7078](https://github.com/currents-dev/currents-playwright/commit/8ea7078b1d68a6ccca90908a00f1d3fb2733579c))

# [1.3.0](https://github.com/currents-dev/currents-playwright/compare/v1.1.8...v1.3.0) (2024-05-16)

### Bug Fixes

- add --repeat-each to scanner args ([2ad9d16](https://github.com/currents-dev/currents-playwright/commit/2ad9d16fa4c13461ddaf34ae5ab194b7f8b49aa0))

### Features

- Support --pwc-reset-signal for resetting machine specs [CSR-1152] ([#153](https://github.com/currents-dev/currents-playwright/issues/153)) ([ab38e51](https://github.com/currents-dev/currents-playwright/commit/ab38e515039c5e112a3541ff44cea32bef6c9114)), closes [#157](https://github.com/currents-dev/currents-playwright/issues/157)

# [1.2.0](https://github.com/currents-dev/currents-playwright/compare/v1.2.0-beta.0...v1.2.0) (2024-05-03)

# [1.2.0-beta.0](https://github.com/currents-dev/currents-playwright/compare/v1.1.8...v1.2.0-beta.0) (2024-05-03)

### Features

- add --pwc-output-file for JSON output [CSR-1157] ([#151](https://github.com/currents-dev/currents-playwright/issues/151)) ([f3626d0](https://github.com/currents-dev/currents-playwright/commit/f3626d057748fd3a9b525c6c2a5ff5d29eedaff7))

## [1.1.9](https://github.com/currents-dev/currents-playwright/compare/v1.1.8...v1.1.9) (2024-04-30)

## [1.1.9-alpha.0](https://github.com/currents-dev/currents-playwright/compare/v1.1.8...v1.1.9-alpha.0) (2024-04-30)

### Bug Fixes

- add lodash as a dep for scanner [skip ci] ([c7ec06b](https://github.com/currents-dev/currents-playwright/commit/c7ec06bc9b2a09bed6168c6adeb87c90a9e556ef))

## [1.1.8](https://github.com/currents-dev/currents-playwright/compare/v1.1.7...v1.1.8) (2024-04-26)

### Bug Fixes

- add "tmp" module dependecy ([#146](https://github.com/currents-dev/currents-playwright/issues/146)) ([5561a04](https://github.com/currents-dev/currents-playwright/commit/5561a04f13de37ca6cc29ddaaed418a2b0f5af69))

## [1.1.7](https://github.com/currents-dev/currents-playwright/compare/v1.1.6...v1.1.7) (2024-04-18)

### Bug Fixes

- Use the correct spec file location ([9dbefcb](https://github.com/currents-dev/currents-playwright/commit/9dbefcb3547acd9ba4ca758e4b0ba2b05f47091a))

## [1.1.6](https://github.com/currents-dev/currents-playwright/compare/v1.1.5...v1.1.6) (2024-04-09)

### Bug Fixes

- use pwc-scanner@0.1.0 [skip ci] ([1918036](https://github.com/currents-dev/currents-playwright/commit/1918036ece840f44373fe3a013838779eef87d08))
- generate name for projects with an empty name or undefined name
- forbid orchestration for unnamed projects

## [1.1.5](https://github.com/currents-dev/currents-playwright/compare/v1.1.4...v1.1.5) (2024-04-05)

### Bug Fixes

- don't throw when there is missing instanceId ([767eb45](https://github.com/currents-dev/currents-playwright/commit/767eb45f2a46b4ff0606c6ee439f086dd0d9f207))

## [1.1.4](https://github.com/currents-dev/currents-playwright/compare/v1.1.3...v1.1.4) (2024-04-03)

## [1.1.3](https://github.com/currents-dev/currents-playwright/compare/v1.1.2...v1.1.3) (2024-04-03)

### Bug Fixes

- fix widnows paths for fullTestSuite ([9d3e56e](https://github.com/currents-dev/currents-playwright/commit/9d3e56e138f8b0a357e20328936333b8f0b2aa39))

## [1.1.2](https://github.com/currents-dev/currents-playwright/compare/v1.1.0...v1.1.2) (2024-04-01)

### Bug Fixes

- @currents/pwc-scanner@0.0.4 ([9d2fef1](https://github.com/currents-dev/currents-playwright/commit/9d2fef1803038f0c69d5d76a32af69ad396540a1))

## [1.1.1](https://github.com/currents-dev/currents-playwright/compare/v1.1.0...v1.1.1) (2024-04-01)

### Bug Fixes

- fix a bug with explicit projects for the same ci-build-id ([92cb0db](https://github.com/currents-dev/currents-playwright/commit/92cb0dba392e39cd5f260b41a21fe6053e02a480))
- fix a bug with ignoring --grep-invert for discovering full testing suite, add context for debug ([1766c01](https://github.com/currents-dev/currents-playwright/commit/1766c017bcdeef6df71551d5215dd593f19bdefd))
- consider .only for discovering full testing suite ([1ac74fe](https://github.com/currents-dev/currents-playwright/commit/1ac74fe27066210407f22e3698bbaf41020b76f7))

# [1.1.0](https://github.com/currents-dev/currents-playwright/compare/v1.0.1...v1.1.0) (2024-03-27)

### Features

- Pipeline url information from azure ([#137](https://github.com/currents-dev/currents-playwright/issues/137)) ([0c022ac](https://github.com/currents-dev/currents-playwright/commit/0c022acce2febf92f14106fde91a2a7593de7cf0))

## [1.0.1](https://github.com/currents-dev/currents-playwright/compare/v0.12.2...v1.0.1) (2024-03-26)

### Features

This is a major revamp of the reporter. There are **no breaking changes** in terms of API and configuration, but there are significant changes in the underlying reporting mechanism and the produced output.

- **Full parallel mode support**: set `fullyParallel: true` to enable running individual tests from the [same spec file on different workers](https://playwright.dev/docs/api/class-testproject#test-project-fully-parallel). Playwright supports multiple levels of concurrency - a test suite can be split between different machines using sharding, and on each individual machine Playwright will spawn parallel workers (according to CPU performance or explicit configuration). The workers will run in parallel, executing the tests (or more precisely, test attempts). By default, Playwright runs the tests of the same spec file serially one after another, but, if the tests are isolated, enabling `fullyParallel: true` will allow running tests from the same spec file in parallel on different workers (or sometimes even on different shards / machines). The most recent version of the reporter is compatible with full parallel mode and will collect the results of concurrent parallel executions.

- **Step-level reporting**: playwright organizes tests executions according to the following hierarchy: Run > Project > Spec File > Test > Attempt > Step. Traditionally, reporters send the results **after** Run completion (sometimes after Spec File completion). It works well in most cases, but.... imagine running a spec file with 10 tests on a CI machine. 9 tests can be completed successfully, but the last test can cause a crash. If we report **after** spec completion, no results will be reported at all, even for 9 completed test. Currents reporter sends the results for each individual step (with some batching applied for better performance). That allows capturing as much information as possible as soon as it's ready. It is super-valuable for debugging failed CI executions, which are often unique and are not easy to reproduce locally.

- **Reporter output and results**: we have refactored the look and the feel of the reporter's console output for more precise and accurate presentation of the execution workflow. A test execution consists of one or more attempts, each attempt can have its own status, errors, stdout and stderr output. [Determining](https://docs.currents.dev/tests/test-status#playwright-test-status) a test's "status" and flakiness requires considering the outcome of all the attempts, the expected status and the execution mode (e.g. ["serial" mode](https://playwright.dev/docs/test-parallel#serial-mode) can generate extra attempts). The new format makes it easier to track the logic behind determining test status, displays individual attempts errors. Additionally, we split the captured output, that can have mixed items from concurrent parallel workers and assign them to the corresponding spec files.

- **Playwright orchestration**: the new CLI tool `pwc-p` improves Playwright CI executions by automatically balancing spec files between CI machines. The balancing uses the data from the previously recorded executions to optimally assign spec files between machines, which allows up to 40% decrease in CI E2E Playwright tests. Please refer to our documentation for more details and instructions.

## [0.12.2](https://github.com/currents-dev/currents-playwright/compare/v0.12.1...v0.12.2) (2024-03-06)

### Bug Fixes

- handle teamcity git params ([56ad8fc](https://github.com/currents-dev/currents-playwright/commit/56ad8fc9fa5896001d62dbb176ba14052a3c42a9))

## [0.12.1](https://github.com/currents-dev/currents-playwright/compare/v0.12.0...v0.12.1) (2024-02-05)

### Bug Fixes

- use proper debug fn for cancellation ([a5cc5c1](https://github.com/currents-dev/currents-playwright/commit/a5cc5c11e4c21f4ec681356f72b42c5bda9edb39))

# [0.12.0](https://github.com/currents-dev/currents-playwright/compare/v0.11.5...v0.12.0) (2024-01-30)

### Features

- Collect GitHub Actions PR information ([7229ac](https://github.com/currents-dev/currents-playwright/commit/7229acd8ae48d2bf34f653be4bf9bfdfd682d3a0))

### Features

- add scanner package, wip ([3195de4](https://github.com/currents-dev/currents-playwright/commit/3195de499912956d7911a41c30c56923f1552376))

## [0.11.5](https://github.com/currents-dev/currents-playwright/compare/v0.11.5-beta.0...v0.11.5) (2023-12-17)

### Bug Fixes

- report non-run tests and attempts as skipped ([dc22305](https://github.com/currents-dev/currents-playwright/commit/dc2230526ee6c7ed9c7f13a90e43de393aaf62e4))

## [0.11.4](https://github.com/currents-dev/currents-playwright/compare/v0.11.3...v0.11.4) (2023-12-11)

## [0.11.3](https://github.com/currents-dev/currents-playwright/compare/v0.11.3-beta.1...v0.11.3) (2023-12-11)

### Bug Fixes

- add remote debugging ([6db1329](https://github.com/currents-dev/currents-playwright/commit/6db13291fafdbc30eb0e70ad6c56de9591c1e735))

## [0.11.2](https://github.com/currents-dev/currents-playwright/compare/v0.11.1...v0.11.2) (2023-12-05)

### Bug Fixes

- exit with zero when no tests detected ([459af9e](https://github.com/currents-dev/currents-playwright/commit/459af9e1570d1675f6b390cd546e5152a0771d7f))

## [0.11.1](https://github.com/currents-dev/currents-playwright/compare/v0.11.0...v0.11.1) (2023-12-01)

### Bug Fixes

- fix cli description ([a8b95b7](https://github.com/currents-dev/currents-playwright/commit/a8b95b74b884401b92b139d4e1ffc8ba7d371568))

# [0.11.0](https://github.com/currents-dev/currents-playwright/compare/v0.11.0-beta.0...v0.11.0) (2023-12-01)

### Bug Fixes

- handle cloud error messages ([c978e9f](https://github.com/currents-dev/currents-playwright/commit/c978e9f05579739df9499604eac0810f9394374c))
- reporter to return run actual status ([3727167](https://github.com/currents-dev/currents-playwright/commit/372716719afd1d31e2d9875b7df917c4a17ac83d))

### Features

- implement cancelAfterFailures and disableTitleTags ([452e666](https://github.com/currents-dev/currents-playwright/commit/452e666b741ea84c216c745b22a4d35a65307ab4))

## [0.10.9](https://github.com/currents-dev/currents-playwright/compare/v0.10.8...v0.10.9) (2023-11-23)

### Bug Fixes

- change doc link ([6d4aacc](https://github.com/currents-dev/currents-playwright/commit/6d4aaccbfa35d956483a580b2580ddb3b6f789d9))

## [0.10.8](https://github.com/currents-dev/currents-playwright/compare/v0.10.8-beta.0...v0.10.8) (2023-11-22)

### Bug Fixes

- set status and flaks based on pw outcome ([2bcec5e](https://github.com/currents-dev/currents-playwright/commit/2bcec5ee12ededa30244ef604c93b63640ab939b))

- handle serial mode ([9499528](https://github.com/currents-dev/currents-playwright/commit/9499528706ee2fe6cfe474ecb4c7578cab3c0fe5))

## [0.10.7](https://github.com/currents-dev/currents-playwright/compare/v0.10.6...v0.10.7) (2023-11-20)

### Bug Fixes

- add commander as a dependency ([f00191b](https://github.com/currents-dev/currents-playwright/commit/f00191b3509d7dd47c292ac11b0ef5c31994eaf0))

## [0.10.6](https://github.com/currents-dev/currents-playwright/compare/v0.10.5...v0.10.6) (2023-11-07)

### Bug Fixes

- use @currents/commit-info ([b737211](https://github.com/currents-dev/currents-playwright/commit/b73721163ec1921fca05eda71111e1abe9a59283))

## [0.10.5](https://github.com/currents-dev/currents-playwright/compare/v0.10.4...v0.10.5) (2023-11-07)

### Bug Fixes

- remove \_pwc-parallel because of pnpm error ([6f9c785](https://github.com/currents-dev/currents-playwright/commit/6f9c785e475f4e78ffcf1dd08b1c5ca7f7beeacf))

## [0.10.4](https://github.com/currents-dev/currents-playwright/compare/v0.10.3...v0.10.4) (2023-11-04)

### Bug Fixes

- remove log message ([8dea731](https://github.com/currents-dev/currents-playwright/commit/8dea73149ffefc6ec283ba543bd5469292e845dd))

## [0.10.3](https://github.com/currents-dev/currents-playwright/compare/v0.10.2...v0.10.3) (2023-11-04)

### Bug Fixes

- make reporterOptions optional ([b497249](https://github.com/currents-dev/currents-playwright/commit/b497249b38d4da16f8d63fa79a5953e960396f50))

## [0.10.2](https://github.com/currents-dev/currents-playwright/compare/v0.10.1...v0.10.2) (2023-11-02)

### Bug Fixes

- report tests for single project ([de6448e](https://github.com/currents-dev/currents-playwright/commit/de6448efebbb59cc35f86297b88250bc35c6bb12))

## [0.10.1](https://github.com/currents-dev/currents-playwright/compare/v0.10.0...v0.10.1) (2023-10-31)

### Bug Fixes

- add missing deps ([9c9e875](https://github.com/currents-dev/currents-playwright/commit/9c9e875d5f8cda7a9327df582f952aa8c3f7fefe))

# [0.10.0](https://github.com/currents-dev/currents-playwright/compare/v0.10.0-beta.2...v0.10.0) (2023-10-31)

### Bug Fixes

- make non-mandatory config optional ([f6b8dcd](https://github.com/currents-dev/currents-playwright/commit/f6b8dcdba50b299039f91bc5e232f75db1101270))

- detect build id in CI ([efcf50d](https://github.com/currents-dev/currents-playwright/commit/efcf50de2e82225e9f276a5d635dbdc66af5c5c2))

### Features

- add --pwc-remove-title-tags ([e842bdb](https://github.com/currents-dev/currents-playwright/commit/e842bdbd7412c5423455610f3c60b5e5af6040df))
- refactor CLI processing ([c5f4977](https://github.com/currents-dev/currents-playwright/commit/c5f49770ca94c20f5fb226748916c2e606f60cee))
- support tags in project metadata ([b11ee9c](https://github.com/currents-dev/currents-playwright/commit/b11ee9cfac44d367f08cf4283a72efc305d61564))

# [0.9.0](https://github.com/currents-dev/currents-playwright/compare/v0.8.1...v0.9.0) (2023-10-20)

### Features

- implement cancellations ([f9bcad0](https://github.com/currents-dev/currents-playwright/commit/f9bcad0f9617988b4e77a47f6804a362c0013422))

### Bug Fixes

- check cancellation for existing runs ([f9bcad0](https://github.com/currents-dev/currents-playwright/commit/f9bcad0f9617988b4e77a47f6804a362c0013422))
- remove useless try...catch block ([46c4403](https://github.com/currents-dev/currents-playwright/commit/46c440300864659f07302143772be4a7e8d414e9))

## [0.8.1](https://github.com/currents-dev/currents-playwright/compare/v0.8.0...v0.8.1) (2023-09-07)

### Bug Fixes

- redact attachments body ([cf6c757](https://github.com/currents-dev/currents-playwright/commit/cf6c757ab02dd4b668ec159808d3049a50d03ba6))

# [0.8.0](https://github.com/currents-dev/currents-playwright/compare/v0.7.2...v0.8.0) (2023-09-07)

### Features

- test-level report ([9797b7a](https://github.com/currents-dev/currents-playwright/commit/9797b7ac68d0fe3e8627058c2e791134f6943345))

## [0.7.2](https://github.com/currents-dev/currents-playwright/compare/v0.7.1...v0.7.2) (2023-08-23)

### Bug Fixes

- capture error details ([7fbcacd](https://github.com/currents-dev/currents-playwright/commit/7fbcacd80cf7649d0a1676628aaf03cd80ca1acb))

## [0.7.1](https://github.com/currents-dev/currents-playwright/compare/v0.7.0...v0.7.1) (2023-08-16)

# [0.7.0](https://github.com/currents-dev/currents-playwright/compare/v0.6.4...v0.7.0) (2023-08-16)

### Features

- implement tags ([3ac3bf1](https://github.com/currents-dev/currents-playwright/commit/3ac3bf12696698d908adc032cb061164374d34ea))

## [0.6.4](https://github.com/currents-dev/currents-playwright/compare/v0.6.0...v0.6.4) (2023-08-09)

### Bug Fixes

- add debug message for execa ([d94e49f](https://github.com/currents-dev/currents-playwright/commit/d94e49fa264320eb17fda919a040c714cfcca0c2))
- add execa ([4158356](https://github.com/currents-dev/currents-playwright/commit/415835689d6c0a7aab73278e97983e8895a4e22b))

## [0.6.4-beta.0](https://github.com/currents-dev/currents-playwright/compare/v0.6.0...v0.6.4-beta.0) (2023-07-29)

### Bug Fixes

- add execa ([4158356](https://github.com/currents-dev/currents-playwright/commit/415835689d6c0a7aab73278e97983e8895a4e22b))

## [0.6.3](https://github.com/currents-dev/currents-playwright/compare/v0.6.0...v0.6.3) (2023-07-12)

### Bug Fixes

- report errors for hooks and internal steps ([1ce1d89](https://github.com/currents-dev/currents-playwright/commit/1ce1d89eaf23d55f36a57265eab084f30f920744))

## [0.6.2](https://github.com/currents-dev/currents-playwright/compare/v0.6.0...v0.6.2) (2023-06-30)

### Bug Fixes

- set pw version ([89468b2](https://github.com/currents-dev/currents-playwright/commit/89468b2fe173a49472e1aa6e9578786a4a1ae8d7))
- specify content-type and disposition ([d9ba3e3](https://github.com/currents-dev/currents-playwright/commit/d9ba3e3424b7c848d37fb3ecd1abb32ed6795d4e))
- support multiple videos ([10d10f9](https://github.com/currents-dev/currents-playwright/commit/10d10f9f997c889e0ead45e3d76b90ca84f406b2))

## [0.6.1](https://github.com/currents-dev/currents-playwright/compare/v0.6.0...v0.6.1) (2023-06-30)

### Bug Fixes

- set pw version ([89468b2](https://github.com/currents-dev/currents-playwright/commit/89468b2fe173a49472e1aa6e9578786a4a1ae8d7))
- specify content-type and disposition ([d9ba3e3](https://github.com/currents-dev/currents-playwright/commit/d9ba3e3424b7c848d37fb3ecd1abb32ed6795d4e))
- support multiple videos ([10d10f9](https://github.com/currents-dev/currents-playwright/commit/10d10f9f997c889e0ead45e3d76b90ca84f406b2))

# [0.6.0](https://github.com/currents-dev/currents-playwright/compare/v0.5.0...v0.6.0) (2023-06-15)

### Bug Fixes

- report pwc version ([c3745a2](https://github.com/currents-dev/currents-playwright/commit/c3745a2f7502c5695775cda1d82c64a36a152f1c))
- send workerId information ([fe29eb5](https://github.com/currents-dev/currents-playwright/commit/fe29eb5e9e072effe65de517d6964d38590b9f4e))

### Features

- send workerIndex and parallelIndex ([c392a41](https://github.com/currents-dev/currents-playwright/commit/c392a41544679305ab12d229b6973cb8dfe1acfa))

# [0.5.0](https://github.com/currents-dev/currents-playwright/compare/v0.5.0-beta.2...v0.5.0) (2023-06-11)

# [0.5.0-beta.2](https://github.com/currents-dev/currents-playwright/compare/v0.5.0-beta.1...v0.5.0-beta.2) (2023-06-08)

### Bug Fixes

- remove playwright from peer deps ([755148e](https://github.com/currents-dev/currents-playwright/commit/755148ea47bc5c909e15a01e00948b5ed2f114e8))

# [0.5.0-beta.1](https://github.com/currents-dev/currents-playwright/compare/0.5.0-beta.0...v0.5.0-beta.1) (2023-06-08)

# [0.5.0-beta.0](https://github.com/currents-dev/currents-playwright/compare/0.4.2...0.5.0-beta.0) (2023-06-08)

### Features

- support image buffers
- upload console output directly to remote storage
- better error messages ([f87a5a9](https://github.com/currents-dev/currents-playwright/commit/f87a5a9a0a706f74290afe5802cd37f193de6b7e))

### Bug Fixes

- show warning received from cloud service
- handle screenshot buffers ([d24b9ab](https://github.com/currents-dev/currents-playwright/commit/d24b9abe07990fa366b0d6d1337184d9c9bb0ae2))
- reduce payload size ([a7b3ed7](https://github.com/currents-dev/currents-playwright/commit/

## [0.4.2](https://github.com/currents-dev/currents-playwright/compare/0.4.1...0.4.2) (2023-05-12)

### Bug Fixes

- fix npm dependencies ([608cd53](https://github.com/currents-dev/currents-playwright/commit/608cd53fa60999fe60f07fe611cca3dfd250a13a))

## [0.4.1](https://github.com/currents-dev/currents-playwright/compare/0.4.0...0.4.1) (2023-05-09)

### Bug Fixes

- fallback to \_id for testCase ([923e7e9](https://github.com/currents-dev/currents-playwright/commit/923e7e9f109802c16e36353f31a2c53387e1d2b3))

# [0.4.0](https://github.com/currents-dev/currents-playwright/compare/0.3.8-beta.0...0.4.0) (2023-05-05)

### Bug Fixes

- allow debugging extensions ([17b5a5f](https://github.com/currents-dev/currents-playwright/commit/17b5a5f0047df8b4fa610b07d47a88a71be34a7d))
- send ciBuildId when creating a run ([d47a2c1](https://github.com/currents-dev/currents-playwright/commit/d47a2c176b308e842eaf67439679354cee82a073))
- show upload warnings at the end of execution ([63c91f3](https://github.com/currents-dev/currents-playwright/commit/63c91f33cc253ef432236e1664a644df40d4a5c1))
- upload stdout and artifacts in parallel ([10a0d2d](https://github.com/currents-dev/currents-playwright/commit/10a0d2d891a1a0c71dccfb7842a37089e26b5647))
- use debug extensions ([0512596](https://github.com/currents-dev/currents-playwright/commit/05125960e25fb532824d268c1a46e82682faa163))

### Features

- refactor + stabilize network uploads ([1f945b6](https://github.com/currents-dev/currents-playwright/commit/1f945b6168e601e0f1f48cf1e4bfd64fd0ee3e25))
- refactor + stabilize network uploads ([1b1cbe9](https://github.com/currents-dev/currents-playwright/commit/1b1cbe9cf136efb056299b257e88fba31fdb2a68))

## [0.3.8-beta.0](https://github.com/currents-dev/currents-playwright/compare/0.3.7...0.3.8-beta.0) (2023-04-20)

### Bug Fixes

- use network retries, enhance debugging ([f996250](https://github.com/currents-dev/currents-playwright/commit/f996250a3b52ade75e0a676c31d50153c2c12b8b))

## [0.3.7](https://github.com/currents-dev/currents-playwright/compare/0.3.6...0.3.7) (2023-04-11)

### Bug Fixes

- send raw results for troubleshooting ([712cf7e](https://github.com/currents-dev/currents-playwright/commit/712cf7e0865ea3fc7488aa8fb01c0fde8db8fde6))

## [0.3.6](https://github.com/currents-dev/currents-playwright/compare/0.3.5...0.3.6) (2023-04-10)

### Bug Fixes

- handle expected vs actual tests status ([6d3c5cb](https://github.com/currents-dev/currents-playwright/commit/6d3c5cb18d1cad94f856eb37fa10cacf0d13ac89))

## [0.3.5](https://github.com/currents-dev/currents-playwright/compare/0.3.4...0.3.5) (2023-03-31)

### Bug Fixes

- use execa to support windows ([b20b746](https://github.com/currents-dev/currents-playwright/commit/b20b746c08f04f8d714d4d39eae49c86387ffc8f))

## [0.3.4](https://github.com/currents-dev/currents-playwright/compare/0.3.3...0.3.4) (2023-02-20)

### Bug Fixes

- wait for flaky test to complete ([95fffef](https://github.com/currents-dev/currents-playwright/commit/95fffef93522391ad665e14841a976fe61da747e))

## [0.3.3](https://github.com/currents-dev/currents-playwright/compare/0.3.2...0.3.3) (2023-02-08)

## [0.3.2](https://github.com/currents-dev/currents-playwright/compare/0.3.1...0.3.2) (2023-02-08)

### Bug Fixes

- handle empty results ([ac09874](https://github.com/currents-dev/currents-playwright/commit/ac098748be6cf135c829b9e3694e19f87ea120ae))

## [0.3.1](https://github.com/currents-dev/currents-playwright/compare/0.3.0...0.3.1) (2023-02-06)

### Bug Fixes

- remove requiring pw+pwc version ([9481736](https://github.com/currents-dev/currents-playwright/commit/9481736139dc96a781bd8103d9fac8651c422b92))

# [0.3.0](https://github.com/currents-dev/currents-playwright/compare/0.2.2...0.3.0) (2023-02-06)

### Bug Fixes

- exist with pw's exit status ([983bb0c](https://github.com/currents-dev/currents-playwright/commit/983bb0c3aece981c6c28fd2f36b2fdef63320d20))
- handle expired run case ([5d008cf](https://github.com/currents-dev/currents-playwright/commit/5d008cfc881c70d5c6471c5032654cabcee14606))
- use claimedCount > 1 ([ee40f1e](https://github.com/currents-dev/currents-playwright/commit/ee40f1e01ff9f17468a1cb975a45456ca3fe8ba0))
- use dedicated pw stdout endpoint ([62f4a48](https://github.com/currents-dev/currents-playwright/commit/62f4a481cbef8e93d1a500942d5df84cca9379dd))
- use PR ref for clear message ([3c7e6a6](https://github.com/currents-dev/currents-playwright/commit/3c7e6a671d4eb8dd6883f0c86e93db3b6c6c6e5e))

### Features

- upload results and stdout in parallel ([4e7e165](https://github.com/currents-dev/currents-playwright/commit/4e7e1657e6a3be03ab697e24b28f2d8e3966dbfe))
- upload results in 1 requests ([93053d1](https://github.com/currents-dev/currents-playwright/commit/93053d19ca6d3391a7df11c29b7edc8e0745d751))

## [0.2.2](https://github.com/currents-dev/currents-playwright/compare/0.2.0...0.2.2) (2023-01-31)

### Bug Fixes

- skip uploading results for errors ([dd0d3a8](https://github.com/currents-dev/currents-playwright/commit/dd0d3a8122f66b305cb94341b35515eac84e5033))

# [0.2.0](https://github.com/currents-dev/currents-playwright/compare/0.1.1...0.2.0) (2023-01-31)

### Bug Fixes

- fix counting repeated tests and their status ([f24694a](https://github.com/currents-dev/currents-playwright/commit/f24694a4d961dd655af4938bcbed45c97ae8a5dd))

### Features

- add http errors handlers ([044a93f](https://github.com/currents-dev/currents-playwright/commit/044a93f93c3c351c69abe220c1596ecf762840a0))
- create instances in advance ([830064b](https://github.com/currents-dev/currents-playwright/commit/830064bb7d501162d26da2bc03b61f36d5d30de2))
- upload results in parallel ([b6f3179](https://github.com/currents-dev/currents-playwright/commit/b6f3179db2dfe4a3d8ce61cbceffae892275dfc2))

## [0.1.1](https://github.com/currents-dev/currents-playwright/compare/0.1.0...0.1.1) (2023-01-26)

# [0.1.0](https://github.com/currents-dev/currents-playwright/compare/f50c00cd0eff6c10728daae8577a1e80d35c5c34...0.1.0) (2023-01-26)

### Bug Fixes

- "skipped" > "pending". Closes [#28](https://github.com/currents-dev/currents-playwright/issues/28) ([96611fe](https://github.com/currents-dev/currents-playwright/commit/96611feab062329e6394acb3ac5fb17c3d0576f2))
- various fixes from local testing ([ace1782](https://github.com/currents-dev/currents-playwright/commit/ace1782a0030203ccbd818b68dc9a3e7fbf06299))

### Features

- add basic Playwright reporter ([f50c00c](https://github.com/currents-dev/currents-playwright/commit/f50c00cd0eff6c10728daae8577a1e80d35c5c34))
- create run on onBegin ([a30c33c](https://github.com/currents-dev/currents-playwright/commit/a30c33c62425920c424551a85d7f966866178dc7))
- get git info in test reporter ([845c83d](https://github.com/currents-dev/currents-playwright/commit/845c83dcb4fb4a5d9a8f740026d1fdddede9f06b))
- make initial setup call from Playwright ([ac5083b](https://github.com/currents-dev/currents-playwright/commit/ac5083bb3c1d585293d090fc6475eb173373ecab))
- sent version headers with network requests ([3ad1896](https://github.com/currents-dev/currents-playwright/commit/3ad1896c239c944ed657a471eeb6e07ea80b762e))

# [0.4.0](https://github.com/currents-dev/currents-playwright/compare/0.3.8-beta.0...0.4.0) (2023-05-05)

### Bug Fixes

- allow debugging extensions ([17b5a5f](https://github.com/currents-dev/currents-playwright/commit/17b5a5f0047df8b4fa610b07d47a88a71be34a7d))
- send ciBuildId when creating a run ([d47a2c1](https://github.com/currents-dev/currents-playwright/commit/d47a2c176b308e842eaf67439679354cee82a073))
- show upload warnings at the end of execution ([63c91f3](https://github.com/currents-dev/currents-playwright/commit/63c91f33cc253ef432236e1664a644df40d4a5c1))
- upload stdout and artifacts in parallel ([10a0d2d](https://github.com/currents-dev/currents-playwright/commit/10a0d2d891a1a0c71dccfb7842a37089e26b5647))
- use debug extensions ([0512596](https://github.com/currents-dev/currents-playwright/commit/05125960e25fb532824d268c1a46e82682faa163))

### Features

- refactor + stabilize network uploads ([1f945b6](https://github.com/currents-dev/currents-playwright/commit/1f945b6168e601e0f1f48cf1e4bfd64fd0ee3e25))
- refactor + stabilize network uploads ([1b1cbe9](https://github.com/currents-dev/currents-playwright/commit/1b1cbe9cf136efb056299b257e88fba31fdb2a68))

## [0.3.8-beta.0](https://github.com/currents-dev/currents-playwright/compare/0.3.7...0.3.8-beta.0) (2023-04-20)

### Bug Fixes

- use network retries, enhance debugging ([f996250](https://github.com/currents-dev/currents-playwright/commit/f996250a3b52ade75e0a676c31d50153c2c12b8b))

## [0.3.7](https://github.com/currents-dev/currents-playwright/compare/0.3.6...0.3.7) (2023-04-11)

### Bug Fixes

- send raw results for troubleshooting ([712cf7e](https://github.com/currents-dev/currents-playwright/commit/712cf7e0865ea3fc7488aa8fb01c0fde8db8fde6))

## [0.3.6](https://github.com/currents-dev/currents-playwright/compare/0.3.5...0.3.6) (2023-04-10)

### Bug Fixes

- handle expected vs actual tests status ([6d3c5cb](https://github.com/currents-dev/currents-playwright/commit/6d3c5cb18d1cad94f856eb37fa10cacf0d13ac89))

## [0.3.5](https://github.com/currents-dev/currents-playwright/compare/0.3.4...0.3.5) (2023-03-31)

### Bug Fixes

- use execa to support windows ([b20b746](https://github.com/currents-dev/currents-playwright/commit/b20b746c08f04f8d714d4d39eae49c86387ffc8f))

## [0.3.4](https://github.com/currents-dev/currents-playwright/compare/0.3.3...0.3.4) (2023-02-20)

### Bug Fixes

- wait for flaky test to complete ([95fffef](https://github.com/currents-dev/currents-playwright/commit/95fffef93522391ad665e14841a976fe61da747e))

## [0.3.3](https://github.com/currents-dev/currents-playwright/compare/0.3.2...0.3.3) (2023-02-08)

## [0.3.2](https://github.com/currents-dev/currents-playwright/compare/0.3.1...0.3.2) (2023-02-08)

### Bug Fixes

- handle empty results ([ac09874](https://github.com/currents-dev/currents-playwright/commit/ac098748be6cf135c829b9e3694e19f87ea120ae))

## [0.3.1](https://github.com/currents-dev/currents-playwright/compare/0.3.0...0.3.1) (2023-02-06)

### Bug Fixes

- remove requiring pw+pwc version ([9481736](https://github.com/currents-dev/currents-playwright/commit/9481736139dc96a781bd8103d9fac8651c422b92))

# [0.3.0](https://github.com/currents-dev/currents-playwright/compare/0.2.2...0.3.0) (2023-02-06)

### Bug Fixes

- exist with pw's exit status ([983bb0c](https://github.com/currents-dev/currents-playwright/commit/983bb0c3aece981c6c28fd2f36b2fdef63320d20))
- handle expired run case ([5d008cf](https://github.com/currents-dev/currents-playwright/commit/5d008cfc881c70d5c6471c5032654cabcee14606))
- use claimedCount > 1 ([ee40f1e](https://github.com/currents-dev/currents-playwright/commit/ee40f1e01ff9f17468a1cb975a45456ca3fe8ba0))
- use dedicated pw stdout endpoint ([62f4a48](https://github.com/currents-dev/currents-playwright/commit/62f4a481cbef8e93d1a500942d5df84cca9379dd))
- use PR ref for clear message ([3c7e6a6](https://github.com/currents-dev/currents-playwright/commit/3c7e6a671d4eb8dd6883f0c86e93db3b6c6c6e5e))

### Features

- upload results and stdout in parallel ([4e7e165](https://github.com/currents-dev/currents-playwright/commit/4e7e1657e6a3be03ab697e24b28f2d8e3966dbfe))
- upload results in 1 requests ([93053d1](https://github.com/currents-dev/currents-playwright/commit/93053d19ca6d3391a7df11c29b7edc8e0745d751))

## [0.2.2](https://github.com/currents-dev/currents-playwright/compare/0.2.0...0.2.2) (2023-01-31)

### Bug Fixes

- skip uploading results for errors ([dd0d3a8](https://github.com/currents-dev/currents-playwright/commit/dd0d3a8122f66b305cb94341b35515eac84e5033))

# [0.2.0](https://github.com/currents-dev/currents-playwright/compare/0.1.1...0.2.0) (2023-01-31)

### Bug Fixes

- fix counting repeated tests and their status ([f24694a](https://github.com/currents-dev/currents-playwright/commit/f24694a4d961dd655af4938bcbed45c97ae8a5dd))

### Features

- add http errors handlers ([044a93f](https://github.com/currents-dev/currents-playwright/commit/044a93f93c3c351c69abe220c1596ecf762840a0))
- create instances in advance ([830064b](https://github.com/currents-dev/currents-playwright/commit/830064bb7d501162d26da2bc03b61f36d5d30de2))
- upload results in parallel ([b6f3179](https://github.com/currents-dev/currents-playwright/commit/b6f3179db2dfe4a3d8ce61cbceffae892275dfc2))

## [0.1.1](https://github.com/currents-dev/currents-playwright/compare/0.1.0...0.1.1) (2023-01-26)

# [0.1.0](https://github.com/currents-dev/currents-playwright/compare/f50c00cd0eff6c10728daae8577a1e80d35c5c34...0.1.0) (2023-01-26)

### Bug Fixes

- "skipped" > "pending". Closes [#28](https://github.com/currents-dev/currents-playwright/issues/28) ([96611fe](https://github.com/currents-dev/currents-playwright/commit/96611feab062329e6394acb3ac5fb17c3d0576f2))
- various fixes from local testing ([ace1782](https://github.com/currents-dev/currents-playwright/commit/ace1782a0030203ccbd818b68dc9a3e7fbf06299))

### Features

- add basic Playwright reporter ([f50c00c](https://github.com/currents-dev/currents-playwright/commit/f50c00cd0eff6c10728daae8577a1e80d35c5c34))
- create run on onBegin ([a30c33c](https://github.com/currents-dev/currents-playwright/commit/a30c33c62425920c424551a85d7f966866178dc7))
- get git info in test reporter ([845c83d](https://github.com/currents-dev/currents-playwright/commit/845c83dcb4fb4a5d9a8f740026d1fdddede9f06b))
- make initial setup call from Playwright ([ac5083b](https://github.com/currents-dev/currents-playwright/commit/ac5083bb3c1d585293d090fc6475eb173373ecab))
- sent version headers with network requests ([3ad1896](https://github.com/currents-dev/currents-playwright/commit/3ad1896c239c944ed657a471eeb6e07ea80b762e))

# [0.4.0](https://github.com/currents-dev/currents-playwright/compare/0.3.8-beta.0...0.4.0) (2023-05-05)

### Bug Fixes

- allow debugging extensions ([17b5a5f](https://github.com/currents-dev/currents-playwright/commit/17b5a5f0047df8b4fa610b07d47a88a71be34a7d))
- send ciBuildId when creating a run ([d47a2c1](https://github.com/currents-dev/currents-playwright/commit/d47a2c176b308e842eaf67439679354cee82a073))
- show upload warnings at the end of execution ([63c91f3](https://github.com/currents-dev/currents-playwright/commit/63c91f33cc253ef432236e1664a644df40d4a5c1))
- upload stdout and artifacts in parallel ([10a0d2d](https://github.com/currents-dev/currents-playwright/commit/10a0d2d891a1a0c71dccfb7842a37089e26b5647))
- use debug extensions ([0512596](https://github.com/currents-dev/currents-playwright/commit/05125960e25fb532824d268c1a46e82682faa163))

### Features

- refactor + stabilize network uploads ([1f945b6](https://github.com/currents-dev/currents-playwright/commit/1f945b6168e601e0f1f48cf1e4bfd64fd0ee3e25))
- refactor + stabilize network uploads ([1b1cbe9](https://github.com/currents-dev/currents-playwright/commit/1b1cbe9cf136efb056299b257e88fba31fdb2a68))

## [0.3.8-beta.0](https://github.com/currents-dev/currents-playwright/compare/0.3.7...0.3.8-beta.0) (2023-04-20)

### Bug Fixes

- use network retries, enhance debugging ([f996250](https://github.com/currents-dev/currents-playwright/commit/f996250a3b52ade75e0a676c31d50153c2c12b8b))

## [0.3.7](https://github.com/currents-dev/currents-playwright/compare/0.3.6...0.3.7) (2023-04-11)

### Bug Fixes

- send raw results for troubleshooting ([712cf7e](https://github.com/currents-dev/currents-playwright/commit/712cf7e0865ea3fc7488aa8fb01c0fde8db8fde6))

## [0.3.6](https://github.com/currents-dev/currents-playwright/compare/0.3.5...0.3.6) (2023-04-10)

### Bug Fixes

- handle expected vs actual tests status ([6d3c5cb](https://github.com/currents-dev/currents-playwright/commit/6d3c5cb18d1cad94f856eb37fa10cacf0d13ac89))

## [0.3.5](https://github.com/currents-dev/currents-playwright/compare/0.3.4...0.3.5) (2023-03-31)

### Bug Fixes

- use execa to support windows ([b20b746](https://github.com/currents-dev/currents-playwright/commit/b20b746c08f04f8d714d4d39eae49c86387ffc8f))

## [0.3.4](https://github.com/currents-dev/currents-playwright/compare/0.3.3...0.3.4) (2023-02-20)

### Bug Fixes

- wait for flaky test to complete ([95fffef](https://github.com/currents-dev/currents-playwright/commit/95fffef93522391ad665e14841a976fe61da747e))
- use relative files location https://github.com/currents-dev/currents-playwright/pull/72
- add CI git and build info https://github.com/currents-dev/currents-playwright/pull/71

## [0.3.3](https://github.com/currents-dev/currents-playwright/compare/0.3.2...0.3.3) (2023-02-08)

## [0.3.2](https://github.com/currents-dev/currents-playwright/compare/0.3.1...0.3.2) (2023-02-08)

### Bug Fixes

- handle empty results ([ac09874](https://github.com/currents-dev/currents-playwright/commit/ac098748be6cf135c829b9e3694e19f87ea120ae))

## [0.3.1](https://github.com/currents-dev/currents-playwright/compare/0.3.0...0.3.1) (2023-02-06)

### Bug Fixes

- remove requiring pw+pwc version ([9481736](https://github.com/currents-dev/currents-playwright/commit/9481736139dc96a781bd8103d9fac8651c422b92))

## [0.3.0](https://github.com/currents-dev/currents-playwright/compare/0.2.2...0.3.0) (2023-02-06)

### Bug Fixes

- exit with pw's exit status ([983bb0c](https://github.com/currents-dev/currents-playwright/commit/983bb0c3aece981c6c28fd2f36b2fdef63320d20))
- handle expired run case ([5d008cf](https://github.com/currents-dev/currents-playwright/commit/5d008cfc881c70d5c6471c5032654cabcee14606))
- use claimedCount > 1 ([ee40f1e](https://github.com/currents-dev/currents-playwright/commit/ee40f1e01ff9f17468a1cb975a45456ca3fe8ba0))
- use dedicated pw stdout endpoint ([62f4a48](https://github.com/currents-dev/currents-playwright/commit/62f4a481cbef8e93d1a500942d5df84cca9379dd))
- use PR ref for clear message ([3c7e6a6](https://github.com/currents-dev/currents-playwright/commit/3c7e6a671d4eb8dd6883f0c86e93db3b6c6c6e5e))

### Features

- upload results and stdout in parallel ([4e7e165](https://github.com/currents-dev/currents-playwright/commit/4e7e1657e6a3be03ab697e24b28f2d8e3966dbfe))
- upload results in 1 requests ([93053d1](https://github.com/currents-dev/currents-playwright/commit/93053d19ca6d3391a7df11c29b7edc8e0745d751))

## [0.2.2](https://github.com/currents-dev/currents-playwright/compare/0.2.0...0.2.2) (2023-01-31)

### Bug Fixes

- skip uploading results for errors ([dd0d3a8](https://github.com/currents-dev/currents-playwright/commit/dd0d3a8122f66b305cb94341b35515eac84e5033))

## [0.2.1](https://github.com/currents-dev/currents-playwright/compare/0.2.0...0.2.1) (2023-01-31)

## [0.2.0](https://github.com/currents-dev/currents-playwright/compare/0.1.1...0.2.0) (2023-01-31)

### Bug Fixes

- fix counting repeated tests and their status ([f24694a](https://github.com/currents-dev/currents-playwright/commit/f24694a4d961dd655af4938bcbed45c97ae8a5dd))

### Features

- add http errors handlers ([044a93f](https://github.com/currents-dev/currents-playwright/commit/044a93f93c3c351c69abe220c1596ecf762840a0))
- create instances in advance ([830064b](https://github.com/currents-dev/currents-playwright/commit/830064bb7d501162d26da2bc03b61f36d5d30de2))
- upload results in parallel ([b6f3179](https://github.com/currents-dev/currents-playwright/commit/b6f3179db2dfe4a3d8ce61cbceffae892275dfc2))

## [0.1.1](https://github.com/currents-dev/currents-playwright/compare/0.1.0...0.1.1) (2023-01-26)

## 0.1.0 (2023-01-26)

### Bug Fixes

- "skipped" > "pending". Closes [#28](https://github.com/currents-dev/currents-playwright/issues/28) ([96611fe](https://github.com/currents-dev/currents-playwright/commit/96611feab062329e6394acb3ac5fb17c3d0576f2))
- various fixes from local testing ([ace1782](https://github.com/currents-dev/currents-playwright/commit/ace1782a0030203ccbd818b68dc9a3e7fbf06299))

### Features

- add basic Playwright reporter ([f50c00c](https://github.com/currents-dev/currents-playwright/commit/f50c00cd0eff6c10728daae8577a1e80d35c5c34))
- create run on onBegin ([a30c33c](https://github.com/currents-dev/currents-playwright/commit/a30c33c62425920c424551a85d7f966866178dc7))
- get git info in test reporter ([845c83d](https://github.com/currents-dev/currents-playwright/commit/845c83dcb4fb4a5d9a8f740026d1fdddede9f06b))
- make initial setup call from Playwright ([ac5083b](https://github.com/currents-dev/currents-playwright/commit/ac5083bb3c1d585293d090fc6475eb173373ecab))
- sent version headers with network requests ([3ad1896](https://github.com/currents-dev/currents-playwright/commit/3ad1896c239c944ed657a471eeb6e07ea80b762e))
