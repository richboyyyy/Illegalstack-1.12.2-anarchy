# IllegalStack - EgirlsNation edition
A spigot based plugin dedicated to fixing glitches and exploits that have made it into final Minecraft... But not quite.


## How to?
1. Grab the precompiled plugin in the releases tab or build it yourself (alternativelly you can download development builds from the actions tab).
2. Install it on your server.
3. Enable "DisableChestsOnMobs".
4. Put chest on donkey while canceling PlayerInteractEntityC2S packet (MountBypass module).
5. Put items you want to dupe in.
6. Click the donkey with chest again, this time without canceling the packet.
7. Profit?
8. Spice things up and name the donkey "popbob sex".

## EgirlsNation links
- [Website](https://egirlsnation.com/)
- [Discord](https://discord.egirlsnation.com/)
- [Dev Builds](https://github.com/Lerbiq/IllegalStack/actions)
- IP - play.egirlsnation.com

## Original IllegalStack links

- [Spigot](https://www.spigotmc.org/resources/dupe-fixes-illegal-stack-remover.44411/)
- [Dev Builds](https://ci.athion.net/job/IllegalStack/)
- [Wiki](https://github.com/dniym/IllegalStack/wiki/FAQ)
- [Discord](https://discord.gg/Gsx4QaT)

## Building this project

Gradle is the recommended way to build the project. Hovewer keep in mind you will need to get spigot jar and JetMinions jars.
Once you get twose jars drop them into the libs folder.
Use `./gradlew build` in the main project directory to build the project.
The output is located at `/build/libs/IllegalStack.jar`.
