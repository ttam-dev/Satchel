<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/SatchelWhite.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/SatchelBlack.png">
    <img alt="Satchel" src="assets/SatchelBlack.png">
  </picture>
  &nbsp;
</h1>

Satchel is a modern open-source alternative to Roblox's default backpack. Satchel aims to be more customizable and easier to use than the default backpack while still having a "vanilla" feel. Installation of Satchel is as simple as dropping the module into your game and setting up a few properties if you like to customize it. It has a familiar feel and structure as to the default backpack for ease of use for both developers and players.

<img alt="Satchel on computer" src="assets/SatchelThumbnail1.png" style="width: 49%;"> <img alt="Satchel on computer with inventory open" src="assets/SatchelThumbnail2.png" style="width: 49%;">
<img alt="Satchel on mobile" src="assets/SatchelThumbnail3.png" style="width: 49%;"> <img alt="Satchel on mobile with inventory open" src="assets/SatchelThumbnail4.png" style="width: 49%;">

<https://github.com/RyanLua/Satchel/assets/80087248/2cd3f164-6bf3-4c3b-a682-67a386f576d5>

## ⭐ Features

Satchel comes packed with much-needed features and changes that the default backpack doesn't have.

### Modernized Familiar Feel

Satchel completely remakes the backpack's UI to a uniform and vanilla feeling UI, blending in with other elements designed by Roblox.

### Highly Customizable & Versatile

Satchel is highly customizable & adjustable with instance attributes support allowing you to customize the behavior and appearance of over 10+ attributes. Change the color, transparency, behavior, and more of it's elegantly designed UI.

### Improved Mobile Experience

Satchel expands on the mobile experience doubling the number of slots allowing players on mobile to not be at a disadvantage.

<div align="center">
  <img alt="Satchel on mobile with 6 hotbar slots" src="assets/SatchelThumbnail4.png" style="width: 49%;">
</div>

### Topbar Plus Support

Satchel supports [Topbar Plus by 1ForeverHD](https://github.com/1ForeverHD/TopbarPlus) to allow users to easily and more quickly open the inventory.

## 👤 Acknowledgements

A special thanks to the following people for their contributions to Satchel.

| Roblox Username | Contribution |
| --- | --- |
| [@OnlyTwentyCharacters](https://www.roblox.com/users/28969907), [@SolarCrane](https://www.roblox.com/users/29373363) | Creating the original CoreGui script |
| [@thebrickplanetboy](https://www.roblox.com/users/525495863) | Allowing me to republish & modify his fork of the backpack system |
| [@ForeverHD](https://www.roblox.com/users/82347291) | Making Topbar Plus and open-sourcing it for everyone to use |
| [@stravant](https://www.roblox.com/users/80119) | For creating Signal module |

## 💖 Support

> [!NOTE]
> If you see an issue with Satchel and would like to report it, see [SUPPORT.md](.github/SUPPORT.md) for additional information.

Satchel fully supports all platforms which includes computer, tablet, phone, console, and VR. Satchel is also fully compatible experiences using TopbarPlus by 1ForeverHD.

## 📖 Documentation

> [!NOTE]
> Visit the [Satchel documentation website](https://satchel.ryanluu.dev) to learn about Satchel.

Satchel has it's very own [documentation site](https://satchel.ryanluu.dev) you can visit. Find guides on how to get started and documentation.

<details>

<summary>Attributes</summary>

Satchel supports instance attributes allowing you to change and customize many aspects including various behaviors in a friendly easy-to-use interface without having to touch any code. Below see all attributes.

| Attribute | Description | Default |
| :--- | :--- | :--- |
| BackgroundColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the background color of the default inventory window and slots. | `[25, 27, 29]` |
| BackgroundTransparency: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the background transparency of the default inventory window and slots. | 0.3 |
| CornerRadius: [`UDim`](https://create.roblox.com/docs/reference/engine/datatypes/UDim) | Determines the radius, in pixels, of the default inventory window and slots. | `0, 8` |
| EquipBorderColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the color of the equip border when a slot is equipped. | `[255, 255, 255]` |
| EquipBorderSizePixel: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the pixel width of the equip border when a slot is equipped. | `5` |
| FontFace: [`Font`](https://create.roblox.com/docs/reference/engine/enums/Font) | Determines the font of the default inventory window and slots. | `Builder Sans` |
| InsetIconPadding: [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) | Determines whether or not the tool icon is padded in the default inventory window and slots. | True |
| OutlineEquipBorder: [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) | Determines whether or not the equip border is outline or inset when a slot is equipped. | True |
| TextColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the color of the text in default inventory window and slots. | `[255, 255, 255]` |
| TextSize: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the size of the text in the default inventory window and slots. | `14` |
| TextStrokeColor3: [`Color3`](https://create.roblox.com/docs/reference/engine/datatypes/Color3) | Determines the color of the text stroke of text in default inventory window and slots. | `[0, 0, 0]` |
| TextStrokeTransparency: [`number`](https://create.roblox.com/docs/scripting/luau/numbers) | Determines the transparency of the text stroke of text in default chat window and slots. | 0.5 |

</details>

<details>

<summary>Methods</summary>

Satchel offers access to some of its internal methods and events for scripting purposes. Below see a table with all the methods available.

| IsOpened(): [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) |
| :--- |
| Returns whether the inventory is opened or not. |

| SetBackpackEnabled(enabled: boolean): `void` |
| :--- |
| Sets whether the backpack gui is enabled or disabled. |

| GetBackpackEnabled(): [`boolean`](https://create.roblox.com/docs/scripting/luau/booleans) |
| :--- |
| Returns whether the backpack gui is enabled or disabled. |

| GetStateChangedEvent(): [`RBXScriptSignal`](https://create.roblox.com/docs/reference/engine/datatypes/RBXScriptSignal) |
| :--- |
| Returns a signal that fires when the inventory is opened or closed. |

</details>

## 🙏 Contributing

We welcome all contributions from the community. If you would like to contribute, please see [CONTRIBUTING.md](.github/CONTRIBUTING.md) to get started on how to contribute to Satchel.

When you contribute to Satchel you will be accredited for your contribution for everyone to see on this repository along with supporting the open-source community.

## 📃 License

Satchel is licensed under [Mozilla Public License 2.0](http://mozilla.org/MPL/2.0/). See [LICENSE.txt](LICENSE.txt) for details.
