# Clockworks

This is a repository of the ProtoGraph code used to build parts of the Clockworks MMC entry.

# Commands

> Prerequisite: [Flux SDK](https://flux-sdk.samsmucny.com/ProtoGraph/Getting-Started.html)

Run commands from the root of the project directory or provide the project directory with the `-d` argument.

- Build: `flux-sdk build` & `flux-sdk build --profile release`

# Structure

```
MyProject/
├─ README.md (this file; project documentation)
├─ Main/ (the modules that are imported into the world)
├─ Lib/ (helper modules)
├─ protograph.toml (project manifest)
├─ protograph.lock (pinned dependencies; this project has no dependencies)
├─ .pg-packages/ (dependencies will be installed here)
├─ .gitignore
```
