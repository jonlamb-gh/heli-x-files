# heli-x files

This repo contains my files for [Heli-X simulator](http://www.heli-x.info).

## Warning

I'm new to Heli-X, and am just starting to learn how to build environments/etc.

This repo will evolve to be more organized as I refine things.

For now, I'm just grabbing random heightmap images from Google to generate terrain.

Until I polish things up, the environments may not be immediately usable.

## Thanks

Thanks to `tweeb` on `forum.heli-x.info` for the great Rumble Canyon environment.

The models/objects used here are based on those files.

See this [forum.heli-x.info thread](http://forum.heli-x.info/viewtopic.php?f=23&t=1502) for the original post and download.

I have a version of it tracked here as well: [RumbleCanyon](Scene3D/RumbleCanyon)

## Generating alphamap file from heightmap

I have a small tool to generate alphamap RGBA files from heightmaps.
I'm not very good with blender so I'd rather generate them programmatically where possible.

[alphamap-gen](https://github.com/jonlamb-gh/alphamap-gen)

## Installation

Expects Heli-X to be installed in: `~/HELI-X7/`

```bash
cd heli-x-files/

# install files from this repo to ~/HELI-X7
./install

# remove files from ~/HELI-X7 install
./uninstall
```

## Random Heightmaps

Random heightmap images I find online to try out: [random heightmaps](random_heightmaps/)

## How To

TODO - walkthrough of creating a new environment

See the developer section in the [manual (v7)](http://www.heli-x.info/help/UsersManualV7.pdf).

General `Scene3D` layout:

```bash
Canyon-1/
├── 1024
│   ├── Canyon-1_back.jpg
│   ├── Canyon-1_bottom.jpg
│   ├── Canyon-1_front.jpg
│   ├── Canyon-1_left.jpg
│   ├── Canyon-1_right.jpg
│   └── Canyon-1_top.jpg
├── Canyon-1.xml
├── heightmap.png
├── alphamap.png
├── outlaw_sandstone.jpg
├── sandstone_square_decontrast.jpg
└── sand_texture.jpg
```

## 3D Scenes

### RumbleCanyon

`tweeb`'s RumbleCanyon

### Canyon-0

A copy of RumbleCanyon for testing.

### Canyon-1

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

### Canyon-2

![heightmap](Scene3D/Canyon-2/heightmap.png)

### Canyon-3

![heightmap](Scene3D/Canyon-3/heightmap.png)

### Canyon-4

![heightmap](Scene3D/Canyon-4/heightmap.png)
