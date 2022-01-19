# alFa-Northstar-mods
mods for R2Northstar used by alFa

# alFa.Moderator
Installation:
Download the latest Release zip file from https://github.com/FrostySn0men/alFa-Northstar-mods/releases
Extract Alfa.Moderator.zip
Copy, recursively, directory Alfa.Moderator to your server's R2Northstar\mods directory.

Configuration:
Modify the mod.json file - updating the "moderators" DefaultValue to a comma seperated list of User NAMES to grant Moderator access:

	"ConVars": [
		{
			"Name": "moderators",
			"DefaultValue": "FrostySn0men,fr0kn"
		}
	],


Use:
Open console (use ` aka backtick, aka incorrectly as tilde) and type one of the following in your client:
modkick <OriginName>
modban <OriginName>
modunban <OriginName>
