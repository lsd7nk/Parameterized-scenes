# Parameterized scenes

## Introduction

Improved scene loading/management  
You no longer need to pass any parameters to the scene using _"PlayerPrefs"_

## Implementation

- Loading scenes without using string identifiers
- Scenes are represented as a classes
- Passing any parameters to the scene
- Generating static scene classes using the button in the menu

Each scene starter implements the _"ISceneLoadHandler"_ interface  
Each scene(represented as a class) inherits an abstract _"Scene"_ class
