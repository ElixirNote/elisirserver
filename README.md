<div align="center">
    <img src="https://raw.githubusercontent.com/ElixirNote/elixirserver/main/jupyter_server/static/logo/logo.png" width=120 alt="logo" />
    <br />
    <small>go from data to knowledge</small>
</div>

# [Elixir Server](https://ciusji.gitbook.io/elixirnote/guides/elixirnote-server)

The [**ElixirNote**](https://github.com/ElixirNote/elixirnote) Server provides the backend (i.e. the core services, APIs, and REST endpoints) for Elixir web applications like Elixir notebook, and Voila.

For more information, read our [documentation here](https://ciusji.gitbook.io/elixirnote/guides/elixirnote-server).

## Installation and Basic usage

To install the latest release locally, make sure you have
[pip installed](https://pip.readthedocs.io/en/stable/installing/) and run:

    pip install elixir_server

or install from source:

    git clone git git@github.com:ElixirNote/elixirserver.git
    cd elixirserver
    pip install -e .

ElixirServer currently supports Python>=3.6 on Linux, OSX and Windows.

### Versioning and Branches

If Elixir Server is a dependency of your project/application, it is important that you pin it to a version that works for your application. Currently, Jupyter Server only has minor and patch versions. Different minor versions likely include API-changes while patch versions do not change API.

When a new minor version is released on PyPI, a branch for that version will be created in this repository, and the version of the main branch will be bumped to the next minor version number. That way, the main branch always reflects the latest un-released version.

To see the changes between releases, checkout the [CHANGELOG](CHANGELOG.md).

## Usage - Running Elixir Server

### Running in a local installation

Launch with:

    elixir-server

### Testing

See [CONTRIBUTING](CONTRIBUTING.rst).

## Contributing

If you are interested in contributing to the project, see [`CONTRIBUTING.rst`](CONTRIBUTING.rst).

## License

[ Licensing terms](./COPYING.md).
