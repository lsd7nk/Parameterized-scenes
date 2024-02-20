# Parameterized-scenes

## Introduction

Improved scene loading/management  
You no longer have to keep _"DontDestroyOnLoad"_ objects on the scene and pass any parameters to the scene using _"PlayerPrefs"_

## Implementation

- Loading scenes without using string identifiers
- Scenes are represented as static classes
- Passing any parameters to the scene
- Generating static scene classes using the button in the menu

Each scene starter implements the _"ISceneLoadHandler"_ interface  
Each scene (represented as a static class) inherits an abstract _"Scene"_ class
