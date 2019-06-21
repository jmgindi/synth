![synth logo](assets/synth_logo.png)

# synth - a Docker bootstrapping tool

Inspired by how long it can take to set up the development of web apps, synth is a tool to help you build modular sets of Docker, Docker Compose, and CI/CD pipeline config files, as well as directory trees and wireframed files for different front- and backend web frameworks. synth can help you set up your next web application project in seconds, allowing you to start coding your idea with zero hassle.

## Dependencies

- `docker` and `docker-compose`

- `python3`

## Installation

Clone the repository into a new directory

```
$ git clone https://github.com/BennettDixon/synth.git
```

Install via pip:

```
pip3 install boot-synth
```

## Usage

```
synth create [OPTIONS]
```

![synth demo](assets/synth_basic_demo.gif)

## Options
```
--help
```

Show help message

![--help demo](assets/synth_help_demo.gif)

```
--frontend, -f
```

Your frontend framework. Currently supported options are `static`, `dynamic`, `react`.

```
--backend, -b
```

Your backend framework. Currently supported options are `flask`, `node`, `django`.

```
--database, -d
```

Your choice of database. Currently supported options are `mysql`, `postgres`, `mongo`, `mariadb`.

```
--cache, -c
```

Your choice of caching tool. Currently supported options are `redis` and `memcache`.

```
--pipeline, -p
```

Your choice of CI/CD pipeline. `travis` is currently the only supported option.

## Coding Style Tests

Strictly followed `pep8` style guide. To install:

### Regular Ubuntu 14.04 install

With apt-get

```
$ sudo apt-get install python3-pep8
```

With pip3

```
$ pip3 install pep8
```

### Check The Version

```
$ pep8 --version
1.7.1
```

## Version

- 1.0.0

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)

## Authors

- **Bennett Dixon** - [@BennettDixon](https://github.com/BennettDixon)
- **Jack Gindi** - [@jmgindi](https://github.com/jmgindi)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details

## Acknowledgments

- [Holberton School](https://github.com/holbertonschool) (providing guidance)

- [Julian Gindi](https://github.com/JulianGindi) (project mentor)
