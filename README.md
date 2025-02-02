# gh fuzzyclone

A [gh](https://github.com/cli/cli) extension to clone GitHub repositories using
[fzf](https://github.com/junegunn/fzf#readme).

## Requirements

You're expected to already have [fzf](https://github.com/junegunn/fzf#readme)
installed for this extension to work.
Please follow their [installation instructions](https://github.com/junegunn/fzf#installation)
if you don't have it yet.

## Installation

```sh
gh extension install hashue/gh-fuzzyclone
```

## Usage

```sh
gh fuzzyclone
```

By default, the extension only fetches repositories under your username.
To get other repositories, you can pass in a username, like so:

```sh
gh fuzzyclone hashue
```

If you want to use custom options (e.g. --limit),  you can set them like below.
``` 
OPTS="--limit 100" gh fuzzyclone
```
## Author

Hasu
