# Overview

## Goal of Estimation/Planning
Inform stakeholders when projects/features will be done

## Traditional Projects
- Team is given a project or feature request and asked when it will be done
	- Guess based on inaccurate/unknown/ambiguous information/requirements
	- Break down the project, maybe a gant chart


## Difference in Agile
- Agile flips that and asks, over the next `cycle`, what work can we accomplish
	- The completion date comes into focus as work gets done- We don't pick functionality then guess a date
- We pick a date, then plan the functionality we can accomplish

## Problems with the Traditional Approach

### Estimation is hard and inaccurate
- we are not good at it
	- optimists and pessimists on team..waste time arguing
	- time spent estimating does not generate more accuracy
	- software is ambiguous and hard to estimate
	- we know the least about a project/feature at the start
- humans are much better at relative estimation
	- comparing is much quicker and more accurate than deconstructing

> "It is better to be **roughly right** than **precisely wrong**."
	> *- John Maynard Keynes*

## Relative Estimation Game - Freezer Meals
```
1. Grilled Salmon
2. Spaghetti
3. Hot Dogs
4. Mac n' Cheese
5. Bologna Sandwich
6. Lasagna
7. Fajitas
8. Fried Rice
9. Pad Thai
10. Chocolate Chip Cookies 
11. Chili
12. Jello
13. Steak and Potatoes
14. Enchiladas 
```
### Steps
1. Relatively estimate the time it takes to prepare each Freezer Meal
2. Assign points to each column
3. It's our Friday off, so we can commit to preparing meals Friday, Saturday, and Sunday afternoon
	- Guesstimate how many points we can accomplish each afternoon
4. Plan the first afternoon's preparations
5. Determine velocity and plan Saturday's afternoon
6. Determine velocity and plan Sunday's afternoon
7. Replace the idea of *Freezer Meals* with *User Stories* and replace *you* with *our team*

### Fibonacci Scale
- implies exponentially rising difficulty
- `1, 2, 3, 5, 8, 13, 21`
- Points are completely arbitrary and have no correlation to time


## Estimation
1. Give each unit of work a `value` based on effort
2. Track how many `values` are completed each `cycle`
3. Calculate `velocity` (`values`/`cycle`) for the team

Velocity
: how much work is getting done per `cycle`

## Planning
1. What is the most important functionality we can fit into this `cycle`
2. We can extrapolate our `velocity` to project when a set of features will be done
3. 
## Units of Work
Epics > Features > Stories > Tasks

- **Data Quality Module**
	* *Issue Assignment*
		+ As an editor, I can reassign an issue
			+ Update UI
			+ Write Tests
			+ Implement Logic
			+ Send notification email
		+ As an editor, I can request help from EHS-DM
			+ Add database column
			+ Update UI
			+ Write Tests
			+ Implement Logic
			+ Send notification email



|Pros of Tasks|Cons of Tasks|
|----|----|
|More focused/accurate estimation|More time breaking down/organizing|
|Easier parallel efforts of team|Cluttered board|
---
> **Decision**: What level do we want to track?
---

	
# Pop-up Support Tasks
---
> **Decision**: do we track them on the board and include them in velocity?
---

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDIyODM3OTIxLC0yMTAxNjU0MDAwLDE5NT
UxNDg0NjEsLTkzNTY4OTAyOCwtMTI1MTE2OTY2NCwtMjQ0MDAz
MjM4LC0yNTc3OTExMzAsNTg1MzY0MDQsMTYzOTUwMzU4NCwtMj
E4MDQ2MzIzLC0xMzA0MDQ2OTcxLDEyODY3NDU1MDQsLTY4Mjgw
NDY5LC0xMTMyMjkzNTAwLDI5NjM3OTY0MCwtMTMwNDMyODM5NC
wxNDk0ODc4MjQ4LDk3NTU3NTY5MCwyNzgxMTM2MjAsMTEyNDMw
NDc5MV19
-->