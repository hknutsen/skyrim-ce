# Tools

Set the following arguments for:

- SSELODGen
- TexGen
- DynDOLOD

If Skyrim was installed to `C:\GOG Games\Skyrim Special Edition`:

```plaintext
-sse -m:"C:\Users\<USER_NAME>\OneDrive\<DOCUMENTS_PATH>\My Games\Skyrim Special Edition GOG\" -p:"C:\Users\<USER_NAME>\AppData\Local\Skyrim Special Edition GOG\plugins.txt" -d:"C:\GOG Games\Skyrim Special Edition\Data\"
```

If Skyrim was installed to `C:\GOG Games\Skyrim Anniversary Edition`:

```plaintext
-sse -m:"C:\Users\<USER_NAME>\OneDrive\<DOCUMENTS_PATH>\My Games\Skyrim Special Edition GOG\" -p:"C:\Users\<USER_NAME>\AppData\Local\Skyrim Anniversary Edition GOG\plugins.txt" -d:"C:\GOG Games\Skyrim Anniversary Edition\Data\"
```

The value of `<DOCUMENTS_PATH>` depends on the configured [Windows display language](https://support.microsoft.com/en-us/windows/manage-display-language-settings-in-windows-219f28b0-9881-cd4c-75ca-dba919c52321).

For example:

- If Windows display language is `English (United States)`, the value of `<DOCUMENTS_PATH>` is `Documents`.
- If Windows display language is `Norsk (bokmål)`, the value of `<DOCUMENTS_PATH>` is `Dokumenter`.
