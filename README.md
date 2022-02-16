# Metametalang

Metametalang is a metadata based protocol for faciliating metaverse interoperability. 

It exists with the following intentions:

  - providing a coherent data layer that specifics what data objects exist at different locations in different metaverses
  - This would allow one to go from any location in any metaverse to any location in any other metaverses 
  - This exists natively cross chain and is compatible with all major cross chain protocols 
  - The language natively supports multiple rendering engines, ideas of space (including fractally embeeding space), and physics transforms 
  - any game logic or interactoins broken out and implemented separately to the object layer 
 
 
 Additional benefits of working with metametalang include:
 
 - because the data layer is completely separate and exists as a blockchain anchored append only universal data store, this means data objects can be dynamically updated, which allows for dynamic upgrade path (i.e. a metaverse is not frozen to a particular technology set at a particular point in time) 
 
 - this allows one to build a client (i.e browser) that can take one from any metaverse location to any other metaverse location
 
 - this allows one to work with non visual information, including audio, olfactory data, phermones, and any other experience which can be registered (keep in mind that the rendering engine can be a physical device) 

 - complex games and interactive experiences can be built on top of the lands (c.f. roblox)  



For metametalang there is one primary native object:


    $meta - represents the active metaverse



For metametalang there is also one default coordinate system:

    /1.3.5.0 - this represeents x coordinates, y coodinates, z coordinates, and zoom level

It can also be appended, which also works as passing a set of vectors: /1.3.5.0/1.3.2.1/2.3.3.0 

All locations in all metaverses can be described as a set of vectors. 




These come with a certain supported actions. 


    $meta.owner - returns the owner of the metaverse
    
    $meta.insert - inserts an object inside the active metaverse

    $meta.created - inserts an object inside the active metaverse

    $meta.children - notes the presence of child metaverses and their locations t

    $meta.zoom(coords) - take me to the child at these coordinates. By default goes to the first child. 

    $meta.go(coordinates) - go to these coordinates





As of now there is a javascript and unreal engine implementation of the language spec 

