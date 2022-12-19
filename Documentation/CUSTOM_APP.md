# Using a custom application

The LiveSplit.Discord plugin uses a basic Discord Application that is provided for the user upon installation. However, one may create [a custom application](https://discord.com/developers/applications) and enter the Application ID in the settings menu. The only requirements for the application are for the assets and asset names to align with what the provided application has.

- ``livesplit_icon`` is the icon shown in the large image slot.
- ``gray_square`` is the icon for neutral (not running or no delta) 
  - Default hex color: #7b6b6e
- ``red_square`` is the icon for being behind 
  - Default hex color: #de2424
- ``green_square`` is the icon for being ahead 
  - Default hex color: #0eb85e

Outside of matching these asset names, everything else is up to the user.
