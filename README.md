# Homebrew Formulae

[Homebrew Formulae](https://formulae.brew.sh) is an online package browser for [Homebrew](https://brew.sh).

It displays all packages in [Homebrew/homebrew-core](https://github.com/Homebrew/homebrew-core). It is deployed to GitHub Pages after every [Homebrew/homebrew-core](https://github.com/Homebrew/homebrew-core) commit by [Travis CI](https://travis-ci.org).

## JSON API

It also provides a JSON API for all packages (or individual packages) in [Homebrew/homebrew-core](https://github.com/Homebrew/homebrew-core) and their related analytics. This JSON data is used for the creation of the HTML resources on this site.

Currently available:
- List formulae metadata for all homebrew-core formulae
- Get formula metadata for a homebrew-core formula
- List analytics events
- List analytics events for all homebrew-core formulae

Read more in the [JSON API documentation](https://formulae.brew.sh/docs/api/).

## Usage
Open https://formulae.brew.sh/ in your web browser.

Instead, to run Homebrew Formulae locally run:
```bash
git clone https://github.com/Homebrew/formulae.brew.sh
cd formulae.brew.sh
bundle install
bundle exec jekyll serve
```

## License
Code is under the [BSD 2-clause "Simplified" License](LICENSE.txt).
