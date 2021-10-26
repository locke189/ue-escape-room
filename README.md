# ue-escape-room

Unreal Engine escape room game

## Installing VSCode Tools

Add the following extension to VSCode

- C/C++
- C/C++ Clang Command Adapter
- C#
- C++ Intellisense
- Clang-Format
- Unreal Engine 4 Snippets

Also make sure you install [VSCode/UE Intellisense Fixes Extension](https://gist.github.com/boocs)

## Git LFS

Run `git lfs install` and then create a `.gitattributes` file with the following:

```
# UE file types
*.uasset filter=lfs diff=lfs merge=lfs -text
*.umap filter=lfs diff=lfs merge=lfs -text

# Raw Content types
*.fbx filter=lfs diff=lfs merge=lfs -text
*.3ds filter=lfs diff=lfs merge=lfs -text
*.psd filter=lfs diff=lfs merge=lfs -text
*.png filter=lfs diff=lfs merge=lfs -text
*.mp3 filter=lfs diff=lfs merge=lfs -text
*.wav filter=lfs diff=lfs merge=lfs -text
*.xcf filter=lfs diff=lfs merge=lfs -text
*.jpg filter=lfs diff=lfs merge=lfs -text
```
