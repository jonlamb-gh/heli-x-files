# heli-x files

Thanks to `tweeb` on `forum.heli-x.info` for the great Rumble Canyon environment.

The models/objects used here are based on those files.

See this [forum.heli-x.info thread](http://forum.heli-x.info/viewtopic.php?f=23&t=1502) for the original post and download.

I have a version of it tracked here as well: [RumbleCanyon](Scene3D/RumbleCanyon)

# Generating alphamap file from heightmap

I have a small tool to generate alphamap RGBA files from heightmaps.
I'm not very good with blender so I'd rather generate them programmatically where possible.

[alphamap-gen](https://github.com/jonlamb-gh/alphamap-gen)

# Installation

Expects Heli-X to be installed in: `~/HELI-X7/`

```bash
cd heli-x-files

# install files from this repo to HELI-X7
./install

# remove files from HELI-X7 install
./uninstall
```

# Random Heightmaps

Random heightmap images I find online to try out: [random heightmaps](random_heightmaps/)

# 3D Scenes

## RumbleCanyon

`tweeb`'s RumbleCanyon

## Canyon-0

A copy of RumbleCanyon for testing.

## Canyon-1

A large canyon.

There are two heightmaps:

- ![standard heightmap (default)](Scene3D/Canyon-1/heightmap.png)
- ![alternate heightmap](Scene3D/Canyon-1/heightmap_alt.png)

Starting positions:

```xml
<!-- standard -->
<StartPosition edit="yes">41.7,-11.7,177.1</StartPosition>

<!-- alternate -->
<StartPosition edit="yes">-3,-50,-3</StartPosition>
```

## Canyon-2

![heightmap](Scene3D/Canyon-2/heightmap.png)

## Canyon-3
![heightmap](Scene3D/Canyon-3/heightmap.png)

## Canyon-4
![heightmap](Scene3D/Canyon-4/heightmap.png)
