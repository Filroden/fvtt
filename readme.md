## Argon Combat HUD extension for Rolemaster Unified (RMU)

This project is a Foundry VTT module that integrates the "Argon - Combat HUD" module with the "Rolemaster Unified" (RMU) system. Its purpose is to provide a customized combat HUD for RMU that displays system-specific information and actions.

The module is written in JavaScript and uses the Foundry VTT API, the Argon Core HUD API and the RMU API.

Key features include:

*   A customised portrait panel showing HP, Power Points, and Defensive Bonus.
*   Integration with the RMU movement system.
*   Categorised attack buttons for Melee, Ranged, Natural, and Shield attacks.
*   Panels for Resistance Rolls, Skill Rolls, and Endurance Checks (Physical/Mental).
*   A "Rest" button to open the RMU rest dialog.
*   A search tool for skills. Just start typing and it will show any skills matching your text and the number of skillsfound on the right of the search bar. Click the clear icon in the search bar to reset the filter.

It lets players and the GM do many actions without opening the character or creature sheet. Each action button has a rich tooltip showing the same data available in the sheet.

**Version History**

**Version 0.2.0**
Includes attack buttons, resistance rolls and the rest action.

**Version 0.3.0**
*   Added skill manouevre rolls. They can be found by clicking the skills panel button on the bottom bar then expanding the skill category to see the skills inside.
*   Added a custom search bar to find skills...just start typing and it will reveal any skills matching your text and show the number found on the right of the search bar. Click the clear icon in the search bar to reset the filter.
*   Added endurance rolls (physical and mental)
*   Updated a few more icons

**Version 0.3.1**
The REST button now hides during combat (it is still accessible via the character sheet).

**Version 0.3.2**
Minor code cleanup.

**Version 0.4.0**
Code and css refactor.

**Roadmap**
*   Spells (waiting on a system dependency)
*   Combat specific actions (roll initiative, end turn, etc)
