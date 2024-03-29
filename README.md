# sublayer-blueprints README

This plugin integrates with sublimetext to send chunks of code to Sublayer's
blueprint server as a new blueprint and generate new code based off existing
blueprints using descriptions of what you're working on.

## Installation

Navigate to your sublime texts packages folder (Sublime Text > Settings... > Browse Packages)

Run `git clone git@github.com:sublayerapp/blueprints_subl.git`

Restart Sublime Text

## Features

Capture chunks of code and save them as blueprints to then later be used in the
future as bases to generate new code off of.

## Usage

Command Palette [command+shift+p] will now have:

`Blueprint: Submit Blueprint` - This command takes whatever code you
have highlighted and submits it to your locally running Sublayer Blueprints
server to save it as a blueprint for future use.

`Blueprint: Replace Selection` - This command takes whatever text you have
highlighted and sends it to your locally running Sublayer Blueprints server and
replaces it with a variation based on a blueprint you have stored in the past.

feel free to add whichever keybindings you would like in Sublime Text > Settings... > Key Bindings
```
  {
    "keys": ["ctrl+shift+s"],
    "command": "sublayer_blueprints_submit_blueprint"
  },
  {
    "keys": ["ctrl+shift+g"],
    "command": "sublayer_blueprints_replace_selection"
  }
```
## Requirements

A [Sublayer Blueprints](https://github.com/sublayerapp/blueprints) server running locally on port 3000

### 1.0.0

Initial release of Sublayer Blueprints Plugin

## Community

Like what you see, or looking for more people working on the future of
programming with LLMs? Come join us in the [Promptable Architecture
Discord](https://discord.gg/sjTJszPwXt)

