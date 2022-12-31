# Lapce Angular (LanguageServer)

### Lapce plugin for the Angular powered by angular

## Available configuration

```toml
[lapce-angular]
serverPath = "path/to/ngserver"
serverArgs = ["--stdio", "--tsProbeLocations", "path/to/your/progect", "--ngProbeLocations", "path/to/your/progect"]
```

If you want to setup specific project, add config to `.lapce/settings.toml` in your root of project.
