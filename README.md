# ark's minqlx plugins

Plugins for Quake Live servers running minqlx or minqlxtended, in one place.
Each plugin's source, documentation and test record live in its own repository,
linked below; this repository carries the files to install.

| Plugin | What it does | Runtime | Home |
|---|---|---|---|
| `footstepsVQL.py` (with `footstepsVQL_lib/`) | Footsteps for high-fps players, without the doubled sounds: anyone above ~400 fps sounds to everyone else like a 250 fps player. Replaces footsteps250. | minqlx, minqlxtended | [ark-ql26/footstepsVQL](https://github.com/ark-ql26/footstepsVQL) |

## Install with QLSM

[QLSM](https://github.com/dngrtech/qlsm) 1.43.0 or newer: Settings →
Repositories → Add Repository, with the URL
`https://github.com/ark-ql26/minqlx-plugins`. Tick the plugins you want, pick the
runtime, and click Download selected. Then enable them in each instance's
Plugins tab and restart the instance.

A plugin you uploaded to an instance by hand before wins over the downloaded
one: delete the instance copy first. Each plugin's README covers anything else
it needs.

## Install by hand

Copy the plugin's `.py`, and its folder if it has one, into your
`minqlx-plugins/` or `minqlxtended-plugins/` directory and add the plugin to
`qlx_plugins`. Details per plugin in its home repository.

Contact: ark · Discord [`arkadnik.`](https://discord.com/users/352928164780965891)

License: [MIT](LICENSE).
