# <p align = "center">**Embed**</p>

<br>

# <p align = "center">*Properties*</p>

<br>

## **Embed.title**: [string](https://create.roblox.com/docs/scripting/luau/strings) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The title of the webhook.

<br>
<hr>
<br>

## **Embed.description**: [string](https://create.roblox.com/docs/scripting/luau/strings) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The description of the webhook.

<br>
<hr>
<br>

## **Embed.url**: [string](https://create.roblox.com/docs/scripting/luau/strings) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The url of the webhook.

<br>
<hr>
<br>

## **Embed.timestamp**: [string](https://create.roblox.com/docs/scripting/luau/strings) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The timestamp of the webhook.

<br>
<hr>
<br>

## **Embed.footer**: [dictionary](https://create.roblox.com/docs/scripting/luau/tables#dictionaries) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The footer of the webhook.

<br>
<hr>
<br>

## **Embed.image**: [dictionary](https://create.roblox.com/docs/scripting/luau/tables#dictionaries) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The image of the webhook.

<br>
<hr>
<br>

## **Embed.thumbnail**: [dictionary](https://create.roblox.com/docs/scripting/luau/tables#dictionaries) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The thumbnail of the webhook.

<br>
<hr>
<br>

## **Embed.author**: [dictionary](https://create.roblox.com/docs/scripting/luau/tables#dictionaries) | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The author of the webhook.

<br>
<hr>
<br>

## **Embed.fields**: {[dictionary](https://create.roblox.com/docs/scripting/luau/tables#dictionaries)} | [nil](https://create.roblox.com/docs/scripting/luau/nil)
The title of the webhook.

<br>
<hr>
<br>

# <p align = "center">*Methods*</p>

<br>

## **Embed.new**(title: [string](https://create.roblox.com/docs/scripting/luau/strings)?, description: [string](https://create.roblox.com/docs/scripting/luau/strings)?, url: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [Embed](/docs/Embed.md)
This method returns a new Embed object.

Parameters:

- title: The title of the embed.
- description: The description of the embed.
- url: The url of the embed.

<br>
<hr>
<br>

## **Embed:_validate**(): ([boolean](https://create.roblox.com/docs/scripting/luau/booleans), [string](https://create.roblox.com/docs/scripting/luau/strings)?)
This method validates the embed to avoid making a pointless request to discord.

*Note: This method is not meant to be used outside Discohook's internal code.*


<br>
<hr>
<br>

## **Embed:setTitle**(title: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's title.

Parameters:

- title: The title of the embed.

<br>
<hr>
<br>

## **Embed:setDescription**(description: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's description.

Parameters:

- description: The description of the embed.

<br>
<hr>
<br>

## **Embed:setUrl**(url: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's url.

Parameters:

- url: The url of the embed.

<br>
<hr>
<br>

## **Embed:setTimestamp**(customTimestamp: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's timestamp.

*Note: If customTimestamp is left nil then the current timestamp will be used instead.*

Parameters:

- customTimestamp: A custom ISO8601 timestamp for the embed.

<br>
<hr>
<br>

## **Embed:setColor**(color3: [Color3](https://create.roblox.com/docs/reference/engine/datatypes/Color3)): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's color.

Parameters:

- color3: A color3 value.

<br>
<hr>
<br>

## **Embed:setFooter**(text: [string](https://create.roblox.com/docs/scripting/luau/strings), iconUrl: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's footer.

Parameters:

- text: The footer's text.
- iconUrl: The footer's url.

<br>
<hr>
<br>

## **Embed:setImage**(url: [string](https://create.roblox.com/docs/scripting/luau/strings), height: [number](https://create.roblox.com/docs/scripting/luau/numbers)?, width: [number](https://create.roblox.com/docs/scripting/luau/numbers)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's image.

Parameters:

- url: The image's url.
- height: The image's height.
- width: The image's width.

<br>
<hr>
<br>

## **Embed:setThumbnail**(url: [string](https://create.roblox.com/docs/scripting/luau/strings), height: [number](https://create.roblox.com/docs/scripting/luau/numbers)?, width: [number](https://create.roblox.com/docs/scripting/luau/numbers)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's thumbnail.

Parameters:

- url: The thumbnail's url.
- height: The thumbnail's height.
- width: The thumbnail's width.

<br>
<hr>
<br>

## **Embed:setAuthor**(name: [string](https://create.roblox.com/docs/scripting/luau/strings), url: [string](https://create.roblox.com/docs/scripting/luau/strings)?, iconUrl: [string](https://create.roblox.com/docs/scripting/luau/strings)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method sets the embed's author.

Parameters:

- name: The author's name.
- url: The author's url.
- iconUrl: The icon's url.

<br>
<hr>
<br>

## **Embed:addField**(name: [string](https://create.roblox.com/docs/scripting/luau/strings), value: [string](https://create.roblox.com/docs/scripting/luau/strings), inLine: [boolean](https://create.roblox.com/docs/scripting/luau/booleans)?): [nil](https://create.roblox.com/docs/scripting/luau/nil)
This method adds a field to the the embed.

Parameters:

- name: The field's name.
- value: The field's value.
- inLine: Whether the field should display inline.

<br>
<hr>
<br>

## **Embed:toDictionary**(): {[string](https://create.roblox.com/docs/scripting/luau/strings): [string](https://create.roblox.com/docs/scripting/luau/strings) | [number](https://create.roblox.com/docs/scripting/luau/numbers) | [nil](https://create.roblox.com/docs/scripting/luau/nil) | {[string](https://create.roblox.com/docs/scripting/luau/strings): [string](https://create.roblox.com/docs/scripting/luau/strings) | [number](https://create.roblox.com/docs/scripting/luau/numbers) | [boolean](https://create.roblox.com/docs/scripting/luau/booleans)}}
This method returns the embed in dictionary form.

<br>
<hr>
<br>

## **Embed:totalCharacters**(): [number](https://create.roblox.com/docs/scripting/luau/numbers)
This method returns the total amount of characters in the embed.

<br>
<hr>
<br>

## **Embed:colorToRGB**(): {[string](https://create.roblox.com/docs/scripting/luau/strings): [number](https://create.roblox.com/docs/scripting/luau/numbers)}
This method returns a dictionary representing the color.

<br>
<hr>
<br>