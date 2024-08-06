Followed this [guide](https://docs.godotengine.org/en/stable/tutorials/scripting/gdextension/gdextension_cpp_example.html)

Had to install cpp compiler, scons, and various vscode plugins

scons related error solved with [this](https://github.com/godotengine/godot-cpp/issues/1518)

to run `godot --dump-extension-api` it is run like `"file/path/to/godot/without/quotes" --dump-extension-api`

Ran into an issue with connecting the signal, resolved with info from [this](https://github.com/godotengine/godot/issues/69813)

Had to setup windows ssh agent and pass: [this](https://stackoverflow.com/questions/65741816/error-connecting-to-agent-no-such-file-or-directory-adding-key-to-ssh-agent)

[refreshed git merging strategies](https://graphite.dev/guides/git-rebase-vs-fast-forward)

In Order to run this project, `extension_api.json` must be compiled. see the guide.