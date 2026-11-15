# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.21] - 2026-11-15

### Added

- Add support for list of trusted entitites (#180)
- Add support for presenting several credential types (#159)
- Add script to download latest OpenAPI schema (#155)
- Add support for DPoP authorization (#141)
- Add CODEOWNERS (#121)
- Add SonarQube analysis with JaCoCo coverage reporting (#115)
- Add JaCoCo code coverage with GitHub Pages publishing (#114)
- Add database migration (#107)
- Add selective disclosure support (#85)
- Add script that pushes CA cert to emulator (#82)
- Add support for SD-JWT parsing (#75)
- Add kotlinter and .editorconfig (#54)
- Support new issuer and updated onboarding flow (#53)
- Added prebuild task for fabriktGenerate (#49)
- Add onboarding flow (#48)
- Add missing license headers
- Add release dev flow, play store (internal)
- Add descriptionLength
- Add fixes to make dev ci pass
- Add reuseable ci
- Add pr workflow and test
- Add openssf scorecard
- Add initial build workflow
- Add initial build workflow
- Add initial build workflow

### Changed

- Use the lab's Forge CI layer
- Name the snapshot and release flows as the other projects do
- Name the snapshot flow release-snapshot-workflow.yml
- Name the extra test workflows test-<kind>.yml
- Ask for the build SBOM only
- Let the build logic fetch its Java 17 toolchain
- Report SAST findings without failing the pull request
- Request a release with a release-request tag
- Migrate workflows to forge-ci
- Issuance module (#204)
- Presentation module (#203)
- Appsetup module (#202)
- Settings module (#201)
- Qrscanner module (#200)
- Credentialdetail module (#199)
- Dashboard module (#198)
- Update gradle non-major (#197)
- Move trust files to trust module (#196)
- Bump gradle and navigation3 libs (#195)
- Data module (#194)
- Assorted fixes from launchpad 2026
- Webauth module (#193)
- Trust module (#191)
- Setup crypto module (#190)
- Gradle and libs bumps (#189)
- Network module (#188)
- App module cleanup (#186)
- Database module (#185)
- Model modularization (#184)
- Update dependency ch.acanda.gradle.fabrikt to v1.44.0 (#182)
- Navigation module under core (#181)
- Build logic setup (#178)
- Fix/hsm e2e proof signer (#179)
- Chore/clean up (#173)
- Update gradle non-major (#176)
- Update kotlin to v2.4.21 (#175)
- Client-configs endpoint does not require a session (#174)
- Bump reusable-ci to dc5d899 for setup-android v4 (#172)
- Bump reusable to v3.0.0 (#171)
- Bump versionName to 0.0.20 (was 0.0.1) (#170)
- Feat/qr (#167)
- Feat/key attestation (#169)
- Test/hsm e2e (#166)
- Vp, vci and others bumped (#165)
- Version bump to libraries (#164)
- Extract issuance logic into IssuanceService (#161)
- Extract shared HSM proof signing (#160)
- Feat/render pid image (#154)
- Update gradle non-major (#157)
- Update androidx to v1.1.7 (#156)
- Header device info (#152)
- Settings improved (#151)
- Improved error handling (#148)
- Update dependency com.google.devtools.ksp to v2.3.11 (#136)
- Request ACCESS_LOCAL_NETWORK in local build variant (#147)
- Bump openid4vci to 0.13.1 and openid4vp to 0.15.1 (#146)
- Feat/build variant (#143)
- Bump targetSdk to 37 (#145)
- Update to multiple libs versions (#139)
- Bump agp and gradle (#138)
- Update dependency androidx.compose:compose-bom to v2026.06.01 (#135)
- Update androidx (#124)
- Feat/access mechanism (#131)
- Update gradle non-major (#123)
- Chore/remove sonarqube (#119)
- Update gradle non-major (#112)
- Update step-security/harden-runner action to v2.19.1 (#113)
- Bump reusable-ci to v2.8.2
- Update step-security/harden-runner action to v2.19.0 (#110)
- Update kotlin to v2.3.21 (#109)
- Update gradle non-major (#108)
- Cleanup resources and update dependencies (#106)
- Update step-security/harden-runner action to v2.18.0 (#103)
- Optional key attestation (#102)
- Update dependencies (#101)
- Update dashboard design (#100)
- Update step-security/harden-runner action to v2.17.0 (#99)
- Migrate to gradle daemon jvm (#95)
- Use reusable ci 2.7.9 (#94)
- Update gradle non-major (#74)
- Update step-security/harden-runner action to v2.16.1 (#89)
- Upgrade to reusable-ci 2.7.7 (#91)
- Update dependency androidx.browser:browser to v1.10.0 (#90)
- Update dependency androidx.compose:compose-bom to v2026.03.01 (#88)
- Update step-security/harden-runner action to v2.16.0 (#87)
- Update kotlin to v2.3.20 (#86)
- Upgrade to reusable-ci 2.7.3
- Update dependency androidx.compose:compose-bom to v2026.03.00 (#81)
- Update androidx (#80)
- Use reusable-ci 2.7.0
- Bump reusable-ci workflow versions to 2.6.2 (was 2.6.0) (#76)
- Update github actions (#73)
- Update step-security/harden-runner action to v2.15.0 (#72)
- Update dependency ch.acanda.gradle.fabrikt to v1.30.0 (#71)
- Update dependency androidx.compose:compose-bom to v2026.02.01 (#70)
- Oauth browser fallback (#69)
- Update gradle non-major (#61)
- Update step-security/harden-runner action to v2.14.2 (#57)
- Configure reuse and apply annotations to source code (#60)
- Compute versionCode automatically (#67)
- Try to fetch credential offer automatically (#68)
- Local buildvariant (#65)
- Onboarding intro screen fixes (#63)
- Wua v3 (#59)
- Upgrade Android Gradle Plugin to 9.0 (#55)
- Update kotlin to v2.2.21 (#46)
- Update github actions (#44)
- Use reuseable ci 2.6.0
- Update justfile and reuseable-ci
- Pin sha and version
- Use base renovate
- Schedule openssf scorecard
- Updated vci flow
- Openid4vp and presentation of data
- Updated gitignore to ignore .aab files.
- Set versionname and added applicationidsuffix
- New project created.
- Initial commit. Added readme and basic gitignore.

### Fixed

- Drop the blank line the trial edit left
- Keep the placeholder secrets file in the test job
- State the licence of the placeholder secrets file
- Build without the signing key, the store and the API keys
- Improve issuance retry handling (#162)
- Manifest cleanup (#153)
- String fix, libs bump, permission fix, haip-vp (#149)
- Use verifiers prefix+clientId as audience (#144)
- Clear device key on incomplete onboarding (#140)
- Align bcutil/bcpkix with bcprov to fix build (#134)
- Bump access-mechanism to 0.0.2-SNAPSHOT and pin bcprov to patched version (#133)
- Create account fix (#132)
- Android workflow refactor repair
- Ux fixes (#83)
- Allow any signed format
- Update to the accounts client (#66)
- VersionCode bump to 8 (#52)
- Bumped openid4vp library and changed to support directpost (#51)
- Onboarding and fetching of wua added
- Bumped versioncode, compilesdk and loads of libraries.
- Updated icons
- Updated navigation from dashboard to detailview, fixed dashboard card, fixed label textoverflow in issuanceflow.
- Ui fixes for presentation, issuance and dashboard.
- Updated urls for buttons on dashboard, added support for openid4vp scheme.
- Changed configuration to work with our issuer
- Prepared fixes for using own issuer.
- Return all disclosures when DCQL query is null
- Key binding in presentation flow
- Presentation fixes, stuck on vptoken verification
- Fetch pid improvement

### Removed

- Remove random delay from wallet setup (#177)
- Remove external link (#142)
- Remove paranoid from local mise config (#137)
- Remove wua/v3 (#64)
- Remove usage of v2/wua endpoint (#56)


<!-- generated by git-cliff -->
