## About

Я начинающий QA Engineer с фокусом на GameDev. У меня пока нет коммерческого опыта работы в студии, но есть практический опыт тестирования инди-игр, проектов с game jam’ов и некоммерческой передачи багов разработчикам.

Мне интересно не только находить ошибки, но и понимать, как они влияют на игровой опыт: игровые механики, UI, коллизии, логику уровней и поведение игрока. Я умею оформлять понятные bug reports, описывать шаги воспроизведения, указывать expected/actual result и предоставлять материалы, которые помогают разработчикам быстрее разобраться в проблеме.

В этом портфолио собраны примеры моих bug reports, чек-листов и QA-разборов игровых проектов. Я ищу возможность применить эти навыки в реальной GameDev-команде и развиваться как Game QA Engineer.


## Tools

- ClickUp / Jira / YouTrack
- Unreal Engine
- Slack / Discord
- Markdown
- OBS Studio/ShareX/LightShot
- Git, GitHub
- Google Sheets, Excel


## Skills

- Functional, exploratory, smoke and regression testing
- Testing gameplay mechanics, UI, levels, collisions and player interactions
- Writing clear bug reports with steps to reproduce, actual/expected results and evidence
- Creating checklists, test cases and QA notes
- Basic practical experience with Unreal Engine
- Capturing screenshots and videos for bug reports using OBS / ShareX
- Basic Git / GitHub workflow
- Understanding of player experience, edge cases and non-standard player behavior
- Clear communication, attention to detail and analytical thinking


## Bug Reports

<details>
<summary><strong>Bug - NPC Freezing</strong></summary>

#### Description:

Project: [KILLOVER](https://quentindelvallet.itch.io/killover)

In all modes, both in the browser version and the downloaded PC build, enemy NPCs freeze in place after some time if they remain alive. They stop moving and no longer interact with the gameplay.

#### Build:

Version 4

#### Platform:

PC, laptop

#### OS:

Windows 10

#### Steps to Reproduce:

1. Launch the game.
2. Wait until around the middle of the match in any mode.
3. Observe the NPC behavior.

#### Expected Result:

NPCs continue moving and attacking each other or the player.

#### Actual Result:

Some NPCs freeze in place around the middle of the match while still alive and stop moving.

#### Reproduction Rate:

100%

#### Severity:

Medium

#### Severity Reasoning:

The bug negatively affects gameplay and enemy NPC behavior, but it does not break the game or block match completion.

#### Attachments:

- Gameplay video


https://github.com/user-attachments/assets/b85dcace-006b-4d9a-bf5f-67185fc80be3



</details>

<details>
<summary><strong>Bug - Structure Gets Stuck Outside the Platform</strong></summary>

#### Description:

Project: [Draftula](https://joespacio.itch.io/draftula)

A building selected after placing the throne room does not disappear if it is released outside the castle-building platform, provided the player has enough gold.

#### Build:

Jam version — browser version and PC build

#### Platform:

PC, laptop

#### OS:

Windows 10

#### Steps to Reproduce:

1. Launch the game.
2. Start a new game or continue an existing one.
3. Place the throne room.
4. Pick up any available building before the building options disappear.
5. Release the building outside the platform where the castle is built.

#### Expected Result:

The building disappears after being released outside the platform.

#### Actual Result:

The building does not disappear and remains in place outside the platform.

#### Reproduction Rate:

100%

#### Severity:

Low

#### Severity Reasoning:

The bug does not affect gameplay.

#### Attachments:

- Gameplay video


https://github.com/user-attachments/assets/46d9275f-cf00-4468-b6cf-f1b5d143fcf5



</details>

<details>
<summary><strong>Bug - Fullscreen Checkbox State Is Not Updated</strong></summary>

#### Description:

Project: [Draftula](https://joespacio.itch.io/draftula)

In the browser version, when fullscreen mode is enabled in Settings and the Esc key is pressed, the game exits fullscreen mode, but the fullscreen checkbox remains enabled. In the PC build, pressing Esc does not affect fullscreen mode.

#### Build:

Jam version — browser version

#### Platform:

PC, laptop

#### OS:

Windows 10

#### Steps to Reproduce:

1. Launch the game.
2. Open Settings.
3. Enable fullscreen mode.
4. Press Esc.

#### Expected Result:

The game exits fullscreen mode and the fullscreen checkbox becomes unchecked.

#### Actual Result:

The game exits fullscreen mode, but the fullscreen checkbox remains checked. The player has to disable it manually.

#### Reproduction Rate:

100%

#### Severity:

Low

#### Severity Reasoning:

The bug does not affect gameplay.

#### Attachments:

- Gameplay video


https://github.com/user-attachments/assets/731fbcc4-747f-48ea-8410-b1d4f864a8bc



</details>


## Contact

- **Linkedin**: [linkedin.com/in/ruslan-kalaev-0a5596408](https://www.linkedin.com/in/ruslan-kalaev-0a5596408/)
- **Email**: [krinoilk@gmail.com](mailto:krinoilk@gmail.com)
- **GitHub**: [My GitHub Profile](https://github.com/Krinoil)
