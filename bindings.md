---
layout: post
title:  "Bindings"
date:   2014-03-16 11:01:52
---

| Keybindings        | Interactive commands                                  | Description
|--------------------|-------------------------------------------------------|----------------------------------------------------------------------------------------------
|                    | <kbd>M-x org-trello/version</kbd>                     | current version
| <kbd>C-c o i</kbd> | <kbd>M-x org-trello/install-key-and-token</kbd>       | Install the keys and the access-token.
| <kbd>C-c o I</kbd> | <kbd>M-x org-trello/install-board-and-lists-ids</kbd> | Connect buffer to board
| <kbd>C-c o d</kbd> | <kbd>M-x org-trello/check-setup</kbd>                 | Check that the setup is ok
| <kbd>C-c o D</kbd> | <kbd>M-x org-trello/delete-setup</kbd>                | Clean the org buffer from all org-trello informations
| <kbd>C-c o b</kbd> | <kbd>M-x org-trello/create-board</kbd>                | Create a board and attach the org-mode file to it
| <kbd>C-c o c</kbd> | <kbd>M-x org-trello/sync-entity</kbd>                 | Sync an entity (card/checklist/item)
| <kbd>C-c o C</kbd> | <kbd>M-x org-trello/sync-full-entity</kbd>            | Sync full entity and its subtree
| <kbd>C-c o s</kbd> | <kbd>M-x org-trello/sync-to-trello</kbd>              | Sync org file to board
| <kbd>C-c o S</kbd> | <kbd>M-x org-trello/sync-from-trello</kbd>            | Sync org file from board
| <kbd>C-c o k</kbd> | <kbd>M-x org-trello/kill-entity</kbd>                 | Kill the entity from the board/org buffer
| <kbd>C-c o K</kbd> | <kbd>M-x org-trello/kill-all-entities</kbd>           | Kill all entities the from the board/org buffer
| <kbd>C-c o a</kbd> | <kbd>M-x org-trello/assign-me</kbd>                   | Assign yourself to the card
| <kbd>C-c o u</kbd> | <kbd>M-x org-trello/unassign-me</kbd>                 | Unassign from the card
| <kbd>C-c o j</kbd> | <kbd>M-x org-trello/jump-to-card</kbd>                | Jump to current trello card
| <kbd>C-c o J</kbd> | <kbd>M-x org-trello/jump-to-trello-board</kbd>        | Jump to current trello board
| <kbd>C-c o h</kbd> | <kbd>M-x org-trello/help-describing-bindings</kbd>    | This help message.