# DynDOLOD

## Arguments

> The following arguments must be set for both `TexGen` and `DynDOLOD`.

If Skyrim was installed to `C:\GOG Games\Skyrim Special Edition`:

```plaintext
-sse -m:"C:\Users\<USERNAME>\Documents\My Games\Skyrim Special Edition GOG\" -p:"C:\Users\<USERNAME>\AppData\Local\Skyrim Special Edition GOG\plugins.txt" -d:"C:\GOG Games\Skyrim Special Edition\Data\"
```

If Skyrim was installed to `C:\GOG Games\Skyrim Anniversary Edition`:

```plaintext
-sse -m:"C:\Users\<USERNAME>\Documents\My Games\Skyrim Special Edition GOG\" -p:"C:\Users\<USERNAME>\AppData\Local\Skyrim Anniversary Edition GOG\plugins.txt" -d:"C:\GOG Games\Skyrim Anniversary Edition\Data\"
```

## Steps

1. Run `TexGen` with default settings.

1. Run `DynDOLOD` for all worldspaces with the `Medium` preset.

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
