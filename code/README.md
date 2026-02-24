# Clockworks

This is a repository of the ProtoGraph code used to build parts of the Clockworks MMC entry.

# Commands

> Prerequisite: [Flux SDK](https://flux-sdk.samsmucny.com/ProtoGraph/Getting-Started.html)

Run commands from the root of the project directory or provide the project directory with the `-d` argument.

- Build: `flux-sdk build` & `flux-sdk build --profile release`
- Build modified only: `flux-sdk build -S`
- Build individual module: `flux-sdk build <module_path>`

# Importing

After building the project, the outputs will be in the `build` directory. Import the `.brson` file(s) into Resonite.
Use the ProtoGraph UI tool to update the flux and assign any IO sources/drives.

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
