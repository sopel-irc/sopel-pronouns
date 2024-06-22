# sopel-pronouns

Pronoun-sharing plugin for Sopel IRC bots

## Installing

Releases are hosted on PyPI, so after installing Sopel, all you need is `pip`:

```shell
$ pip install sopel-pronouns
```

## Configuring

The easiest way to configure `sopel-pronouns` is via Sopel's
configuration wizard—simply run `sopel-plugins configure pronouns`
and enter the values for which it prompts you.

Options are:

* Whether to download a full list of supported pronoun sets
* An optional custom base URL for links in the plugin's output

The custom base URL allows you to use your own domain to host a copy of [our
pronoun service][pronoun-service], which is itself a fork of Lucas Eduardo's
[lovely little Svelte project][original-pronoun-service].

[pronoun-service]: https://github.com/sopel-irc/pronoun-service
[original-pronoun-service]: https://github.com/lucasew/svelte-pronounisland

## Credits

`sopel-pronouns` is based on the `pronouns.py` plugin that was built into Sopel
from version 6.5.1 through 8.0. Special thanks to Elsie Powell and other
contributors to the original code, whose work can be viewed in the main Sopel
repository's [commit history][original-history].

[original-history]: https://github.com/sopel-irc/sopel/commits/d4a0efde1a4bdea03be265d5e23591b553a0ce76/sopel/modules/pronouns.py
