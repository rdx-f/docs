Uploaders must be admins of the PSP Homebrew Library, otherwise it will not be possible to add their uploads to the collection (not even by the admins of the collection).

## File structure

All homebrews must be compressed using the 7z format before uploading them.

The EBOOT file and its immediate contents must be placed at the root of the archive (as opposed to a subfolder).

## Metadata structure

1. Cover image:
	1. Any image uploaded in the root folder will be the cover image. Prefer in-game screenshots to artwork, menus or icons, as they provide a better impression of what the game looks like. 
1. **Subject Tags**:
	1. Pick one among 'game', 'application', 'emulator', 'demo', 'port'. Additional tags can be added where deeded relevant by the uploader. 
	- 'Ports' typically require files from the original game to work. 'Games' may be based on a previous game, but the assets are created anew. 
	1. If a game participated in a competition (e.g. the NEO 2008 competition), add the relevant tag.
	1. **Support tags**:
		1. 'PSP-2000+ only': if the game won't work on a PSP-1000 model.
		1. 'Go!Cam': game supports or requires the PSP camera.
		1. 'IrDA ': game/app supports or requires an infrared device.
1. **Creator** field:
	1. Where both the real names and nicknames of a creator are known, prefer real names (as those tend to change less often).
1. **Date**:
	1. When main version of the game/app (i.e., the most recent one included in the item) was released. If the game/app was previously unreleased, leave it blank. 
1. **Language**:
	1. Only if a language other than English, leave blank otherwise.
1. **License**:
	1. Only add if the game/app does mention a license within its content, and the license is available among the dropdown options - leave blank otherwise.
1. Additional metadata:
	1. **Version**: Add a custom field named 'version' whenever a version number is available. This will make it easier to keep the most recent version as the main one. 
	- If multiple versions are available: add older versions in an "Old Versions" folder within the main item (as separate 7z files).