# Changelog

All notable changes to this package are documented here. Releases are managed
from conventional commits by the repository release workflow.

## 1.0.0 (2026-07-27)

### ✨ Features ✨

- **shared:** add agnostic standards payload ([2d65acb](https://github.com/AtomiCloud/diene.dart_e2e/commit/2d65acb118ebcc797cca0f13b0d9e979e7a8c29c))
- **probes:** add nix root suite ([27e4184](https://github.com/AtomiCloud/diene.dart_e2e/commit/27e41843f06e38cfcc26a516c05f4ae4fb294ac0))
- **dart-lib:** add pure-Dart publishable library template package ([47a4837](https://github.com/AtomiCloud/diene.dart_e2e/commit/47a4837f54f7ad0342a4539ff1320c4f94d7df71))
- **probes:** add shared authoring helpers ([f20d53f](https://github.com/AtomiCloud/diene.dart_e2e/commit/f20d53f805564fe21e0ee32084fc49f2973a50e4))
- materialize atomi/nix sample (yes_basic_yes_llm) as chain root ([24105ef](https://github.com/AtomiCloud/diene.dart_e2e/commit/24105ef4948ff884353011be24b915f69c7c8382))
- materialize workspace spine baseline ([f74cf31](https://github.com/AtomiCloud/diene.dart_e2e/commit/f74cf3179989e12f662b1c98061aeb2d4803f563))
- **shared-wo-docker:** remove Docker axis ([b125b74](https://github.com/AtomiCloud/diene.dart_e2e/commit/b125b74a556f5b5f5d82ef973a79c80079c5b63e))
- **shared-wo-docker-helm:** remove Helm axis ([e01fe36](https://github.com/AtomiCloud/diene.dart_e2e/commit/e01fe368b9fe30bee238c809a58444c9170998f2))
- **dart-e2e:** ship a runnable example, prove it runs in the meta tier ([65c9777](https://github.com/AtomiCloud/diene.dart_e2e/commit/65c9777763a038c57d215015722cefc9215b6056))
- **dart-e2e:** transplant diene_e2e onto dart-lib, wire version train ([923157c](https://github.com/AtomiCloud/diene.dart_e2e/commit/923157cd9931c77b1e15ff486554392a8d99027f)), closes [#26](https://github.com/AtomiCloud/diene.dart_e2e/issues/26)
- **dart-lib:** wire Dart CI, release, and OIDC publish machinery ([770b8ec](https://github.com/AtomiCloud/diene.dart_e2e/commit/770b8ec512e44ccfb0495daebbcad081a65344c5))

### 🐛 Bug Fixes 🐛

- **probes:** attribute actionlint smoke overlap ([bfb0271](https://github.com/AtomiCloud/diene.dart_e2e/commit/bfb02717d6eca8c86f617efe50286008da328fe1))
- **nix:** check precommit from repository root ([c6046ac](https://github.com/AtomiCloud/diene.dart_e2e/commit/c6046ac3d877f2fed40073ff333fe2b877b778a8))
- **nix:** enforce root formatter probes ([3b4188a](https://github.com/AtomiCloud/diene.dart_e2e/commit/3b4188aa9797c14f10fb448e68cdeefeb9ae231e))
- **probes:** isolate cross-template mutations ([f8169d0](https://github.com/AtomiCloud/diene.dart_e2e/commit/f8169d002a3db773f638a01a280c0170781164f5))
- **dart-lib:** make the released changelog formatter-clean at generation ([#121](https://github.com/AtomiCloud/diene.dart_e2e/issues/121)) ([59a812b](https://github.com/AtomiCloud/diene.dart_e2e/commit/59a812bf5b78e986dee16c47e4da90f18b20bd7c))
- **dart-lib:** preserve nested C0 result files ([#126](https://github.com/AtomiCloud/diene.dart_e2e/issues/126)) ([602610f](https://github.com/AtomiCloud/diene.dart_e2e/commit/602610fd452430fd7e8a3cdd396cfd0b0f8235ee))
- **dart-e2e:** set per-node gate values, close both coverage residues ([5d5369a](https://github.com/AtomiCloud/diene.dart_e2e/commit/5d5369a04a9d0884e5cae97022b222fef398ea80))
- **dart-e2e:** untrack and ignore the generated flutter plugin manifest ([e707ee6](https://github.com/AtomiCloud/diene.dart_e2e/commit/e707ee6cdcafa1da221b4d8c01016f1d30597cb3))
- **dart-lib:** use credentialed pub.dev publishing ([#107](https://github.com/AtomiCloud/diene.dart_e2e/issues/107)) ([796d025](https://github.com/AtomiCloud/diene.dart_e2e/commit/796d0252fa94b14e2ec418fd9c70e3f75e792813))

### 🧪 Tests 🧪

- **dart-lib:** add TEMPLATE-ONLY CyanPrint probe matrix ([6a1f748](https://github.com/AtomiCloud/diene.dart_e2e/commit/6a1f748e2960ae7cd07d768eec81bdbbd68c0ed7))
- **dart-lib:** fix dead-code and credential-policy mutation sabotages ([f1737e9](https://github.com/AtomiCloud/diene.dart_e2e/commit/f1737e95d097716c53139fe2b64822dddb71aa6b))
- **dart-lib:** fix deadcode-whole-package sabotage target ([226e3d2](https://github.com/AtomiCloud/diene.dart_e2e/commit/226e3d2de16ff2ce5b206f434e12fcac9fd79354))
- **dart-lib:** fix probe baselines for gitlint hook and pana ([1519f9a](https://github.com/AtomiCloud/diene.dart_e2e/commit/1519f9a4939ab0811cac827e1c36d2eaa2da1d05))
- **dart-lib:** restore workspace deps for skills-freshness sandbox ([9a2e5bf](https://github.com/AtomiCloud/diene.dart_e2e/commit/9a2e5bffc1e4ff36d259c1abc2b5021a7b7bca87))

## 0.0.0

- Establish the pure-Dart library template: workspace-member package metadata,
  strict analysis options, and pub.dev publish hygiene.
- Add the replaceable `Note` sample: an immutable value type with a JSON wire
  codec and the pure `summarizeNote` transform, exported from the barrel.
- Add the dependency-light `assertNoteSummary` TestHelper and its meta suite.
- Add the C0 fixture harness with a SHA-256 digest manifest and a
  decode/encode/decode round trip.
