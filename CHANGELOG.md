# Release Notes

## [Unreleased](https://github.com/laravel/installer/compare/v5.16.0...master)

## [v5.16.0](https://github.com/laravel/installer/compare/v5.15.0...v5.16.0) - 2025-06-17

* fix: Starter kits should not ignore the `--database` option by [@mathiasgrimm](https://github.com/mathiasgrimm) in https://github.com/laravel/installer/pull/422

## [v5.15.0](https://github.com/laravel/installer/compare/v5.14.2...v5.15.0) - 2025-05-20

* add missing variable name to doc tags and missing doc tags to methods by [@Muetze42](https://github.com/Muetze42) in https://github.com/laravel/installer/pull/420

## [v5.14.2](https://github.com/laravel/installer/compare/v5.14.1...v5.14.2) - 2025-04-01

* [5.x] Only open files in the tests directory when converting to Pest by [@tonysm](https://github.com/tonysm) in https://github.com/laravel/installer/pull/414

## [v5.14.1](https://github.com/laravel/installer/compare/v5.14.0...v5.14.1) - 2025-03-18

* Adding Pest option back in Laravel app and improve pest experience by [@tnylea](https://github.com/tnylea) in https://github.com/laravel/installer/pull/413

## [v5.14.0](https://github.com/laravel/installer/compare/v5.13.0...v5.14.0) - 2025-03-07

* [12.x] Adds an option to install a custom starter kits by [@tonysm](https://github.com/tonysm) in https://github.com/laravel/installer/pull/407

## [v5.13.0](https://github.com/laravel/installer/compare/v5.12.2...v5.13.0) - 2025-02-28

* Add support for non-Volt Livewire starter kit
* Add npm option to fix no-interaction installs by [@mpociot](https://github.com/mpociot) in https://github.com/laravel/installer/pull/402

## [v5.12.2](https://github.com/laravel/installer/compare/v5.12.1...v5.12.2) - 2025-02-25

* Remove drift plugin after running drift command by [@laserhybiz](https://github.com/laserhybiz) in https://github.com/laravel/installer/pull/393
* Fix Pest installation by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/397
* Use PHPStan 2 by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/396
* Use pest command in github workflow when using pest by [@laserhybiz](https://github.com/laserhybiz) in https://github.com/laravel/installer/pull/401

## [v5.12.1](https://github.com/laravel/installer/compare/v5.12.0...v5.12.1) - 2025-02-24

## [v5.12.0](https://github.com/laravel/installer/compare/v5.11.2...v5.12.0) - 2025-02-24

* Laravel 12.x Compatibility by [@laravel-shift](https://github.com/laravel-shift) in https://github.com/laravel/installer/pull/389
* Laravel 12 + New Starter Kits by [@taylorotwell](https://github.com/taylorotwell) in https://github.com/laravel/installer/pull/390

## [v5.11.2](https://github.com/laravel/installer/compare/v5.11.1...v5.11.2) - 2025-01-14

* Update version to 5.11.1 by [@miclaus](https://github.com/miclaus) in https://github.com/laravel/installer/pull/381
* Fix Laravel installer on Windows WSL by [@JasonTame](https://github.com/JasonTame) in https://github.com/laravel/installer/pull/385

## [v5.11.1](https://github.com/laravel/installer/compare/v5.11.0...v5.11.1) - 2024-12-11

* [5.x] Throw exceptions when trying to use Installer on PHP environment without required extensions by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/373
* Ensure Symfony/mbstring-polyfill version 1.31 or higher by [@ellnix](https://github.com/ellnix) in https://github.com/laravel/installer/pull/376

## [v5.11.0](https://github.com/laravel/installer/compare/v5.10.0...v5.11.0) - 2024-12-10

* Remove any trailing slash from application name by [@jasonmccreary](https://github.com/jasonmccreary) in https://github.com/laravel/installer/pull/368
* Add disableProcessTimeout to composer run dev by [@ryan08100715](https://github.com/ryan08100715) in https://github.com/laravel/installer/pull/370
* Test Improvements by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/371

## [v5.10.0](https://github.com/laravel/installer/compare/v5.9.2...v5.10.0) - 2024-11-19

* [5.x] Supports PHP 8.4 by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/364
* [5.x] Remove `php artisan pail` from `composer run dev` on Windows  by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/366

## [v5.9.2](https://github.com/laravel/installer/compare/v5.9.1...v5.9.2) - 2024-10-22

* Replace `php artisan serve` with `composer run dev` by [@1weiho](https://github.com/1weiho) in https://github.com/laravel/installer/pull/362

## [v5.9.1](https://github.com/laravel/installer/compare/v5.9.0...v5.9.1) - 2024-10-10

* [5.x] Add `eslint` option for breeze inertia stack by [@avosalmon](https://github.com/avosalmon) in https://github.com/laravel/installer/pull/361

## [v5.9.0](https://github.com/laravel/installer/compare/v5.8.5...v5.9.0) - 2024-10-01

* [5.x] Utilise `Illuminate\Support\php_binary()` by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/360
* [5.x] Support Laravel Prompts 0.2+ and 0.3+ by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/359

## [v5.8.5](https://github.com/laravel/installer/compare/v5.8.3...v5.8.5) - 2024-09-11

* Replace dead link in Security Policy by [@Jubeki](https://github.com/Jubeki) in https://github.com/laravel/installer/pull/351
* Fix `--no-interaction` SQLite file prompt by [@jacksleight](https://github.com/jacksleight) in https://github.com/laravel/installer/pull/354

## [v5.8.3](https://github.com/laravel/installer/compare/v5.8.2...v5.8.3) - 2024-06-18

* Validate Laravel can be installed on selected directory by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/344
* Automatically run migration when `--database` is given. by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/346

## [v5.8.2](https://github.com/laravel/installer/compare/v5.8.1...v5.8.2) - 2024-06-02

* [5.x] Fixes issue if there is no `herd` or `valet` installed by [@xiCO2k](https://github.com/xiCO2k) in https://github.com/laravel/installer/pull/343

## [v5.8.1](https://github.com/laravel/installer/compare/v5.8.0...v5.8.1) - 2024-05-21

* Only run migration after selecting the database by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/337
* [1.x] Enforce output when running with `--quiet` by [@xiCO2k](https://github.com/xiCO2k) in https://github.com/laravel/installer/pull/339

## [v5.8.0](https://github.com/laravel/installer/compare/v5.7.3...v5.8.0) - 2024-05-07

* Improves output if Herd or Valet are installed. by [@xiCO2k](https://github.com/xiCO2k) in https://github.com/laravel/installer/pull/335
* Gets the default "tld" on install. by [@xiCO2k](https://github.com/xiCO2k) in https://github.com/laravel/installer/pull/336

## [v5.7.3](https://github.com/laravel/installer/compare/v5.7.2...v5.7.3) - 2024-04-30

* Prevent using unavailable databases by [@driesvints](https://github.com/driesvints) in https://github.com/laravel/installer/pull/334

## [v5.7.2](https://github.com/laravel/installer/compare/v5.7.1...v5.7.2) - 2024-04-16

* Install Breeze with dev flag by [@driesvints](https://github.com/driesvints) in https://github.com/laravel/installer/pull/332

## [v5.7.1](https://github.com/laravel/installer/compare/v5.7.0...v5.7.1) - 2024-04-02

* [5.x] Removes "(experimental)" label by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/330

## [v5.7.0](https://github.com/laravel/installer/compare/v5.6.0...v5.7.0) - 2024-03-26

* Remove unused `migrate` parameter by [@nshiro](https://github.com/nshiro) in https://github.com/laravel/installer/pull/323
* Add `--database` option by [@CasEbb](https://github.com/CasEbb) in https://github.com/laravel/installer/pull/320

## [v5.6.0](https://github.com/laravel/installer/compare/v5.5.3...v5.6.0) - 2024-03-12

* Remove Laravel 11 Checks by [@Jubeki](https://github.com/Jubeki) in https://github.com/laravel/installer/pull/319

## [v5.5.3](https://github.com/laravel/installer/compare/v5.5.2...v5.5.3) - 2024-03-05

* [11.x] Removes `publish config` files by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/317

## [v5.5.2](https://github.com/laravel/installer/compare/v5.5.1...v5.5.2) - 2024-02-20

- Prompt for config publish by [@taylorotwell](https://github.com/taylorotwell) in https://github.com/laravel/installer/commit/c3b3c661ffc1323951537b5ff470ec706357fa1f

## [v5.5.1](https://github.com/laravel/installer/compare/v5.5.0...v5.5.1) - 2024-02-12

* [5.x] Fixes Pest installation on Windows by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/314

## [v5.5.0](https://github.com/laravel/installer/compare/v5.4.0...v5.5.0) - 2024-01-30

* [5.x] Improves installation of Pest by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/311

## [v5.4.0](https://github.com/laravel/installer/compare/v5.3.0...v5.4.0) - 2024-01-23

* SQLite by [@taylorotwell](https://github.com/taylorotwell) in https://github.com/laravel/installer/pull/304
* [5.x] Implies only the new migrations behaviour on L11 by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/305
* [5.x] Improves ending message by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/307

## [v5.3.0](https://github.com/laravel/installer/compare/v5.2.1...v5.3.0) - 2024-01-16

* [5.x]  Laravel v11 support by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/302

## [v5.2.1](https://github.com/laravel/installer/compare/v5.2.0...v5.2.1) - 2024-01-09

* Adjust link to docs by [@driesvints](https://github.com/driesvints) in https://github.com/laravel/installer/pull/299
* [5.x] Added default value on selection question while creating new application by [@bigship-prashant](https://github.com/bigship-prashant) in https://github.com/laravel/installer/pull/300

## [v5.2.0](https://github.com/laravel/installer/compare/v5.1.3...v5.2.0) - 2023-12-05

* Apply using the str_starts_with function by [@peter279k](https://github.com/peter279k) in https://github.com/laravel/installer/pull/289
* Add mariadb installation option by [@Jubeki](https://github.com/Jubeki) in https://github.com/laravel/installer/pull/292
* [5.x] Removes alias by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/293

## [v5.1.3](https://github.com/laravel/installer/compare/v5.1.2...v5.1.3) - 2023-10-10

- Remove extra DB_DATABASE by [@ConnySjoblom](https://github.com/ConnySjoblom) in https://github.com/laravel/installer/pull/287
- Adjusts new command with new Breeze options by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/288

## [v5.1.2](https://github.com/laravel/installer/compare/v5.1.1...v5.1.2) - 2023-09-26

- Add the Livewire stack by [@mpociot](https://github.com/mpociot) in https://github.com/laravel/installer/pull/285

## [v5.1.1](https://github.com/laravel/installer/compare/v5.1.0...v5.1.1) - 2023-09-12

- Fix Jetstream SSR option by [@jessarcher](https://github.com/jessarcher) in https://github.com/laravel/installer/pull/281

## [v5.1.0](https://github.com/laravel/installer/compare/v5.0.4...v5.1.0) - 2023-08-29

- Fixes breeze installation with `--ssr` options by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/278
- Adds missing jetstream options by [@nunomaduro](https://github.com/nunomaduro) in https://github.com/laravel/installer/pull/279
- Add ability to select default database connection by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/275
- Updated to use the Process constructor to install Pest and use `Composer` helper class by [@crynobone](https://github.com/crynobone) in https://github.com/laravel/installer/pull/274

## [v5.0.4](https://github.com/laravel/installer/compare/v5.0.3...v5.0.4) - 2023-08-22

No major changes.

## [v5.0.3](https://github.com/laravel/installer/compare/v5.0.2...v5.0.3) - 2023-08-15

- Add option to indicate whether Breeze should be scaffolded with TypeScript support by [@weavdale](https://github.com/weavdale) in https://github.com/laravel/installer/pull/271

## [v5.0.2](https://github.com/laravel/installer/compare/v5.0.1...v5.0.2) - 2023-08-08

- Show the directory name at the end of the installer by [@jessarcher](https://github.com/jessarcher) in https://github.com/laravel/installer/pull/270

## [v5.0.1](https://github.com/laravel/installer/compare/v5.0.0...v5.0.1) - 2023-08-03

- Don't prompt for Git if Github Option is found by [@Jubeki](https://github.com/Jubeki) in https://github.com/laravel/installer/pull/269

## [v5.0.0](https://github.com/laravel/installer/compare/v4.5.1...v5.0.0) - 2023-08-01

- Update prompts by [@jessarcher](https://github.com/jessarcher) in https://github.com/laravel/installer/pull/267

## [v4.5.1](https://github.com/laravel/installer/compare/v4.5.0...v4.5.1) - 2023-07-25

- Wrap PHP_BINARY in quotes by [@mpociot](https://github.com/mpociot) in https://github.com/laravel/installer/pull/268

## [v4.5.0](https://github.com/laravel/installer/compare/v4.4.3...v4.5.0) - 2023-03-20

- Use Pest v2 by @nunomaduro in https://github.com/laravel/installer/pull/262

## [v4.4.3](https://github.com/laravel/installer/compare/v4.4.2...v4.4.3) - 2023-03-07

- Prevent unknown option with git commands by @zepfietje in https://github.com/laravel/installer/pull/260

## [v4.4.2](https://github.com/laravel/installer/compare/v4.4.1...v4.4.2) - 2023-03-02

- Adds option "dark" to jetstream installation by @MarioPerini in https://github.com/laravel/installer/pull/259

## [v4.4.1](https://github.com/laravel/installer/compare/v4.4.0...v4.4.1) - 2023-02-21

- Add an option to install PHPUnit by @likeadeckofcards in https://github.com/laravel/installer/pull/256

## [v4.4.0](https://github.com/laravel/installer/compare/v4.3.0...v4.4.0) - 2023-02-14

### Added

- Adds Laravel Breeze scaffolding by @nunomaduro in https://github.com/laravel/installer/pull/253

### Fixed

- Fixes installation of Pest in Laravel 10 by @nunomaduro in https://github.com/laravel/installer/pull/254

## [v4.3.0](https://github.com/laravel/installer/compare/v4.2.17...v4.3.0) - 2023-02-07

### Added

- Adds `--pest` flag to use Pest by @nunomaduro in https://github.com/laravel/installer/pull/251

## [v4.2.17](https://github.com/laravel/installer/compare/v4.2.16...v4.2.17) - 2022-09-13

### Changed

- Remove `storage:link` command by @jessarcher in https://github.com/laravel/installer/pull/245

## [v4.2.16](https://github.com/laravel/installer/compare/v4.2.15...v4.2.16) - 2022-08-16

### Changed

- Remove duplicate `npm install` and `npm run build` steps by @jessarcher in https://github.com/laravel/installer/pull/242

## [v4.2.15](https://github.com/laravel/installer/compare/v4.2.14...v4.2.15) - 2022-08-09

### Fixed

- Changes APP_URL replacement with name to lower by @RhysLees in https://github.com/laravel/installer/pull/239
- Prevent unresolvable `APP_URL` by @jessarcher in https://github.com/laravel/installer/pull/240

## [v4.2.14](https://github.com/laravel/installer/compare/v4.2.13...v4.2.14) - 2022-08-02

### Changed

- Simplify push to GitHub by @driesvints in https://github.com/laravel/installer/pull/238

## [v4.2.13](https://github.com/laravel/installer/compare/v4.2.12...v4.2.13) - 2022-07-26

### Changed

- Improved console output by @nunomaduro in https://github.com/laravel/installer/pull/235

## [v4.2.12](https://github.com/laravel/installer/compare/v4.2.11...v4.2.12) - 2022-07-13

### Fixed

- Check directory before deleting in Windows OS by @azizramdan in https://github.com/laravel/installer/pull/233

## [v4.2.11](https://github.com/laravel/installer/compare/v4.2.10...v4.2.11) - 2022-06-28

### Fixed

- Use build command instead of dev command for Vite support by @driesvints in https://github.com/laravel/installer/pull/232

## [v4.2.10 (2022-01-18)](https://github.com/laravel/installer/compare/v4.2.9...v4.2.10)

### Changed

- Symfony v6 support ([#217](https://github.com/laravel/installer/pull/217))

### Fixed

- Maintain current functionality with gh repo create rewrite ([#219](https://github.com/laravel/installer/pull/219))

## [v4.2.9 (2021-10-26)](https://github.com/laravel/installer/compare/v4.2.8...v4.2.9)

### Changed

- Always run NPM install ([#214](https://github.com/laravel/installer/pull/214))

## [v4.2.8 (2021-08-17)](https://github.com/laravel/installer/compare/v4.2.7...v4.2.8)

### Changed

- Respect git global config for a default branch ([#207](https://github.com/laravel/installer/pull/207))

## [v4.2.7 (2021-06-08)](https://github.com/laravel/installer/compare/v4.2.6...v4.2.7)

### Fixed

- Use `isDecorated` for no-ansi detection ([#203](https://github.com/laravel/installer/pull/203))

## [v4.2.6 (2021-06-01)](https://github.com/laravel/installer/compare/v4.2.5...v4.2.6)

### Fixed

- Fix new command failing without `no-ansi` option ([#202](https://github.com/laravel/installer/pull/202))

## [v4.2.5 (2021-04-27)](https://github.com/laravel/installer/compare/v4.2.4...v4.2.5)

### Changed

- Add support for older versions of Git ([#199](https://github.com/laravel/installer/pull/199))

## [v4.2.4 (2021-03-23)](https://github.com/laravel/installer/compare/v4.2.3...v4.2.4)

### Added

- Add branch flag ([#197](https://github.com/laravel/installer/pull/197), [a8d5c2d](https://github.com/laravel/installer/commit/a8d5c2d2ff7df892b567ffea19527b0c4451b750))

### Changed

- Update pushing branch ([#196](https://github.com/laravel/installer/pull/196))

## [v4.2.3 (2021-03-18)](https://github.com/laravel/installer/compare/v4.2.2...v4.2.3)

### Added

- Add organization flag ([#194](https://github.com/laravel/installer/pull/194))

## [v4.2.2 (2021-03-16)](https://github.com/laravel/installer/compare/v4.2.1...v4.2.2)

### Changed

- Revert "Improve Git push" ([#192](https://github.com/laravel/installer/pull/192))

## [v4.2.1 (2021-03-16)](https://github.com/laravel/installer/compare/v4.2.0...v4.2.1)

### Changed

- Improve Git push ([#191](https://github.com/laravel/installer/pull/191))

## [v4.2.0 (2021-03-09)](https://github.com/laravel/installer/compare/v4.1.1...v4.2.0)

### Added

- Git Support ([#185](https://github.com/laravel/installer/pull/185))

## [v4.1.1 (2020-11-17)](https://github.com/laravel/installer/compare/v4.1.0...v4.1.1)

### Changed

- Require name argument ([#178](https://github.com/laravel/installer/pull/178))

## [v4.1.0 (2020-11-03)](https://github.com/laravel/installer/compare/v4.0.7...v4.1.0)

### Added

- PHP 8 Support ([#168](https://github.com/laravel/installer/pull/168))

### Changed

- Use `dev-master` for `dev` version ([9ce64f82](https://github.com/laravel/installer/commit/9ce64f82dcc6d700d91e34b7bcfc32f0b16e2839))

## [v4.0.7 (2020-10-30)](https://github.com/laravel/installer/compare/v4.0.6...v4.0.7)

### Fixed

- Fixed some jetstream prompt issues

## [v4.0.6 (2020-10-30)](https://github.com/laravel/installer/compare/v4.0.5...v4.0.6)

### Added

- Add prompt-jetstream switch ([95c3a00](https://github.com/laravel/installer/commit/95c3a00ee7fc188121ae3e90292f712eae19b26b))

### Changed

- Update `DB_DATABASE` in `.env.example` ([#167](https://github.com/laravel/installer/pull/167))

## [v4.0.5 (2020-09-22)](https://github.com/laravel/installer/compare/v4.0.4...v4.0.5)

### Fixed

- Ensure artisan command is executable ([#153](https://github.com/laravel/installer/pull/153))
- Fix quiet and no-ansi flags ([#156](https://github.com/laravel/installer/pull/156))

## [v4.0.4 (2020-09-15)](https://github.com/laravel/installer/compare/v4.0.3...v4.0.4)

### Fixed

- Close `<fg>` tag ([#149](https://github.com/laravel/installer/pull/149))
- Add warning about `--force` and installing in current directory ([#152](https://github.com/laravel/installer/pull/152))

## [v4.0.3 (2020-09-08)](https://github.com/laravel/installer/compare/v4.0.2...v4.0.3)

### Fixed

- Fix for directories with spaces in current working directory path ([#147](https://github.com/laravel/installer/pull/147))

## [v4.0.2 (2020-09-08)](https://github.com/laravel/installer/compare/v4.0.1...v4.0.2)

### Added

- Add stack and teams options ([#143](https://github.com/laravel/installer/pull/143))

## [v4.0.1 (2020-09-07)](https://github.com/laravel/installer/compare/v4.0.0...v4.0.1)

### Changed

- Require PHP 7.3 ([#132](https://github.com/laravel/installer/pull/132))

### Fixed

- Fix multiple issues when running on Windows ([#133](https://github.com/laravel/installer/pull/133), [#137](https://github.com/laravel/installer/pull/137))
- Only change `.env` file when project name exists ([#140](https://github.com/laravel/installer/pull/140))

## [v4.0.0 (2020-09-03)](https://github.com/laravel/installer/compare/v3.2.0...v4.0.0)

### Changed

- Switch to `composer create-project` ([#124](https://github.com/laravel/installer/pull/124), [562650d](https://github.com/laravel/installer/commit/562650de8b637253b7ae47c3383bdd20e8419d1c), [8ab3502](https://github.com/laravel/installer/commit/8ab3502f1d5561d10cf1767213ec0c008baa145b))

## [v3.2.0 (2020-06-30)](https://github.com/laravel/installer/compare/v3.1.0...v3.2.0)

### Added

- Guzzle 7 support ([144a695](https://github.com/laravel/installer/commit/144a69576bfb0df2bbd5c7ae3f40dd87db64d0ba))

## [v3.1.0 (2020-05-21)](https://github.com/laravel/installer/compare/v3.0.1...v3.1.0)

### Removed

- Drop support for PHP 7.2 ([#118](https://github.com/laravel/installer/pull/118))

## [v3.0.1 (2019-11-26)](https://github.com/laravel/installer/compare/v3.0.0...v3.0.1)

### Fixed

- Fix composer autoloader path ([f3db3f3](https://github.com/laravel/installer/commit/f3db3f306c3c2dbbf4ecce4a5dbefe6c1fd178be))

## [v3.0.0 (2019-11-26)](https://github.com/laravel/installer/compare/v2.3.0...v3.0.0)

### Changed

- Move `laravel` binary to new directory ([c581a78](https://github.com/laravel/installer/commit/c581a784643911b97c3b8a2ec25ac809eadbf9c5))
- Require PHP 7.2 as the new minimum version ([3ab97f2](https://github.com/laravel/installer/commit/3ab97f2e454d9c95833ccdd141d2fdbcdc8e0066))
- Allow Symfony 5 ([513a060](https://github.com/laravel/installer/commit/513a060e9877bc8ab222d7ff4a60bc97131a0a0c))

### Removed

- Remove Symfony 3.x support ([a09d8fe](https://github.com/laravel/installer/commit/a09d8fe2ced9579d4fce445aa1336b0993e3e9d0))
- Remove `zipper.sh` ([78ef1db](https://github.com/laravel/installer/commit/78ef1dbe9ad2fbe5f16a85917748f89bb372599f))

## [v2.3.0 (2019-11-19)](https://github.com/laravel/installer/compare/v2.2.1...v2.3.0)

### Added

- Add `--auth` flag ([f5ebbff](https://github.com/laravel/installer/commit/f5ebbff32f9ff9c40fdf4c200cb2f396050e3cf3))

## [v2.2.1 (2019-10-29)](https://github.com/laravel/installer/compare/v2.2.0...v2.2.1)

### Fixed

- Make sure zip file is valid before extracting ([#100](https://github.com/laravel/installer/pull/100))

## [v2.2.0 (2019-10-15)](https://github.com/laravel/installer/compare/v2.1.0...v2.2.0)

### Added

- Create a new project in the current directory using "laravel new ." ([#99](https://github.com/laravel/installer/pull/99))

## [v2.1.0 (2019-04-30)](https://github.com/laravel/installer/compare/v2.0.1...v2.1.0)

### Added

- Added an alias to the `--force` option ([#79](https://github.com/laravel/installer/pull/79))

### Changed

- Use the `extension_loaded` method to check if the 'zip' extension is loaded ([#81](https://github.com/laravel/installer/pull/81))

### Fixed

- Respect `--quiet` option ([#77](https://github.com/laravel/installer/pull/77))
- Update composer path on `findComposer` ([#86](https://github.com/laravel/installer/pull/86))

## [v2.0.1 (2018-02-01)](https://github.com/laravel/installer/compare/v2.0.0...v2.0.1)

### Changed

- Update dependencies ([6e34188](https://github.com/laravel/installer/commit/6e341883b9ba45be6a06f40c8e2c1b5033029d99))

## [v2.0.0 (2018-02-01)](https://github.com/laravel/installer/compare/v1.5.0...v2.0.0)

### Changed

- Bump guzzle requirement ([f909b98](https://github.com/laravel/installer/commit/f909b983e1b57f13b5b102f4c0c0fc1883fcbe22))
