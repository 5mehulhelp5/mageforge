# Changelog for MageForge

All notable changes to this project will be documented in this file.

---

## UNRELEASED

### Changed

* **Inspector CSS Migration**: Migrated Inspector component from Tailwind CSS to pure Vanilla CSS for universal compatibility
  - All CSS classes now use `mageforge-*` prefix for namespace isolation
  - Removed Tailwind build dependency (`tailwind/` directory deprecated)
  - No npm build step required - direct CSS editing
  - Compatible with all Magento 2 projects regardless of frontend stack
  - Inspector CSS location: `src/view/frontend/web/css/inspector.css`

## Latest Release

## [0.13.0](https://github.com/5mehulhelp5/mageforge/compare/0.12.0...0.13.0) (2026-02-17)


### ⚠ BREAKING CHANGES

* create theme:clean command for cleaning theme static files and cache, remove old mageforge:static:clean command ([#80](https://github.com/5mehulhelp5/mageforge/issues/80))

### Added

* :sparkles: add HelloMageForgeCommand ([a911143](https://github.com/5mehulhelp5/mageforge/commit/a9111431bc25f7b9bfd13f3a6b591250cf43c433))
* :sparkles: add version command ([#16](https://github.com/5mehulhelp5/mageforge/issues/16)) ([7dbb577](https://github.com/5mehulhelp5/mageforge/commit/7dbb5771e37b9dee36d888d96feb1ea0339bbd9b))
* ✨ add dependabot ([#11](https://github.com/5mehulhelp5/mageforge/issues/11)) ([12537a7](https://github.com/5mehulhelp5/mageforge/commit/12537a7b7eb4af69fb0cf8b9840c4dd8084e1b52))
* ✨ add HelloMageForgeCommand ([ada1b66](https://github.com/5mehulhelp5/mageforge/commit/ada1b662d9ddc80570c9586515d49a57819bd5ab))
* ✨ add phpcs ([#10](https://github.com/5mehulhelp5/mageforge/issues/10)) ([51d0841](https://github.com/5mehulhelp5/mageforge/commit/51d08412bd1530e6d59b49f6a35e3f2b939eef72))
* **actions:** replace elasticsearch with opensearch ([#137](https://github.com/5mehulhelp5/mageforge/issues/137)) ([cc8c534](https://github.com/5mehulhelp5/mageforge/commit/cc8c53428288a45b8ad645baf87623bf4a8b9a1f))
* add alias for BuildThemeCommand to improve command usability ([f522fa7](https://github.com/5mehulhelp5/mageforge/commit/f522fa74dc5a7b430f2a3a41919e8f1c9d3d7367))
* add autoRepair method to ensure node_modules are installed for Hyvä themes ([79901e1](https://github.com/5mehulhelp5/mageforge/commit/79901e16c2c1da792ef46fa8f962a61d4e4a17cf))
* add cache and webvitals tabs to inspector and improve ux with dragable overlay ([#127](https://github.com/5mehulhelp5/mageforge/issues/127)) ([eea755d](https://github.com/5mehulhelp5/mageforge/commit/eea755d1b38fe9e736a49157192babc5b98fbb10))
* add CacheCleaner service and autoRepair method to BuilderInterface for improved theme setup ([df5fc6a](https://github.com/5mehulhelp5/mageforge/commit/df5fc6ac283d020b0de45bb49dde51b360679a73))
* add CliTest command for CLI testing and update SystemCheckCommand name ([979b864](https://github.com/5mehulhelp5/mageforge/commit/979b864bd1559c4a52ebd801ca3bad16402f3418))
* add compatibility check for PHP 8.4 and Magento 2.4.8 with OpenSearch ([0516606](https://github.com/5mehulhelp5/mageforge/commit/051660685b664ffa0a9bc492f8f9a20917ff8d2f))
* add comprehensive documentation for MageForge commands and custom ThemeBuilders ([1c59d9b](https://github.com/5mehulhelp5/mageforge/commit/1c59d9b8eb28cf10121e7e8f8c98c1ff87cca4d1))
* add context7 configuration file with URL and public key ([977bee0](https://github.com/5mehulhelp5/mageforge/commit/977bee0d2b2c4301bd2764b07ef82eefb92e29fb))
* add error handling and success message for npm install in CliTest command ([8d9c693](https://github.com/5mehulhelp5/mageforge/commit/8d9c693e733406e73a2ffbcff122b00245d13814))
* add functional-tests badge to readme.md ([#95](https://github.com/5mehulhelp5/mageforge/issues/95)) ([7108ef0](https://github.com/5mehulhelp5/mageforge/commit/7108ef0d4408b82f3010acaa00cf6f257880809d))
* add GruntTaskRunner and StaticContentDeployer services; implement DependencyChecker for theme build validation ([b81ed47](https://github.com/5mehulhelp5/mageforge/commit/b81ed47ed8249c77677745272868fc209003bf2a))
* add Hyvä theme detection logic and refactor constructor ([1227a84](https://github.com/5mehulhelp5/mageforge/commit/1227a84f65d873081b43b2c8ed6e3a78523ae8c4))
* add laravel/prompts dependency to composer.json ([dbcde5f](https://github.com/5mehulhelp5/mageforge/commit/dbcde5fa060cb7584808ec7708059bffbd3a4729))
* add Magento compatibility tests workflow ([#35](https://github.com/5mehulhelp5/mageforge/issues/35)) ([ff04dc0](https://github.com/5mehulhelp5/mageforge/commit/ff04dc01b66cf91aace6cabd8a435c75aa5a2ec8))
* add NodePackageManager service for npm dependency management ([#91](https://github.com/5mehulhelp5/mageforge/issues/91)) ([1ab623f](https://github.com/5mehulhelp5/mageforge/commit/1ab623f5d858c272b6f692acb98edd35bf15ed3d))
* add NodeSetupValidator for validating Magento default setup files ([#142](https://github.com/5mehulhelp5/mageforge/issues/142)) ([3f36d43](https://github.com/5mehulhelp5/mageforge/commit/3f36d433a04ac31be0ca84f04cd4495245ecf52e))
* add npm sync validation to NodePackageManager and theme builders ([#93](https://github.com/5mehulhelp5/mageforge/issues/93)) ([5fcbdaf](https://github.com/5mehulhelp5/mageforge/commit/5fcbdaf7ceb19136f4b86fbffd33b44cee1469d6))
* add PHP 8.4 compatibility for Magento 2.4.7-p5 in workflow ([6a3fec8](https://github.com/5mehulhelp5/mageforge/commit/6a3fec86c73ff54d5704b61f9903df166354ea95))
* add phpstan & phpcs ([#96](https://github.com/5mehulhelp5/mageforge/issues/96)) ([06bcfdc](https://github.com/5mehulhelp5/mageforge/commit/06bcfdc82b1a8e0a58ad8712f7a120dc215e850f))
* add pinning functionality for inspector badge ([#104](https://github.com/5mehulhelp5/mageforge/issues/104)) ([69f7328](https://github.com/5mehulhelp5/mageforge/commit/69f73287754b572ea27349fcbb248f351dd7bc0d))
* add spinner for theme building process in BuildThemeCommand ([39236d8](https://github.com/5mehulhelp5/mageforge/commit/39236d8d7827a8c5c75a2c068c2f7b3fc4584700))
* add StaticContentDeployer dependency to BuildThemesCommand for enhanced functionality ([ba30d25](https://github.com/5mehulhelp5/mageforge/commit/ba30d255366fc3a3dd2c1e3968dd8116b36ff6d6))
* add system check commands for Node.js, MySQL, and environment status ([2ced182](https://github.com/5mehulhelp5/mageforge/commit/2ced1824fdcb92d932d7b5384d41c927eb09c8a1))
* add tailwind directory check in HyvaThemeDetector for theme validation ([0ce5883](https://github.com/5mehulhelp5/mageforge/commit/0ce5883db67467654259b0ac0d69e1dd881e3ede))
* add theme building functionality with user selection and summary display ([722ae75](https://github.com/5mehulhelp5/mageforge/commit/722ae7524495619cf05a02b4ffcd75eb703aa630))
* add theme listing and npm commands to CliTest ([bfa08de](https://github.com/5mehulhelp5/mageforge/commit/bfa08de116be53302ae62940c360623022d7ec5c))
* add theme suggestion service and integrate with commands [#75](https://github.com/5mehulhelp5/mageforge/issues/75) ([#76](https://github.com/5mehulhelp5/mageforge/issues/76)) ([1347782](https://github.com/5mehulhelp5/mageforge/commit/13477823e82b81bda5412a7f8d4cbd747254d6c5))
* add ThemeWatchCommand ([b6699fd](https://github.com/5mehulhelp5/mageforge/commit/b6699fd508c35d359b18f61b98e14e9f3b5dc5ad))
* **BuildThemesCommand:** add success summary display for theme build process ([3d4ea4b](https://github.com/5mehulhelp5/mageforge/commit/3d4ea4b85bc6eeee97a4b7dfb52f313cada42d66))
* **BuildThemesCommand:** add theme list display when no theme codes are provided ([e74be85](https://github.com/5mehulhelp5/mageforge/commit/e74be8531b12b01df62151f0db2f20230c1cedaa))
* **BuildThemesCommand:** enhance file verification and setup processes for theme building ([854e87f](https://github.com/5mehulhelp5/mageforge/commit/854e87ff92f53d17dcb4157449702e05fa8696e3))
* **BuildThemesCommand:** refactor file handling and improve error management for theme build processes ([3cc5888](https://github.com/5mehulhelp5/mageforge/commit/3cc5888b10394b2fff8424cff09d52faed5ca0ef))
* dev Inspector Overlay (Frontend) ([#85](https://github.com/5mehulhelp5/mageforge/issues/85)) ([806d04a](https://github.com/5mehulhelp5/mageforge/commit/806d04a252eb70f6f76131a672296d62a7c5372b))
* enhance BuildThemesCommand to support Hyvä theme processing and improve success message grouping ([fbefb9c](https://github.com/5mehulhelp5/mageforge/commit/fbefb9c614b14a0bbb840afcbb426a4a417a02ae))
* enhance CliTest command to check for outdated packages and handle npm install results ([969c999](https://github.com/5mehulhelp5/mageforge/commit/969c999fa7c0ef9f323abaa2bb7064da012ead39))
* enhance inspector with JSON metadata and comment parsing ([#105](https://github.com/5mehulhelp5/mageforge/issues/105)) ([a2f9ebf](https://github.com/5mehulhelp5/mageforge/commit/a2f9ebf4a188e01576d980866c92b7d9e7bf55f1))
* enhance Magento compatibility with PHP 8.4 and update search engine configurations ([7764c70](https://github.com/5mehulhelp5/mageforge/commit/7764c70700eed625240de2de825e1823e95edd3a))
* enhance MySQL and Elasticsearch status checks with improved con… ([#37](https://github.com/5mehulhelp5/mageforge/issues/37)) ([9fa70b7](https://github.com/5mehulhelp5/mageforge/commit/9fa70b7dabd7c34dcabdbcf915fa7d4817f1b524))
* enhance npm installation process with package-lock.json check ([492cfd6](https://github.com/5mehulhelp5/mageforge/commit/492cfd661cf8f97ad4d1dfb6b16df918eeddd44c))
* enhance system check command to display additional environment information ([b03abab](https://github.com/5mehulhelp5/mageforge/commit/b03ababad49349682ff04e22545fc1d45957e9c1))
* enhance terminal compatibility and error handling for theme selection process 🎨 ([#44](https://github.com/5mehulhelp5/mageforge/issues/44)) ([326a6dd](https://github.com/5mehulhelp5/mageforge/commit/326a6dd8065bf8218e2f72e0ebfc7a88226cadde))
* enhance theme command arguments for better clarity and compatib… ([#40](https://github.com/5mehulhelp5/mageforge/issues/40)) ([6a61c5e](https://github.com/5mehulhelp5/mageforge/commit/6a61c5eefd93a41117573a9d23c07d5921b340f9))
* implement abstract command structure for improved command handling ([af0022b](https://github.com/5mehulhelp5/mageforge/commit/af0022b03ca11706e9e8eb841aafe23429620b5f))
* implement dark/light mode theme selection and admin configuration section ([#131](https://github.com/5mehulhelp5/mageforge/issues/131)) ([0a95280](https://github.com/5mehulhelp5/mageforge/commit/0a952808b6a5f7102aa5ad4b874e576d67f77bd1))
* implement HyvaThemeBuilder service and integrate it into BuildThemesCommand for Hyvä theme building ([f4ffc68](https://github.com/5mehulhelp5/mageforge/commit/f4ffc68c2efadb4bf2d9b8911dc73996bf71e4f1))
* implement MultiSelectPrompt for theme selection in BuildThemeCommand ([3a0fa08](https://github.com/5mehulhelp5/mageforge/commit/3a0fa0878d6d4616122f66885a5323021cde732b))
* implement Release Please workflow and update configuration ([d814853](https://github.com/5mehulhelp5/mageforge/commit/d814853c220dd098ad11340ea179ad66f9fb01f7))
* implement StaticContentCleaner and update theme build commands ([#83](https://github.com/5mehulhelp5/mageforge/issues/83)) ([80a6abf](https://github.com/5mehulhelp5/mageforge/commit/80a6abf8b63dfdf25233f884d3fc3c6a2648b05c))
* implement SymlinkCleaner service and integrate into theme builders [#88](https://github.com/5mehulhelp5/mageforge/issues/88) ([#89](https://github.com/5mehulhelp5/mageforge/issues/89)) ([3f40ef6](https://github.com/5mehulhelp5/mageforge/commit/3f40ef64174686fd3c75944d00773ef83515f0f9))
* implement TailwindCSS theme builder and enhance detect method for theme identification ([690baee](https://github.com/5mehulhelp5/mageforge/commit/690baeec0ac1506e89f6d3a9c56c29da7b1936a5))
* implement theme builder architecture with Builder and BuilderPool interfaces ([4521a37](https://github.com/5mehulhelp5/mageforge/commit/4521a375065e976762b6142a423cc7381d773ed9))
* implement theme builder architecture with Builder and BuilderPool interfaces ([c4e143f](https://github.com/5mehulhelp5/mageforge/commit/c4e143f8709ebfff72fbfb18128ac6e79a386bca))
* introduce StandardThemeBuilder for improved theme building process in BuildThemesCommand ([28b2ceb](https://github.com/5mehulhelp5/mageforge/commit/28b2cebf31ae959dae6428b98be23f987fb9b847))
* modify BuildThemesCommand to adjust total steps based on standard theme presence and optimize dependency checks ([1db4487](https://github.com/5mehulhelp5/mageforge/commit/1db4487760731f582776f004de6a8f38df58ee03))
* Node.js/Grunt setup detection for improved build process ([#114](https://github.com/5mehulhelp5/mageforge/issues/114)) ([5330e17](https://github.com/5mehulhelp5/mageforge/commit/5330e1702acc470276bd8c6ea508b0c35ac18a2f))
* reduce cyklomatic complexity ([#39](https://github.com/5mehulhelp5/mageforge/issues/39)) ([caacb69](https://github.com/5mehulhelp5/mageforge/commit/caacb69447b963d1fa427c7cdab1d28617283fcc))
* refactor node module installation and outdated package check in Builder ([07d4423](https://github.com/5mehulhelp5/mageforge/commit/07d4423eaa9ca01e965bee8ec90bd1b9c9d27456))
* rename commands ([f1bd115](https://github.com/5mehulhelp5/mageforge/commit/f1bd115a04370e0b9858bace8585870b0f056370))
* separate functional tests from compatibility tests ([effac26](https://github.com/5mehulhelp5/mageforge/commit/effac2637837efa4814b93bc1b09eb8cef306544))
* systemCheckCommand to display system information and enhance Vers… ([5368e39](https://github.com/5mehulhelp5/mageforge/commit/5368e3953e960c9b47e97d8635eabe015f5e6a28))
* update CliTest command to countdown before running npm outdated ([566f7af](https://github.com/5mehulhelp5/mageforge/commit/566f7aff51d9fb7a49e255f588d854f1e7184ea2))
* update feature request link to direct to new issue template ([7e0b57e](https://github.com/5mehulhelp5/mageforge/commit/7e0b57eb33f927ba307b008af504de42c4a2a5af))
* update Hyva theme detection logic to check composer.json for module dependency ([757edf0](https://github.com/5mehulhelp5/mageforge/commit/757edf0294819081761126567f6699e5de23ba82))
* update Magento compatibility to version 2.4.8 with PHP 8.4 support ([5fdafd5](https://github.com/5mehulhelp5/mageforge/commit/5fdafd564179b9ffd681754be7fbb8f0e41f66f8))
* update Magento compatibility workflow for PHP 8.4 and Elasticsearch integration ([96c9831](https://github.com/5mehulhelp5/mageforge/commit/96c98313058562eb1b16a8e9e519a78498397d9a))
* update phpstan level and add type hints ([#116](https://github.com/5mehulhelp5/mageforge/issues/116)) ([0a4a5fa](https://github.com/5mehulhelp5/mageforge/commit/0a4a5fa45ca77396a87569eca3491b569e3d3539))
* update success and error messages for custom TailwindCSS theme build process ([baa7d4b](https://github.com/5mehulhelp5/mageforge/commit/baa7d4b93b941b713957b307934f95e9abe5d66e))
* update ThemeWatchCommand prompt label and modify TailwindCSS build command for improved usability ([1ca3e40](https://github.com/5mehulhelp5/mageforge/commit/1ca3e40679768d52c98f44da6438917af700b8ac))


### Fixed

* add new lines in BuildThemesCommand output for better readability ([62e251c](https://github.com/5mehulhelp5/mageforge/commit/62e251c255590dbad0517fabdca1e2108e6daa0d))
* adjust command argument order and clean up whitespace ([9c4fb73](https://github.com/5mehulhelp5/mageforge/commit/9c4fb7356d23c38096e798d797fdfcb4ec455ff5))
* **BuildThemesCommand:** ignore coding standards for shell argument sanitization ([0de7e60](https://github.com/5mehulhelp5/mageforge/commit/0de7e602f8cfda3f917adef7917ec76519f63941))
* correct font size and border radius in inspector CSS ([7bb3348](https://github.com/5mehulhelp5/mageforge/commit/7bb334806a134687bd06cf55e5f27682947f3c84))
* correct head-branch regex and add new changed-files sections ([53777ea](https://github.com/5mehulhelp5/mageforge/commit/53777eac19920e4de175b2a52704ff8b0c9982de))
* correct spacing and formatting in multiple files ([#120](https://github.com/5mehulhelp5/mageforge/issues/120)) ([3f9048a](https://github.com/5mehulhelp5/mageforge/commit/3f9048abc0b0f2785aa5be3858704037ad14ce5a))
* create theme:clean command for cleaning theme static files and cache, remove old mageforge:static:clean command ([#80](https://github.com/5mehulhelp5/mageforge/issues/80)) ([ffd5ec8](https://github.com/5mehulhelp5/mageforge/commit/ffd5ec89e87eb8aa3a1f19eb957bd3f95a5c50b1))
* enhance interactive mode for compatibility checks and prompts ([#79](https://github.com/5mehulhelp5/mageforge/issues/79)) ([428a133](https://github.com/5mehulhelp5/mageforge/commit/428a1338479a2ad1642ea7a353d0c73e37ef155b))
* fix phpcs - integrate filesystem driver for file operations ([3994788](https://github.com/5mehulhelp5/mageforge/commit/39947883c626bc6f01eebe36bb38a9def1f38f6c))
* improve node module installation fallback logic ([#107](https://github.com/5mehulhelp5/mageforge/issues/107)) ([c400732](https://github.com/5mehulhelp5/mageforge/commit/c400732d5dfec183adc7fde9e42ad6b99f573f0e))
* improve theme builder to reduce cyclomatic complexity ([bd18896](https://github.com/5mehulhelp5/mageforge/commit/bd188962cbb1737fac80374b22f86de8426db2ab))
* improve theme selection and validation in TokensCommand ([#77](https://github.com/5mehulhelp5/mageforge/issues/77)) ([9167e95](https://github.com/5mehulhelp5/mageforge/commit/9167e956ddd1faebc03f39a26cf9a8434ecbe99a))
* labeler.yml to simplify Documentation labels ([2d96502](https://github.com/5mehulhelp5/mageforge/commit/2d96502e697fb6bc0c262867163d93086c75c9aa))
* labeler.yml to update label rules ([79c3fc0](https://github.com/5mehulhelp5/mageforge/commit/79c3fc05b8a468c76b3e69ee9b555e0460bc3928))
* normalize theme name check to be case-insensitive for Hyva themes ([#38](https://github.com/5mehulhelp5/mageforge/issues/38)) ([5426d18](https://github.com/5mehulhelp5/mageforge/commit/5426d183827b23dc3f704beaece8c87eee5a4542))
* phpcs errors ([#138](https://github.com/5mehulhelp5/mageforge/issues/138)) ([625c6da](https://github.com/5mehulhelp5/mageforge/commit/625c6da89882d19605713e4c295af713700890aa))
* **phpcs:** refactor environment variable handling in commands ([#135](https://github.com/5mehulhelp5/mageforge/issues/135)) ([9c01ce5](https://github.com/5mehulhelp5/mageforge/commit/9c01ce5fe269c0b917c95b5804542c7ee7840af3))
* phpstan level 5 errors [#84](https://github.com/5mehulhelp5/mageforge/issues/84) ([#100](https://github.com/5mehulhelp5/mageforge/issues/100)) ([154d15e](https://github.com/5mehulhelp5/mageforge/commit/154d15eba0db013b99cb4141dc0b2cd059147fb0))
* remove deprecated environment retrieval method ([#98](https://github.com/5mehulhelp5/mageforge/issues/98)) ([3e11ae7](https://github.com/5mehulhelp5/mageforge/commit/3e11ae7a572dff28875167043d5f9e64e7cc67b5))
* remove metric icons and rename metric titles for better ux ([#129](https://github.com/5mehulhelp5/mageforge/issues/129)) ([11d3c45](https://github.com/5mehulhelp5/mageforge/commit/11d3c45991684e5936862386e5a6e731ce7962ff))
* remove unnecessary blank lines in functional tests workflow ([f1e9bb7](https://github.com/5mehulhelp5/mageforge/commit/f1e9bb7ce8ea96f20f5c23b1b4ae78138388ab53))
* resolve issues with missing node_modules installation and watch output display ([b8eaa0b](https://github.com/5mehulhelp5/mageforge/commit/b8eaa0bdbb06a758e7cf0fe92897c691f7ca30b6))
* restore TTY after prompting for theme selection in BuildThemeCommand and ThemeWatchCommand 🎨 ([753685a](https://github.com/5mehulhelp5/mageforge/commit/753685a31862ef88091ea2cd781784bfd10eaf33))
* return theme parts as array in parseThemeName ([#122](https://github.com/5mehulhelp5/mageforge/issues/122)) ([94aef44](https://github.com/5mehulhelp5/mageforge/commit/94aef44bbc92ef6506ef6cd306ce010f1d6b6ef8))
* **ThemePath:** simplify theme retrieval logic in getPath method ([ffa4b41](https://github.com/5mehulhelp5/mageforge/commit/ffa4b415b8a1f244e4dee4a4464be9b4a1bd1bbc))
* update command aliases for consistency and clarity ([#82](https://github.com/5mehulhelp5/mageforge/issues/82)) ([34640fa](https://github.com/5mehulhelp5/mageforge/commit/34640fa88f0b622780b7257f7a74a2b469453391))
* update file_exists call to use named argument for clarity in HyvaThemeDetector ([00e370f](https://github.com/5mehulhelp5/mageforge/commit/00e370fe5b5e14921f9dd85494e436f2236b61db))
* update font settings and sizes in inspector CSS ([986ded6](https://github.com/5mehulhelp5/mageforge/commit/986ded6aeafe628c0549dc6d72f6ae119421d9df))
* update head-branch patterns and file globbing in labeler.yml ([#103](https://github.com/5mehulhelp5/mageforge/issues/103)) ([bd48b7c](https://github.com/5mehulhelp5/mageforge/commit/bd48b7ced59e405002897e595972bebf97a34bc4))
* update MageForge version command in compatibility test workflow ([b9bc5d1](https://github.com/5mehulhelp5/mageforge/commit/b9bc5d11e732d8d12f552e7d8cefa475cd0bd742))
* update phpcs errors ([#124](https://github.com/5mehulhelp5/mageforge/issues/124)) ([a19e23d](https://github.com/5mehulhelp5/mageforge/commit/a19e23d6bfc61bb255057ed739b3904855971e2f))
* update phpstan level to 7 and improve error handling ([#118](https://github.com/5mehulhelp5/mageforge/issues/118)) ([7c84ae7](https://github.com/5mehulhelp5/mageforge/commit/7c84ae75580037b6764c4e570cdca06fc5a3a970))
* update phpstan level to 8 and improve commands ([#119](https://github.com/5mehulhelp5/mageforge/issues/119)) ([e24e138](https://github.com/5mehulhelp5/mageforge/commit/e24e138ae2e5fcdb0013639cdb573da782fcb3fd))
* update validateHyvaTheme to include output parameter ([#99](https://github.com/5mehulhelp5/mageforge/issues/99)) ([9b53f8d](https://github.com/5mehulhelp5/mageforge/commit/9b53f8d270df9c56ab13488c2d7c60b367e3fa47))
* Workflow permissions ([#101](https://github.com/5mehulhelp5/mageforge/issues/101)) ([c0c4c3d](https://github.com/5mehulhelp5/mageforge/commit/c0c4c3dbccda41befc7107b38279dbb11dc77db2))


### Changed

* **BuildThemesCommand:** improve code readability by formatting shell command execution and success message ([5c26ee5](https://github.com/5mehulhelp5/mageforge/commit/5c26ee552bb0e99925466fd0657b7bec65e969b1))
* **BuildThemesCommand:** remove filesystem driver dependency and simplify file checks ([b7b21f3](https://github.com/5mehulhelp5/mageforge/commit/b7b21f3f3cc2061a6493177f53a9810c4ef4a71c))
* enhance progress bar format and improve success message output ([2d6807f](https://github.com/5mehulhelp5/mageforge/commit/2d6807f9ff6bd7fcc836436455a6afb1b5b1d5c9))
* remove AbstractBuilder ([f1e2b0a](https://github.com/5mehulhelp5/mageforge/commit/f1e2b0a9a1a69ee83097bcd4ea4ed1722fc2c701))
* remove HelloMageForgeCommand as it is no longer needed ([f507868](https://github.com/5mehulhelp5/mageforge/commit/f50786885accb5beb6140ed441e338f2d85b5469))
* remove redundant docblock comments for clarity ([2cb8763](https://github.com/5mehulhelp5/mageforge/commit/2cb87632ee8ae2c0a556a3375629e76d9373fdcc))
* remove redundant docblocks and improve table headers in SystemCheckCommand ([91dcc92](https://github.com/5mehulhelp5/mageforge/commit/91dcc924ee27580b5edcc38e47ca4df29c596b34))
* remove unnecessary blank lines in CliTest command ([9bbec97](https://github.com/5mehulhelp5/mageforge/commit/9bbec97256edf68135599060d59794b75d499bc7))
* remove unused service configurations from di.xml ([35a5d38](https://github.com/5mehulhelp5/mageforge/commit/35a5d38be42b75facbe4e5a79d29030cf738a163))
* simplify theme options retrieval in ThemeWatchCommand ([a62a512](https://github.com/5mehulhelp5/mageforge/commit/a62a512e3b4a094bc16e3b9059557e2d0b8ae1a6))
* update comments in BuildThemesCommand for clarity and consistency ([d3f056d](https://github.com/5mehulhelp5/mageforge/commit/d3f056d6900652d4392a4b19b8c74839e89579fc))


### Documentation

* add build command process documentation for Hyvä and Magento themes ([5aa361b](https://github.com/5mehulhelp5/mageforge/commit/5aa361b86c7ffab2207c00b1e0d207194e2720d5))
* add cli-chooser image to README.md ([c22a3f5](https://github.com/5mehulhelp5/mageforge/commit/c22a3f538aa461a8139c7ad495b062ffa636d5bb))
* clean up and format CHANGELOG.md ([ba34597](https://github.com/5mehulhelp5/mageforge/commit/ba34597fa1811723453c05e655cad7f802ed0e89))
* remove Github Action to watch for Changelog edits ([2f5745e](https://github.com/5mehulhelp5/mageforge/commit/2f5745e021e25c605b9370bef2c2bc213b9ea7e4))
* remove TODO note from custom_theme_builders.md and ListCommand.php ([6ce4aef](https://github.com/5mehulhelp5/mageforge/commit/6ce4aef1e5ab227f70cc151399349fbac0062a01))
* simplify installation instructions in README.md ([946e272](https://github.com/5mehulhelp5/mageforge/commit/946e27211b0252083fc55660d99b0916f3acfdea))
* update changelog for latest release [0.2.0] - 2025-05-30 ([058da28](https://github.com/5mehulhelp5/mageforge/commit/058da288bd744cd51783dea038f97790eb060690))
* update changelog for latest release and add new features ([604e76d](https://github.com/5mehulhelp5/mageforge/commit/604e76d26e8c9c134b708cdee63e74e6cf7463e5))
* update changelog for version 0.2.2 release with new features and fixes ✨ ([e358562](https://github.com/5mehulhelp5/mageforge/commit/e3585621eda5c76e62b9ba6de8445c43cc841fc4))
* update community support links to GitHub Discussions ([c67380e](https://github.com/5mehulhelp5/mageforge/commit/c67380ea8366a364ab5161b7e01c1a66872d3e24))
* update dependencies and naming conventions in Copilot instructions ([cf98266](https://github.com/5mehulhelp5/mageforge/commit/cf98266c331d41516c96eddaa32983038adc8ee4))
* update README and add advanced usage guide for improved clarity and tips 📝 ([0cc4572](https://github.com/5mehulhelp5/mageforge/commit/0cc4572b7c1b2801547417b0979b59fef18ddbd5))
* update README for command list and support section ([f4fb886](https://github.com/5mehulhelp5/mageforge/commit/f4fb886ca698a8f6d4ed3800bb60937f0f88331f))
* update README to include Magento version requirements ([103a92b](https://github.com/5mehulhelp5/mageforge/commit/103a92b570fa877af75362743fef90458efbadab))
* update README with beta status, enhance command descriptions, and add installation instructions ([230276c](https://github.com/5mehulhelp5/mageforge/commit/230276c38665f820210e23c49b4605f9c0fae121))
* update README with custom theme builders and contribution guidelines ([9b6886d](https://github.com/5mehulhelp5/mageforge/commit/9b6886df83a171e4de5a5f92c1f736b16000a335))
* update README with custom theme details and add inspector section ([084b528](https://github.com/5mehulhelp5/mageforge/commit/084b52815adb78b4292d748fc100a8be3994844c))

## [0.12.0](https://github.com/OpenForgeProject/mageforge/compare/0.11.0...0.12.0) (2026-02-14)


### Added

* **actions:** replace elasticsearch with opensearch ([#137](https://github.com/OpenForgeProject/mageforge/issues/137)) ([cc8c534](https://github.com/OpenForgeProject/mageforge/commit/cc8c53428288a45b8ad645baf87623bf4a8b9a1f))


### Fixed

* correct font size and border radius in inspector CSS ([7bb3348](https://github.com/OpenForgeProject/mageforge/commit/7bb334806a134687bd06cf55e5f27682947f3c84))
* phpcs errors ([#138](https://github.com/OpenForgeProject/mageforge/issues/138)) ([625c6da](https://github.com/OpenForgeProject/mageforge/commit/625c6da89882d19605713e4c295af713700890aa))
* **phpcs:** refactor environment variable handling in commands ([#135](https://github.com/OpenForgeProject/mageforge/issues/135)) ([9c01ce5](https://github.com/OpenForgeProject/mageforge/commit/9c01ce5fe269c0b917c95b5804542c7ee7840af3))
* update font settings and sizes in inspector CSS ([986ded6](https://github.com/OpenForgeProject/mageforge/commit/986ded6aeafe628c0549dc6d72f6ae119421d9df))


### Documentation

* update README with custom theme details and add inspector section ([084b528](https://github.com/OpenForgeProject/mageforge/commit/084b52815adb78b4292d748fc100a8be3994844c))

## [0.11.0](https://github.com/OpenForgeProject/mageforge/compare/0.10.3...0.11.0) (2026-02-10)


### Added

* add cache and webvitals tabs to inspector and improve ux with dragable overlay ([#127](https://github.com/OpenForgeProject/mageforge/issues/127)) ([eea755d](https://github.com/OpenForgeProject/mageforge/commit/eea755d1b38fe9e736a49157192babc5b98fbb10))
* implement dark/light mode theme selection and admin configuration section ([#131](https://github.com/OpenForgeProject/mageforge/issues/131)) ([0a95280](https://github.com/OpenForgeProject/mageforge/commit/0a952808b6a5f7102aa5ad4b874e576d67f77bd1))


### Fixed

* remove metric icons and rename metric titles for better ux ([#129](https://github.com/OpenForgeProject/mageforge/issues/129)) ([11d3c45](https://github.com/OpenForgeProject/mageforge/commit/11d3c45991684e5936862386e5a6e731ce7962ff))

## [0.10.3](https://github.com/OpenForgeProject/mageforge/compare/0.10.2...0.10.3) (2026-02-05)


### Fixed

* update phpcs errors ([#124](https://github.com/OpenForgeProject/mageforge/issues/124)) ([a19e23d](https://github.com/OpenForgeProject/mageforge/commit/a19e23d6bfc61bb255057ed739b3904855971e2f))

## [0.10.2](https://github.com/OpenForgeProject/mageforge/compare/0.10.1...0.10.2) (2026-02-02)


### Fixed

* return theme parts as array in parseThemeName ([#122](https://github.com/OpenForgeProject/mageforge/issues/122)) ([94aef44](https://github.com/OpenForgeProject/mageforge/commit/94aef44bbc92ef6506ef6cd306ce010f1d6b6ef8))

## [0.10.1](https://github.com/OpenForgeProject/mageforge/compare/0.10.0...0.10.1) (2026-01-30)


### Fixed

* correct spacing and formatting in multiple files ([#120](https://github.com/OpenForgeProject/mageforge/issues/120)) ([3f9048a](https://github.com/OpenForgeProject/mageforge/commit/3f9048abc0b0f2785aa5be3858704037ad14ce5a))
* update phpstan level to 8 and improve commands ([#119](https://github.com/OpenForgeProject/mageforge/issues/119)) ([e24e138](https://github.com/OpenForgeProject/mageforge/commit/e24e138ae2e5fcdb0013639cdb573da782fcb3fd))

## [0.10.0](https://github.com/OpenForgeProject/mageforge/compare/0.9.0...0.10.0) (2026-01-30)


### Added

* update phpstan level and add type hints ([#116](https://github.com/OpenForgeProject/mageforge/issues/116)) ([0a4a5fa](https://github.com/OpenForgeProject/mageforge/commit/0a4a5fa45ca77396a87569eca3491b569e3d3539))


### Fixed

* update phpstan level to 7 and improve error handling ([#118](https://github.com/OpenForgeProject/mageforge/issues/118)) ([7c84ae7](https://github.com/OpenForgeProject/mageforge/commit/7c84ae75580037b6764c4e570cdca06fc5a3a970))

## [0.9.0](https://github.com/OpenForgeProject/mageforge/compare/0.8.1...0.9.0) (2026-01-30)


### Added

* Node.js/Grunt setup detection for improved build process ([#114](https://github.com/OpenForgeProject/mageforge/issues/114)) ([5330e17](https://github.com/OpenForgeProject/mageforge/commit/5330e1702acc470276bd8c6ea508b0c35ac18a2f))


### Fixed

* phpstan level 5 errors [#84](https://github.com/OpenForgeProject/mageforge/issues/84) ([#100](https://github.com/OpenForgeProject/mageforge/issues/100)) ([154d15e](https://github.com/OpenForgeProject/mageforge/commit/154d15eba0db013b99cb4141dc0b2cd059147fb0))

## [0.8.1](https://github.com/OpenForgeProject/mageforge/compare/0.8.0...0.8.1) (2026-01-27)


### Fixed

* improve node module installation fallback logic ([#107](https://github.com/OpenForgeProject/mageforge/issues/107)) ([c400732](https://github.com/OpenForgeProject/mageforge/commit/c400732d5dfec183adc7fde9e42ad6b99f573f0e))

## [0.8.0](https://github.com/OpenForgeProject/mageforge/compare/0.7.0...0.8.0) (2026-01-23)


### Added

* add functional-tests badge to readme.md ([#95](https://github.com/OpenForgeProject/mageforge/issues/95)) ([7108ef0](https://github.com/OpenForgeProject/mageforge/commit/7108ef0d4408b82f3010acaa00cf6f257880809d))
* add npm sync validation to NodePackageManager and theme builders ([#93](https://github.com/OpenForgeProject/mageforge/issues/93)) ([5fcbdaf](https://github.com/OpenForgeProject/mageforge/commit/5fcbdaf7ceb19136f4b86fbffd33b44cee1469d6))
* add phpstan & phpcs ([#96](https://github.com/OpenForgeProject/mageforge/issues/96)) ([06bcfdc](https://github.com/OpenForgeProject/mageforge/commit/06bcfdc82b1a8e0a58ad8712f7a120dc215e850f))
* add pinning functionality for inspector badge ([#104](https://github.com/OpenForgeProject/mageforge/issues/104)) ([69f7328](https://github.com/OpenForgeProject/mageforge/commit/69f73287754b572ea27349fcbb248f351dd7bc0d))
* enhance inspector with JSON metadata and comment parsing ([#105](https://github.com/OpenForgeProject/mageforge/issues/105)) ([a2f9ebf](https://github.com/OpenForgeProject/mageforge/commit/a2f9ebf4a188e01576d980866c92b7d9e7bf55f1))
* separate functional tests from compatibility tests ([effac26](https://github.com/OpenForgeProject/mageforge/commit/effac2637837efa4814b93bc1b09eb8cef306544))
* update feature request link to direct to new issue template ([7e0b57e](https://github.com/OpenForgeProject/mageforge/commit/7e0b57eb33f927ba307b008af504de42c4a2a5af))


### Fixed

* correct head-branch regex and add new changed-files sections ([53777ea](https://github.com/OpenForgeProject/mageforge/commit/53777eac19920e4de175b2a52704ff8b0c9982de))
* labeler.yml to simplify Documentation labels ([2d96502](https://github.com/OpenForgeProject/mageforge/commit/2d96502e697fb6bc0c262867163d93086c75c9aa))
* labeler.yml to update label rules ([79c3fc0](https://github.com/OpenForgeProject/mageforge/commit/79c3fc05b8a468c76b3e69ee9b555e0460bc3928))
* remove deprecated environment retrieval method ([#98](https://github.com/OpenForgeProject/mageforge/issues/98)) ([3e11ae7](https://github.com/OpenForgeProject/mageforge/commit/3e11ae7a572dff28875167043d5f9e64e7cc67b5))
* remove unnecessary blank lines in functional tests workflow ([f1e9bb7](https://github.com/OpenForgeProject/mageforge/commit/f1e9bb7ce8ea96f20f5c23b1b4ae78138388ab53))
* update head-branch patterns and file globbing in labeler.yml ([#103](https://github.com/OpenForgeProject/mageforge/issues/103)) ([bd48b7c](https://github.com/OpenForgeProject/mageforge/commit/bd48b7ced59e405002897e595972bebf97a34bc4))
* update validateHyvaTheme to include output parameter ([#99](https://github.com/OpenForgeProject/mageforge/issues/99)) ([9b53f8d](https://github.com/OpenForgeProject/mageforge/commit/9b53f8d270df9c56ab13488c2d7c60b367e3fa47))
* Workflow permissions ([#101](https://github.com/OpenForgeProject/mageforge/issues/101)) ([c0c4c3d](https://github.com/OpenForgeProject/mageforge/commit/c0c4c3dbccda41befc7107b38279dbb11dc77db2))

## [0.7.0](https://github.com/OpenForgeProject/mageforge/compare/0.6.0...0.7.0) (2026-01-20)


### Added

* add context7 configuration file with URL and public key ([977bee0](https://github.com/OpenForgeProject/mageforge/commit/977bee0d2b2c4301bd2764b07ef82eefb92e29fb))
* add NodePackageManager service for npm dependency management ([#91](https://github.com/OpenForgeProject/mageforge/issues/91)) ([1ab623f](https://github.com/OpenForgeProject/mageforge/commit/1ab623f5d858c272b6f692acb98edd35bf15ed3d))
* implement SymlinkCleaner service and integrate into theme builders [#88](https://github.com/OpenForgeProject/mageforge/issues/88) ([#89](https://github.com/OpenForgeProject/mageforge/issues/89)) ([3f40ef6](https://github.com/OpenForgeProject/mageforge/commit/3f40ef64174686fd3c75944d00773ef83515f0f9))

## [0.6.0](https://github.com/OpenForgeProject/mageforge/compare/0.5.0...0.6.0) (2026-01-19)


### Added

* dev Inspector Overlay (Frontend) ([#85](https://github.com/OpenForgeProject/mageforge/issues/85)) ([806d04a](https://github.com/OpenForgeProject/mageforge/commit/806d04a252eb70f6f76131a672296d62a7c5372b))

## [0.5.0](https://github.com/OpenForgeProject/mageforge/compare/0.4.0...0.5.0) (2026-01-17)


### ⚠ BREAKING CHANGES

* create theme:clean command for cleaning theme static files and cache, remove old mageforge:static:clean command ([#80](https://github.com/OpenForgeProject/mageforge/issues/80))

### Added

* implement StaticContentCleaner and update theme build commands ([#83](https://github.com/OpenForgeProject/mageforge/issues/83)) ([80a6abf](https://github.com/OpenForgeProject/mageforge/commit/80a6abf8b63dfdf25233f884d3fc3c6a2648b05c))


### Fixed

* create theme:clean command for cleaning theme static files and cache, remove old mageforge:static:clean command ([#80](https://github.com/OpenForgeProject/mageforge/issues/80)) ([ffd5ec8](https://github.com/OpenForgeProject/mageforge/commit/ffd5ec89e87eb8aa3a1f19eb957bd3f95a5c50b1))
* update command aliases for consistency and clarity ([#82](https://github.com/OpenForgeProject/mageforge/issues/82)) ([34640fa](https://github.com/OpenForgeProject/mageforge/commit/34640fa88f0b622780b7257f7a74a2b469453391))

## [0.4.0](https://github.com/OpenForgeProject/mageforge/compare/0.3.1...0.4.0) (2026-01-17)


### Added

* add theme suggestion service and integrate with commands [#75](https://github.com/OpenForgeProject/mageforge/issues/75) ([#76](https://github.com/OpenForgeProject/mageforge/issues/76)) ([1347782](https://github.com/OpenForgeProject/mageforge/commit/13477823e82b81bda5412a7f8d4cbd747254d6c5))
* implement Release Please workflow and update configuration ([d814853](https://github.com/OpenForgeProject/mageforge/commit/d814853c220dd098ad11340ea179ad66f9fb01f7))


### Fixed

* adjust command argument order and clean up whitespace ([9c4fb73](https://github.com/OpenForgeProject/mageforge/commit/9c4fb7356d23c38096e798d797fdfcb4ec455ff5))
* enhance interactive mode for compatibility checks and prompts ([#79](https://github.com/OpenForgeProject/mageforge/issues/79)) ([428a133](https://github.com/OpenForgeProject/mageforge/commit/428a1338479a2ad1642ea7a353d0c73e37ef155b))
* improve theme selection and validation in TokensCommand ([#77](https://github.com/OpenForgeProject/mageforge/issues/77)) ([9167e95](https://github.com/OpenForgeProject/mageforge/commit/9167e956ddd1faebc03f39a26cf9a8434ecbe99a))


### Documentation

* update community support links to GitHub Discussions ([c67380e](https://github.com/OpenForgeProject/mageforge/commit/c67380ea8366a364ab5161b7e01c1a66872d3e24))
* update dependencies and naming conventions in Copilot instructions ([cf98266](https://github.com/OpenForgeProject/mageforge/commit/cf98266c331d41516c96eddaa32983038adc8ee4))
* update README for command list and support section ([f4fb886](https://github.com/OpenForgeProject/mageforge/commit/f4fb886ca698a8f6d4ed3800bb60937f0f88331f))

### [0.3.1] - 2026-01-12

#### Fixed

- fix: add missing static property `$cachedEnv` in CleanCommand to resolve undeclared property error

### [0.3.0] - 2026-01-12

#### Added

- feat: add verbose output support for watch task with `-v` flag
  - Shows informative messages during watch mode based on verbosity level
  - Captures and reports exit codes from npm/grunt watch commands
  - Displays clear error messages when watch mode exits with errors
  - Provides hint to use `-v` flag for verbose output in non-verbose mode
- feat: add `mageforge:theme:tokens` command to generate Hyvä design tokens from design.tokens.json or hyva.config.json
- feat: add `mageforge:hyva:compatibility:check` command to add a Hyvä compatibility checker
  - Scans Magento modules for Hyvä theme compatibility issues
  - Detects RequireJS, Knockout.js, jQuery, and UI Components usage
  - Interactive menu with Laravel Prompts for scan options
  - Options: `--show-all`, `--third-party-only`, `--include-vendor`, `--detailed`
  - Color-coded output (✓ Compatible, ⚠ Warnings, ✗ Incompatible)
  - Detailed file-level issues with line numbers
  - Exit code 1 for critical issues, 0 for success
  - Command aliases: `m:h:c:c`, `hyva:check`
- feat: add `mageforge:theme:clean` command for comprehensive cache and generated files cleanup
  - feat: add interactive multi-theme selection for theme:clean command using Laravel Prompts
  - feat: add `--all` option to clean all themes at once
  - feat: add `--dry-run` option to preview what would be cleaned without deleting
  - feat: add command alias `frontend:clean` for quick access
  - feat: add CI/CD tests for theme:clean command in compatibility workflow

#### Fixed

- fix: remove duplicate `--verbose` option from WatchCommand that conflicted with Symfony Console's built-in verbose option

#### Changed

- refactor: improve build commands to show full output in verbose mode
  - Remove `--quiet` flag from npm/grunt build commands when using verbose mode
  - Allow better debugging of build issues during theme compilation
- refactor: split complex executeCommand method into smaller, focused methods to reduce cyclomatic complexity
- docs: update copilot-instructions.md with CI/CD integration guidelines for new commands

### [0.2.2] - 2025-06-05

- feat: enhance theme command arguments for better clarity and compatibility

### [0.2.1] - 2025-06-04

- feat: reduce cyclomatic complexity
- fix: normalize theme name check to be case-insensitive for Hyva themes

### [0.2.0] - 2025-05-30

- docs: clean up `CHANGELOG.md`
- feat: add PHP 8.4 and Magento 2.4.8 compatibilty check with opensearch support
- feat: enhance MySQL and Search Engine checks for `mageforge:system:check` command
- removed: removed Github Action to watch for Changelog edits
- fix: fixed issue where missing node_modules were not being installed
- fix: fixed issue where watch output was not displayed correctly

### [0.1.0] - 2025-05-23

- docs: add cli-chooser image to README.md
- docs: simplify installation instructions in README.md
- feat: add comprehensive documentation for MageForge commands and custom ThemeBuilders
- feat: add Magento compatibility tests workflow (#35)
- feat: add spinner for theme building process in BuildThemeCommand
- feat: add system check commands for Node.js, MySQL, and environment status
- feat: enhance npm installation process with package-lock.json check
- feat: enhance system check command to display additional environment information
- feat: implement abstract command structure for improved command handling
- fix: improve theme builder to reduce cyclomatic complexity
- fix: restore TTY after prompting for theme selection in BuildThemeCommand and ThemeWatchCommand 🎨
- fix: update MageForge version command in compatibility test workflow
- refactor system and theme commands
- refactor: remove redundant docblocks and improve table headers in SystemCheckCommand
- refactor: simplify theme options retrieval in ThemeWatchCommand
- Update ListCommand.php
- Update custom_theme_builders.md
- Update magento-compatibility.yml
