# DASTraderConfig

Configuration files for DAS Trader Pro and Stream Deck.

## Overview

This repository contains my personal DAS Trader Pro and Stream Deck configuration files for reference and educational purposes. The desktop and chart layouts plus Stream Deck profiles are designed to work with my hotkeys and tooling. Please review and adapt anything you use to match your account settings, broker rules, and hardware setup.

## Requirements

- Hotkeys repository: https://github.com/madiver/DASTraderScripts
- DAS Hotkey Tools VS Code extension: https://github.com/madiver/dasVSide
- Tested with DAS Trader Pro 5.8.1.6

## Repository Layout

- `DASTrader/` - DAS Trader Pro configuration, hotkeys, and layouts.
- `StreamDeck/` - Stream Deck profiles, buttons, and assets.

## Setup

The desktop profile was set up on a 3840x2160 monitor, so you may need to adjust layouts for other resolutions.

After loading my hotkeys, set your account numbers for `$TRLIVE` and `$TRSIM` in the "Set Global Variables* hotkey script if not already set if you used the DAS Hotkey Tools extension. 

The desktop uses two layered position windows: "Positions - Live" and "Positions - Simulator." Only one is on top at a time. The Position, Orders, and Trades windows switch between Live and Sim using the dedicated mode hotkeys, and the colored button at the bottom of the order entry montage is a visual indicator of the current mode. If the position window gets out of sync, use the "Toggle Pos" hotkey to bring the correct position window to the front.

After loading the desktop the first time, configure the account filters:
- Right-click "Positions - Live" and set "Only Show These Accounts" to your live account number.
- Right-click "Positions - Simulator" and set "Only Show These Accounts" to your simulator account number.

If you prefer, you can separate the two position windows so both are visible at the same time.

## Risk Disclaimer

These configuration files are provided "as is" and are used at your own risk. Always review and test changes before use in DAS Trader or Stream Deck.
- I make no warranties or guarantees that these configurations are correct or bug free.
- Test changes in SIM and confirm order routes, share sizes, and risk controls.
- Hotkeys can place, modify, or cancel orders instantly; mistakes can be costly.
- You are responsible for compliance with broker rules, account settings, and regulatory requirements.
