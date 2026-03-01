<p align="center">
  <img src="images/Heavy-Lvy.png" width="600"/>
</p>
<p align="center">
  <img src="images/Craft-II.png" width="300"/>
</p>

To build mod pack for Modrinth or Curseforge run

```
./packwiz modrinth export
```

```
./packwiz curseforge export
```

If you're hosting a server with packwiz, set the packwiz url to
"https://github.com/HeavyLvy/Heavy-Lvy-Craft-2/raw/refs/heads/master/pack.toml"

If you're using packwiz [bootstrapper](https://github.com/packwiz/packwiz-installer-bootstrap/releases) use this command to install/update the mod pack

```
java -jar packwiz-installer-bootstrap.jar https://github.com/HeavyLvy/Heavy-Lvy-Craft-2/raw/refs/heads/master/pack.toml --side server
```

by choosing the side of `client`, `server`, or `both`, will install the corresponding mods.
