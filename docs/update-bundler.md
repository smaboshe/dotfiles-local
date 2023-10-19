# update-bundler

The `update-bundler` script updates `bundler` for a set of projects.

## Requirements

To use `update-bundler` please make sure that [Docker](https://www.docker.com/products/docker-desktop/) is installed and running.

## Usage

Define the projects that need updating in `~/.config/bundler-projects`. Here is an example `bundler-projects` file:

```
/u/bootcamp
/u/mango
~/code/blue-band
~/code/swingset
```

Run the script using `update-bundler <BUNDLER_VERSION>`. For example:

```
update-bundler 2.4.21
```
