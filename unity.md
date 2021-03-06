<!-- TITLE: Unity -->

# Unity Modding
## Games

Name | Developer | Unity Version | .NET Compatibility
:--- | :--- | :--- | :---
Pathfinder: Kingmaker | Owlcat Games | 2018.1f0 | .NET 4.x (Assembly-CSharp.dll)
Pillars of Eternity | Obsidian Entertainment | 5.1 | .NET 3.5 (Assembly-CSharp.dll)
Pillars of Eternity II: Deadfire | Obsidian Entertainment | 5.6.3 | .NET 3.5 (Assembly-CSharp.dll)
Torment: Tides of Numenera |  inXile Entertainment | 5.4.1 | .NET 3.5 (Assembly-CSharp.dll)
Tyranny | Obsidian Entertainment | 5.2 | .NET 3.5 (Assembly-CSharp.dll)

## Tools

Most of modding Unity games involves decompiling `Assembly-CSharp.dll` and patching in new code.

Type | Name | Developer | Price | License | Download | Website
:--- | :--- | :--- | :--- | :--- | :--- | :---
Decompiler/IL Editor | dnSpy | 0xd4d | Open source | GPL v3 | [https://ci.appveyor.com/project/0xd4d/dnspy/branch/master/artifacts](https://ci.appveyor.com/project/0xd4d/dnspy/branch/master/artifacts) | [GitHub](https://github.com/0xd4d/dnSpy)
Decompiler | dotPeek | JetBrains | Free | Commercial | [https://www.jetbrains.com/decompiler/download/](https://www.jetbrains.com/decompiler/download/) | [Official Website](https://www.jetbrains.com/decompiler/)
Deobfuscator | de4dot | 0xd4d | Open source | GPL v3 | [https://ci.appveyor.com/project/0xd4d/de4dot/branch/master/artifacts](https://ci.appveyor.com/project/0xd4d/de4dot/branch/master/artifacts) | [GitHub](https://github.com/0xd4d/de4dot)
Monkey Patcher | Harmony | pardeike | Open source | MIT | Compile from source code | [GitHub](https://github.com/pardeike/Harmony)
Monkey Patcher | Patchwork | Greg Ros | Open source | MIT | Compile from source code | [GitHub](https://github.com/GregRos/Patchwork)

### In development

Name | Description | Developers
:--- | :--- | :---
[Asset Studio Pro](https://github.com/fireundubh/AssetStudio) | A fork of Asset Studio with better MonoBehaviour support<br>([Project goals and tasks](https://trello.com/b/XKKryP88/asset-studio-pro)) | &bull; fireundubh<br>&bull; Jackal

## References

Tutorial | Description
:--- | :---
[Patchwork Design Patterns](/unity/patchwork-design-patterns) | How to use Patchwork attributes for common problems
[Patchwork Project Structure](/unity/patchwork-project-structure) | How to structure a Patchwork project
[Turning a release build into a debug build](/unity/turning-a-release-build-into-a-debug-build) | ADVANCED. You do not need to do this unless you use debug logging and want Assembly-CSharp line numbers in call stacks.

## Notes

* If you use Microsoft's [PEVerify Tool](https://docs.microsoft.com/en-us/dotnet/framework/tools/peverify-exe-peverify-tool) (e.g., Patchwork's Test Run), you may notice that an unmodded Unity game has IL errors in `Assembly-CSharp.dll`. These errors are likely caused by Unity either writing bad IL or, less likely, performing (probably unnecessary) IL optimizations. For example, the latest version of _Torment: Tides of Numenera_ has 150 IL errors in `Assembly-CSharp.dll`. Most IL errors can be monkey patched.