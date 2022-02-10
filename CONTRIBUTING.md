## Contributing

### Adding new signs

All traffic signs in this project are found in the `data` directory.

Each country in the `data` directory should be represented by their [ISO 3166 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) code. For example, the directory `us` holds traffic signs used the [United States](https://en.wikipedia.org/wiki/United_States). Subdirectories can be created within these country folders if a subdivision of that country has a unique traffic sign using their [ISO 3166-2](https://en.wikipedia.org/wiki/ISO_3166-2) code. For example, the subdirectory `or` within the `us` directory holds traffic signs used in [Oregon](https://en.wikipedia.org/wiki/Oregon).

Each sign must be a .json file and must minimally have a `name` and `tags`.

It's also recommended to link the `wikidata` item if it has one and `terms` if there are any synonyms.
