The Legacy Modding wiki aims to be a comprehensive resource about creating mods for old versions of Minecraft. Currently it mainly focuses on Forge mod development for 1.7.10.

The wiki can be browsed **[here](https://legacymoddingmc.github.io/wiki/)**.

## Contributing

It's possible to contribute by simply editing the markdown files in the `docs` directory. The index page is at [docs/index.md](docs/index.md).

Some files are generated from templates. These have a corresponding `.template.md` file. Do not edit the generated files directly. Edit the template file, and run `python3 build.py` to regenerate the output files before committing.

### Testing

To test changes, it may be desirable to set up a local mkdocs server:

```
pip install mkdocs mkdocs-windmill
mkdocs serve
```

The wiki will be browsable at [http://localhost:8000/](http://localhost:8000/) with live reloading.

## License

The wiki's contents are available under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
