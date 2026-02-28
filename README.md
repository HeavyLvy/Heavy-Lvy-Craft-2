# Heavy Lvy Craft 2

To build modpack for Modrinth or Curseforge run
```
./packwiz modrinth export
```
```
./packwiz curseforge export
```

If you're hosting a server with packwiz, set the packwiz url to
"https://github.com/HeavyLvy/Heavy-Lvy-Craft-2/raw/refs/heads/master/pack.toml"

You can install the modpack files via packwiz [bootstrapper](https://github.com/packwiz/packwiz-installer-bootstrap/releases)

```
java -jar packwiz-installer-bootstrap.jar https://github.com/HeavyLvy/Heavy-Lvy-Craft-2/raw/refs/heads/master/pack.toml --side server
```

by choosing the side of either `client`, `server`, or `both`, will install the correct mods.

