# github-label-presets

[![Software License][ico-license]](LICENSE.md)

A default set of label presets for my GitHub repositories.

## Install

This requires [`github-label-sync`][link-github-label-sync] to manage the labels for a repository.

```bash
npm install -g github-label-sync
```

## Usage

Run the following to set labels for a repository:

```bash
export GITHUB_ACCESS_TOKEN=''

# To perform a dry-run
github-label-sync --labels https://git.io/fjZcw pxgamer/repo-name -d

# To perform a real run
github-label-sync --labels https://git.io/fjZcw pxgamer/repo-name
```

## Credits

- [pxgamer][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square

[link-github-label-sync]: https://github.com/Financial-Times/github-label-sync#command-line-interface
[link-author]: https://github.com/pxgamer
[link-contributors]: ../../contributors
