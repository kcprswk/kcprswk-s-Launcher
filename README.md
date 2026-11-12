# kcprswk-s-Launcher

An independent Windows desktop launcher for a private Minecraft:
Java Edition server, built with C#, WPF and .NET.

The project aims to provide a simple way for community members
to sign in, prepare the server's modpack and launch the game.

## Current features

- Minimal dark interface.
- Microsoft sign-in through CmlLib.
- Minecraft Java username displayed after authentication.
- Persistent sessions protected with Windows DPAPI.
- Local sign-out.

## Planned features

- Installation and launch of Minecraft 1.21.1 with NeoForge 21.1.265.
- Automatic download, verification and updates of the server modpack.
- Administrator-issued UID accounts for separate server authentication.
- Integration with custom client and server authentication mods.

UID authentication is separate from Microsoft authentication and
does not grant Minecraft ownership or a Microsoft/Minecraft session.

## Development status

Early development. Microsoft sign-in is functional in the current
Windows build. Game installation, launching and UID authentication
are not implemented yet.

## Technology

- C# / .NET 10
- WPF
- CmlLib.Core.Auth.Microsoft

## Running

Requires Windows and the .NET 10 SDK.

    dotnet run --project WpfLauncher/Launcher.csproj

## Contact

Maintainer: kcprswk

## Disclaimer

Not an official Minecraft product.
Not approved by or associated with Mojang or Microsoft.
