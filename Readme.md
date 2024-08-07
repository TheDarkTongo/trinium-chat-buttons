# Trinium Chat Buttons

[![Latest Release](https://img.shields.io/github/v/release/thedarktongo/trinium-chat-buttons)](https://github.com/thedarktongo/trinium-chat-buttons/releases/latest)
[![License](https://img.shields.io/github/license/thedarktongo/trinium-chat-buttons)](https://github.com/thedarktongo/trinium-chat-buttons/blob/main/LICENSE.md)
[![Discord](https://img.shields.io/discord/1264218090061955132?label=Discord)](https://discord.gg/6KUmpqef)


Trinium Chat Buttons is a Foundry VTT module that adds several new buttons below the chat.

# Features

![GM Buttons](https://github.com/TheDarkTongo/trinium-chat-buttons/blob/main/media/examples/buttons-GM.png)

- **GM Screen**: Show a customizable, tabbed, highly configurable, editable GM Screen. Expands as a sidebar or large screen. Supports Markdown, HTML, Journals and Enrichers with live preview.
- **Roll Privacy Buttons**: Switch between different roll types (Public Roll, GM Roll, Self Roll, Blind Roll) using buttons instead of a dropdown.
- **MIDI QOL Buttons**: Toggle MIDI QOL features on and off and visualize its keybindings. Requires [Midi QOL](https://gitlab.com/tposney/midi-qol).
- **Mini Combat Tracker**: Compact, feature-packed and easy to use. 
- **Utility Buttons**: Player: Roll initiative, Find My Token. GM: Roll NPCs, Select all players/npcs, Select random token

# Usage

## GM Screen

Everything you need to know at the click of a single button! Try it in the super-compact Sidebar mode or Bottom Mode as seen here:

![GM Screen Bottom mode](https://github.com/TheDarkTongo/trinium-chat-buttons/blob/main/media/examples/gm-screen.png)

#### Features

- **Built-in Editor:** Fully editable content to keep exactly the information you want at your fingertips. Supports Markdown and HTML with live preview.
- **Journals**: Drag and drop a journal page to add it to the GM Screen!
- **Enrichers**: Drag and drop an item, actor etc to add a link to it in the GM Screen.
- **Sections:** Up to 4 columns and 3 rows for a total of up to 12 sections! 
- **Tabs:** A total of 12 tabs to choose from so you can keep it as compact as you wish
- **Customizable Sizes:** Open from the right, left or bottom and customize width, height and more.
- **Presets:** Add preset info and cheat sheets to the GM Screen with the click of a button. Submissions are welcome!

## Roll Privacy and MIDI Buttons

These roll privacy buttons replace the traditional dropdown menu for selecting the roll mode, reducing necessary clicks to 1. Efficient!

If [Midi QOL](https://gitlab.com/tposney/midi-qol) is active, additional buttons will appear for:
- Fast Forward all rolls
- Auto Roll/Fast Forward rolls
- Advantage
- Disadvantage

#### Polling Power
Look, no (mouse) hands! If polling is enabled in the settings, Buttons also automatically update to show you which Midi modifier key you're holding.

![Midi Polling](https://github.com/TheDarkTongo/trinium-chat-buttons/blob/main/media/examples/buttons-midi-polling.gif)

**Note:** The toggle affects the same variables as Midi: Holding Midi keybindings and then releasing them will turn off the button.

## Combat Tracker

The GM gets quick and easy controls, the player gets no spoilers. Yes, it also has a glowing End Turn button!

![Combat Tracker GM and Player View](https://github.com/TheDarkTongo/trinium-chat-buttons/blob/main/media/examples/combat-tracker-gm-player-view.gif)

#### Features

- **Combatant List:** Displays all active combatants with their initiative, name, image, and health.
- **Health Bar:** Visual representation of combatant's health with color indicating health status.
- **Disposition Colors:** Background colors to indicate if a combatant is an ally (green), enemy (red), neutral (yellow) or secret (purple). 
- **Defeated Status:** Visual indication (strikethrough and red background) for defeated combatants.

- **Masking:**
    - **Names:** All NPC names are set to "Creature" for non-GM players.
    - **Hidden NPCs:** Tokens set to invisible have a grey background for GM players and are hidden to non-GM players.
    - **Health:** Players can't see NPC Health and Healthbar. Can be configured in settings.
    - **Hide until turn:** Before combat and on the first round, players can't see NPCs who haven't acted yet.

#### Shortcuts
- **Click Combatant:** Select token.
- **Double Click Combatant:** Open character sheet.
- **Click Initiative:** Set Initiative.
- **Right Click Combatant**:
  - Clear Initiative
  - Reroll Initiative
  - Set Initiative
  - Set Turn to this Combatant
  - Toggle Token Visibility
  - Toggle Defeated Status
  - Change Disposition (Neutral, Friendly, Enemy, Secret)

## Additional Buttons next to the Mini Tracker
- **GM: Roll all NPC initiatives** 
- **GM: Select all player tokens. Doubleclick to select all NPCs** 
- **GM: Pick one selected token at random. If none selected, pick a random player** 
- **Player: Find and select my token**
- **Player: Own initiative roller**

## Additional CSS Changes

Additional changes that improve readability of the sidebar can be enabled in the module settings.

## Support

If you encounter any issues or have suggestions for improvements, please open an issue on the [GitHub repository](https://github.com/thedarktongo/trinium-chat-buttons/issues).

## Contributing

Contributions are welcome and appreciated! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

The roll privacy buttons are Inspired by [DF Chat Enhancements](https://github.com/flamewave000/dragonflagon-fvtt/tree/master/df-chat-enhance).
Special thanks to Tim Posney for creating [Midi QOL](https://gitlab.com/tposney/midi-qol).

This project includes the following third-party libraries:

- **Marked** - A Markdown parser and compiler. Built for speed. Used for Markdown to HTML parsing in the GM screen. You can find more information about it [here](https://github.com/markedjs/marked).
