- "id" (required):
   - The unique identifier for the mod.
   - Rules: No spaces. Use dashes (-) instead.
   - Example: "id": "example-mod"

- "name" (required):
   - The display name of the mod. This is shown to users.
   - Example: "name": "Example Mod"

- "discord" (optional):
   - A Discord link for the mod or developer's community.
   - If there is no link, delete this line.
   - Example: "discord": "https://discord.gg/yourlink"

- "developers" (required):
   - The name(s) of the mod developer(s).
   - Example: "developers": "epic_mod_developer"

- "paid" (required):
   - Set to true if the mod is paid; otherwise, set to false.
   - Example: "paid": false

- "price" (conditionally required):
   - Include only if "paid" is set to true.
   - Example: "price": "1.00"

- "icon" (optional):
   - A direct image URL for the mod's icon or developer's avatar.
   - Example: "icon": "https://imgur.com/image123.png"

- "website" (optional):
   - A link to the mod’s website.
   - If there is no link, delete this line.
   - Example: "website": "https://google.com"

- "github" (optional):
   - A GitHub repository link for the mod.
   - If there is no link, delete this line.
   - Example: "github": "https://github.com/"

- "tags" (required):
   - Tags describing the mod.
   - Rules: Include 1-2 descriptive tags.
   - If the mod is a cheat mod, include "cheats" as a tag.
   - Example: "tags": ["skyblock", "dungeons"]
