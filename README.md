This is a generic folder template for game design.

It features dedicated structures for the game's binaries (assets) and scripts, and documentation.

# Software
To use this template, these are the recommended applications, however they are not required. Some structures and files are already present that make it easier to use these apps. These can be deleted, if you choose to use a different kind of software.

## IDE
For this template, **VISUAL STUDIO CODE** was used, but any IDE will do.

## Game Engine
While this template works with any engine, it's structure was created with **GODOT**'s scene-based structure in mind.

## Documentation
For documentation, using **OBSIDIAN.MD** is recommended, but any markdown-processor, even VSC, works. If you choose to not use Obsidian, you can delete the /.obsidian folder inside the documentation-directory.

## Versioning
This template uses **GIT** and has some premade files already created, however they need to be filled depending on the individual requirements. If not using git, delete the /.git folder, as well as the .gitignore and .gitattributes files in the root-directory.


# Structure Overview
This template follows a hybrid approach. While the **/assets** folder is structured in a hierarchical way with folders for each type of asset (textures, models, audio, etc.), the **/src** folder contains all source code as well as any other non-binary files. This is where things like scenes (if using Godot) or prefabs (if using Unity) are stored.

This makes it not only easier for programmers and artists to work without having to deal with the other departements things, it makes handling LFS easier, too, since ideally most, if not all binaries can be stored inside /assets.

This approach attempts to keep the structure easily readable, while preserving modularity.


# Development
Anything not directly relevant to the game like the documentation, moodboards, meeting notes, etc. belongs inside the **/dev** folder, along with any third party **/tools** and their files used for development. For example when using **FMOD** for sound design, any project-files or project-relevant settings can be stored in here.

> Note, that if any tools involve large files, either exclude those files and/or folders inside the **.gitignore** file or use other means of storage, as EVERYTHING inside the /dev directory will be tracked via git by default.

## Documentation
While referencing code snippets inside the documentation would make sense, this would make it impossible for the documentation and the actual game to stay separate and thus introduce another layer of complexity to the structure. As the documentation is only relevant for development, it can be found inside the **/dev** folder. In an effort to keep things clean, this is a necessary compromise.