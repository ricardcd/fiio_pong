# Pong

Practica Pong. Extracted from the Apress Source Code repository: https://github.com/Apress/physics-for-game-programmers

That repository accompanies the book Physics for Game Programmers by Grant Palmer (Apress, 2005), http://www.apress.com/9781590594728

## About this version

This is a modified version of the original repository https://github.com/arnauatgithub/Pong, which was a .NET Framework 4.5 project for SharpDevelop. It was adapted to build and run in Visual Studio Code with modern C# and .NET (.NET 10 SDK). The game code is unchanged. The changes are a new SDK-style project file, small additions to `Main()` (`[STAThread]`, DPI and default-font settings so the window looks like the original), and the `.vscode` configuration.

## Running it

This version is a modern .NET (`net10.0-windows`) Windows Forms project. It runs on Windows only.

- **Visual Studio Code:** open this folder (`File > Open Folder...`) and press `F5`.
- **Command line:** `dotnet run --project Pong`

Requires the .NET 10 SDK and, for VS Code, the C# Dev Kit extension.
