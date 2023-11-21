# Run DynDOLOD

## Steps

1. Run `TexGen` with default settings.

    Settings:

    - [x] HD Trees

    Estimated generation time: ~2 minutes.

1. Run `DynDOLOD` for all worldspaces with the `Medium` preset.

    Settings:

    - [x] Ultra Tree LOD

    Estimated generation time: ~15 minutes.

## Troubleshooting

If you get the following error:

```plaintext
Fatal: Error loading plugin list: <EDirectoryNotFoundException: The specified path was not found
```

Open `regedit`, find key `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Bethesda Softworks\Skyrim Special Edition` and add a new string value `Installed Path`.

If Skyrim was installed to `C:\GOG Games\Skyrim Special Edition`, set the value to:

```plaintext
C:\GOG Games\Skyrim Special Edition\
```

If Skyrim was installed to `C:\GOG Games\Skyrim Anniversary Edition`, set the value to:

```plaintext
C:\GOG Games\Skyrim Anniversary Edition\
```

## References

- [Official documentation](https://dyndolod.info/)
