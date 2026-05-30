# ERJuego

ERJuego is a 2D serious game designed to support the learning and practice of conceptual database modelling through Entity–Relationship (E/R) diagrams.

The game asks students to build an E/R diagram from textual requirements collected during gameplay. While students interact with the game, their actions are recorded in an event log that can later be used for learning analytics and educational process mining.

## Overview

At the beginning of the game, each player enters a unique identifier, which is stored in the event log. After that, the player can use the main menu to access the game map, the notepad, and the E/R diagram editor. The menu also includes an option to confirm the diagram and finish the session.

On the map screen, players collect textual requirements by visiting different buildings. When a building is selected, a character provides new information about the data model to be designed.

The notepad screen stores all requirements collected by the player. Each requirement is presented as one or two sentences, with relevant keywords highlighted to support the identification of entities, attributes, and relationships.

Finally, players design the E/R diagram in the editor screen. The editor includes an inventory of extracted keywords and a workspace where players can create, arrange, link, and delete diagram elements and set cardinalities. When the player confirms the diagram, the game generates an event log containing the interactions performed during the session.

## Event logging

The game records students' interactions during the modelling task, including actions such as creating and deleting entities, attributes, and relationships; linking and unlinking elements; and assigning cardinalities. These logs can be used to analyse students' modelling processes beyond their final diagram or score.

## Platforms

The game is intended to be built and distributed for:

- Windows
- GNU/Linux
- macOS

## Research use

This repository contains the source code of the serious game used in an educational study on interaction logs, serious game-based learning, and educational process mining.

## License

This project is distributed under the GNU General Public License v3.0 (GPL-3.0). See the `LICENSE` file for details.