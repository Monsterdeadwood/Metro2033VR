# Metro 2033 VR — project status

[← Project page](../README.md) · [Flat2VR testing & discussion](https://discord.gg/P4q9zt7ek)

Reviewed **14 November 2026**. Documented branch: **Original Metro 2033 / local interaction branches**.

## What has been checked

- The powered-core branch recorded native flight, seven static rebounds, return and cleanup in the actual game with XR Sim, including a separate cold-start repeat.
- Enemy-reaction checks are separate runs on one armed human; strong-hit recovery resumed original firing in the checked scenario.

## Current limits

- These experiments do not establish a complete playable campaign or physical-headset acceptance.
- Universal enemy/mutant reactions, weak-hit armed recovery, all collision geometry and sound/feel remain open.

## Separate experimental work

- Physics and enemy-reaction branches keep their individual test scopes; features from different runs are not presented as one finished build.

## Build access

Ask for the current complete test package in the game’s Flat2VR thread. A local build record does not by itself mean a file has been uploaded to this repository’s Releases.

## Documentation basis

This overview was reconciled against the project’s recorded package notes and validation records. The following names identify the records reviewed; they are not download links:

- `METRO_POWERED_CORE_20261114/REVIEW.txt`
- `METRO_NATIVE_ENEMY_REACTIONS_20261114/REVIEW.txt`

Game execution, simulator validation and physical-headset feedback are reported separately above. Features from a separate experimental branch are identified explicitly.

## Кратко по-русски

Экспериментальный проект VR и взаимодействий для оригинальной PC-версии Metro 2033. Локальная работа исследует взаимодействие от контроллеров, родные тела PhysX, полёт предметов, освещение и реакции врагов.

- Эти эксперименты не подтверждают полностью игровую кампанию и принятие в физическом шлеме.
- Все враги/мутанты, вооружённая поза после слабого удара, вся геометрия коллизии и звук/ощущения ещё требуют работы.
