# Modded Work Carts

Allows making modifications to Work Carts, such as adding Auto Turret, Storage

## Permissions

This plugin uses Oxide's permission system. To assign a permission, use `oxide.grant <user or group> <name or steam id> <permission>`. To remove a permission, use `oxide.revoke <user or group> <name or steam id> <permission>`.

* `moddedworkcarts.placeturret` -- Allows players to use the commad  `/workcartturret`

## Chat Commands

* `/workcartturret` -- Allows players with permission to spawn a Auto Turret on a Work Cart

## Configuration

The settings and options can be configured in the `ModdedWorkCarts` file under the `config` directory. The use of a JSON editor or validation site such as [jsonlint.com](https://jsonlint.com/) is recommended to avoid formatting issues and syntax errors.

``` json
{
  "Add a Auto Turret on top of the driver cabin": false,
  "Add Storage Boxes on top of the fuel deposit": false,
  "Add chairs at the back of the Work Cart": false,
  "Turret Command Cooldown in Minutes (If 0 there will be none)": 0
}
```

## Localization

The default messages are in the `ModdedWorkCarts` file under the `oxide/lang/en` directory. To add support for another language, create a new language folder (e.g. `de` for German) if not already created, copy the default language file to the new folder and then customize the messages.

