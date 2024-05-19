# simple-mod-framework
A mod framework for HITMAN 3 that allows the automatic synthesis of mods from source files.

Main.ts modified.
Deleted:
`
if (typeof core.config.platform === "undefined") {
	await core.logger.error(
		"Could not detect a workable game copy! If the game has recently updated, the framework will also need an update. If you're using a cracked version, that sounds like a you problem."
	)
}
`
