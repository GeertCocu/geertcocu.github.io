# IGart Terrain Tool

## About the Framework

The **IGArt Framework** is a custom C++ framework, completely made from scratch, that was heavily inspired by The UbiArt Framework from Ubisoft. This framework was designed to create simple 2D platforming games, just like the UbiArt framework. We targeted development for the PSVita and Windows.

## My Contribution

My main contribution was recreating the terrain tool of UbiArt in our framework.
To recreate this in our framework, the following had to be done:

- Ear-clipping triangulation for rendering meshes
- Generate collider mesh using Box2D
- Generate edge meshes (grass, cliff, etc.)
- Create an intuitive UI for end-users to modify the terrain.

https://github.com/user-attachments/assets/ec761d14-e440-412a-a5d4-f1eb03769737

For more details see [Github](https://github.com/GeertCocu/IGArt-TerrainTool).