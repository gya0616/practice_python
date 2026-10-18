# StudyHub — Interface and Example Usage

## Interface

StudyHub is a **command-line app** for managing student practice scores, assignments, and rewards. Select a student, then choose from the main menu:

1. **Play practice game** — Guess a number to earn points.
2. **View grade report** — View scores, averages, grades, and points.
3. **Manage assignments** — Add, complete, filter, or delete assignments.
4. **View class statistics** — Compare scores and completion rates.
5. **Shop for rewards** — Browse rewards and spend points.
6. **Exit** — Close the application.

**Hidden admin shortcut:** At the main menu, press **Shift+A**, then **Enter** (input `A`). This option must **not appear in the menu**. It opens an admin screen with these actions:

- **List rewards** — Show each item's ID, name, and point cost.
- **Add reward** — Enter a name and point cost to add an item to the shop.
- **Remove reward** — Enter an existing item ID to remove it.
- **Back** — Return to the main menu.

## Example Usage

```text
Welcome to StudyHub!
Choose a student: 1. Alice  2. Bob
> 1

1. Play game  2. Grades  3. Assignments
4. Statistics  5. Rewards  6. Exit
> A

[Admin — Reward Catalog]
1. List rewards  2. Add reward  3. Remove reward  4. Back
> 2
Reward name: Extra break
Point cost: 150
Added "Extra break" (ID: 3).

> 3
Reward ID: 2
Removed "Badge".

> 4
1. Play game  2. Grades  3. Assignments
4. Statistics  5. Rewards  6. Exit
> 5
Rewards: 1. Break pass (100 pts)  3. Extra break (150 pts)
Choose reward: 3
Purchased Extra break. Remaining points: 90
```