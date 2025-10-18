# Public Repository

1. Argon Combat HUD extenstion for Rolemaster Unitied (RMU): Integrates Argon Combat HUD for RMU with some additional features specifically for RMU
2. Visage: A system-agnostic module that allows a token's owner (player or GM) to add additional token art to the token within the token's configuration dialogue and then, via the token's HUD, quickly change both the token art and the actor's portrait so you can apply disguises, illusions, shapeshift forms, etc. It will store the original image paths and provide a quick way to return to the default images. This is purely a visual change of token and portrait image.

## Argon Combat HUD extension for Rolemaster Unified (RMU)

This project is a Foundry VTT module that integrates the "Argon - Combat HUD" module with the "Rolemaster Unified" (RMU) system. Its purpose is to provide a customized combat HUD for RMU that displays system-specific information and actions.

The module is written in JavaScript and uses the Foundry VTT API, the Argon Core HUD API and the RMU API.

Key features include:

*   A customised portrait panel showing HP, Power Points, and Defensive Bonus and with buttons to open character sheet and to roll initiative.
*   Integration with the RMU movement system.
*   Categorised attack buttons for Melee, Ranged, Natural, and Shield attacks.
*   Panels for Resistance Rolls, Skill Rolls, and Endurance Checks (Physical/Mental).
*   A "Rest" button to open the RMU rest dialog.
*   A search tool for skills. Just start typing and it will show any skills matching your text and the number of skillsfound on the right of the search bar. Click the clear icon in the search bar to reset the filter. There is a favourites toggle which will, when active, will only show skills marked as your favourites.
*   A combat panel to end turn when in combat.

It lets players and the GM do many actions without opening the character or creature sheet. Each action button has a rich tooltip showing the same data available in the sheet.


**Version History**

**Version 0.4.3**
*   Minor css change to consolidate styles

**Version 0.4.2**
*   Added favourite toggle in the skills search bar
*   Added a favourite "chip" on all skill buttons that are marked as favourite on the actor skills tab

**Version 0.4.1**
*   Added combat panel with an end turn button that is only visible when token is in combat and it is their turn.
*   Fixed missing css styles for skill category buttons introduced in v0.4.0
*   Verified roll initiative button works (in portrait panel).
*   Changed clear icon in the skills search bar and made it visible only when there is a filter applied.

**Version 0.4.0**
Code and css refactor.

**Version 0.3.2**
Minor code cleanup.

**Version 0.3.1**
The REST button now hides during combat (it is still accessible via the character sheet).

**Version 0.2.0**
Includes attack buttons, resistance rolls and the rest action.

**Version 0.3.0**
*   Added skill manouevre rolls. They can be found by clicking the skills panel button on the bottom bar then expanding the skill category to see the skills inside.
*   Added a custom search bar to find skills...just start typing and it will reveal any skills matching your text and show the number found on the right of the search bar. Click the clear icon in the search bar to reset the filter.
*   Added endurance rolls (physical and mental)
*   Updated a few more icons

**Roadmap**
*   Spells (waiting on a system dependency)
*   Items (waiting on a system dependency)

## Visage

tbd
