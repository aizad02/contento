# Contento

> An open source CMS built with the power of Elixir, Phoenix and Postgresql.

![Contento Admin Screenshot](https://raw.githubusercontent.com/contentocms/contento/master/screenshot.png)

#### Disclaimer

This project is currently a WIP and documentation, guides and more info is on it's way, stay tuned by staring this repo!

Many things may change before a stable version comes out, if you have any idea/suggestion/contribution, feel free to do it!

Find me (soon *us* I hope!) in #contento channel on [Elixir Slack](https://elixir-slackin.herokuapp.com/).

## Getting Started

*This info will be updated soon!*

1. Clone this repo wherever you'd like:

```
$ git clone https://github.com/contentocms/contento.git
```

2. Install dependencies:

```
$ cd ./contento/
$ mix deps.get
```

3. Setup Contento:

```
$ mix contento.install --force --defaults
```

6. Run Contento:

```
$ mix phx.server
```

After that you can access the website in `http://localhost:4000` and login to the back-office in `http://localhost:4000/login`.

Default credentials are:

- Email: **contento@example.org**
- Password: **contento**

**NOTE:** Check [ROADMAP.md](https://github.com/contentocms/contento/blob/master/ROADMAP.md) for current features and what's expected to come next.

## Contributing

Info for contributing to this project will be here soon, in the meanwhile just submit your PRs!

## License

This project is licensed under the [MIT license](https://github.com/contentocms/contento/blob/master/LICENSE.md).
