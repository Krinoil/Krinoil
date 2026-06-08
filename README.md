## About

Меня зовут Руслан, я начинающий QA Engineer с фокусом на GameDev. У меня пока нет коммерческого опыта работы в студии, но есть практический опыт тестирования инди-игр, проектов с game jam’ов и некоммерческой передачи багов разработчикам.

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
<summary><strong>Bug - Collision Overlap</strong></summary>

#### Description:

Project: [Blueprint Bob](https://suumpmolk.itch.io/blueprint-bob)

Object can be placed overlapping the player, causing the player to become stuck and unable to move (only in browser version).

#### Build:

Jam version — browser version.

#### Platform:

PC, laptop.

#### OS:

Windows 10.

#### Steps to Reproduce:

1. Start the game.
2. Overlap player unit by any object.
3. Push start.
  
#### Expected Result:

Avoid overlapping.

#### Actual Result:

Object overlapping and lock the player unit.

#### Reproduction Rate:

100%

#### Severity:

Medium

#### Severity Reasoning:

Negatively impacts the game experience. But is easily avoided or corrected by the player.

#### Attachments:

- Gameplay video


https://github.com/user-attachments/assets/c496a678-5256-48af-aa8c-5a652b8a2c7b



</details>


<details>
<summary><strong>Bug - Player Gets Stuck Between Box and Ceiling</strong></summary>

#### Description:

Project: [Loop/death](https://fankyu.itch.io/deathlooptype)

In level 2 the player gets stuck between the box and the ceiling and can`t move.

#### Build:

Jam version — browser version.

#### Platform:

PC, laptop

#### OS:

Windows 10

#### Steps to Reproduce:

1. Launch the game.
2. Load level 2.
3. Push the box all the way against the wall.
4. Continue pushing and try to jump onto the box.

#### Expected Result:

The player either jumps onto the box successfully or the jump is blocked if there is not enough space.

#### Actual Result:

The player can jump onto the box, but gets stuck and can`t move.

#### Reproduction Rate:

100%

#### Severity:

High

#### Severity Reasoning:

The player gets stuck in place, making it impossible to complete the level.

#### Attachments:

- Gameplay video


https://github.com/user-attachments/assets/02db78ab-c9d6-4922-a6db-e708bf6da8be



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


## Checklists

<details>
<summary><strong>Movement, Box Interaction and Collision Checklist</strong></summary>


- Project: 2D Platformer Game

- Tested area: Player movement, box interaction, collisions

- Tester: Junior QA Engineer

- Purpose: Check that the player can move, interact with the box, and complete the level without getting stuck.


| ID    | Area              | Check                                                                       |
| ----- | ----------------- | --------------------------------------------------------------------------- |
| CH-01 | Player Movement   | Check that the player can move left and right.                              |
| CH-02 | Player Movement   | Check that the player stops when movement input is released.                |
| CH-03 | Player Movement   | Check that the player cannot move through walls.                            |
| CH-04 | Jumping           | Check that the player can jump from the ground.                             |
| CH-05 | Jumping           | Check that the player lands correctly after jumping.                        |
| CH-06 | Jumping           | Check that the player cannot jump through the ceiling.                      |
| CH-07 | Box Interaction   | Check that the player can push the box.                                     |
| CH-08 | Box Interaction   | Check that the box moves when the player pushes it.                         |
| CH-09 | Box Interaction   | Check that the box stops when pushed against a wall.                        |
| CH-10 | Box Interaction   | Check that the box does not pass through the wall or floor.                 |
| CH-11 | Box Interaction   | Check that the player can jump onto the box if this is intended by design.  |
| CH-12 | Box Interaction   | Check that the player can jump back down from the box.                      |
| CH-13 | Collision         | Check that the player does not get stuck between the box and the wall.      |
| CH-14 | Collision         | Check that the player does not get stuck between the box and the ceiling.   |
| CH-15 | Collision         | Check that the player does not get stuck while standing on or near the box. |
| CH-16 | Collision         | Check that the player’s movement is not blocked after pushing the box.      |
| CH-17 | Level Progression | Check that the level can still be completed after moving the box.           |
| CH-18 | Level Progression | Check that the player cannot easily block the main path with the box.       |
| CH-19 | Restart           | Check that restarting the level resets the player position correctly.       |
| CH-20 | Restart           | Check that restarting the level resets the box position correctly.          |



</details>


## Test Cases

<details>
<summary><strong>Verify that the player can safely interact with the box</strong></summary>

### Test Case ID: TC-01

- Title: Verify that the player can safely interact with the box
  
- Project: 2D Platformer Game
  
- Feature/Area: Player Movement, Box Interaction, Collision
  
- Priority: Medium
  
- Test Type: Functional

### Preconditions

 1. The game is launched.
 2. The required level is loaded.
 3. The player is near the movable box. 
 4. The box can be pushed by the player.  
 5. There is a platform/ceiling above or near the box.

### Test Steps

| Step | Action                                                        | Expected Result                                                                                        |
| ---- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| 1    | Move the player to the box.                                   | The player moves to the box without any issues.                                                        |
| 2    | Push the box toward the wall/platform area.                   | The box moves correctly and stops when it reaches an obstacle.                                         |
| 3    | Try to jump onto the box.                                     | The player either jumps onto the box successfully or the jump is blocked if there is not enough space. |
| 4    | Try to move left and right while standing on or near the box. | The player can move normally and does not get stuck.                                                   |
| 5    | Try to jump down from the box.                                | The player can jump down and continue moving.                                                          |
| 6    | Continue playing the level.                                   | The player can continue the level without losing control or getting stuck.                             |

### Expected Result

The player can interact with the box near the platform without getting stuck. If there is not enough space, the game should prevent the player from entering the collision area.


</details>



## Contact

- **Telegram**: [@Krinoil](https://t.me/Krinoil)
- **Email**: [krinoilk@gmail.com](mailto:krinoilk@gmail.com)
- **GitHub**: [My GitHub Profile](https://github.com/Krinoil)
