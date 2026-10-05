# FLY-FPS

A browser-based 3D multiplayer FPS where everyone plays as a fly.

## Features
- Party-code multiplayer using WebRTC/PeerJS
- Up to 8 players
- Fly movement with a stamina system
- When stamina is empty, powered flight/boost is unavailable; you can walk and glide while stamina recovers
- Machine gun: 18 damage, rapid fire
- Sniper rifle: 100 damage and therefore one-shots a full-health fly
- Respawning, kills/deaths, health and stamina HUD
- 3D arena built entirely in the browser

## Controls
- WASD: move
- Space: powered flight / glide
- Shift: flight boost
- Mouse: aim and fire
- 1: machine gun
- 2: sniper rifle
- Esc: release mouse

## Running
Open `index.html` in a modern browser, or publish the repository with GitHub Pages.

The game uses Three.js and PeerJS from jsDelivr, while gameplay networking is peer-to-peer. The party code is the host's short PeerJS ID.
