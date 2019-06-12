# Git License Generator Plugin

Simple git license generator plugin.

## Installation

There are two ways to install this plugin

### Manual Installation

```bash
git clone https://github.com/foss-dev/git-license-generator

cd git-license-generator

sudo mv git-licenses/* /usr/local/bin/
sudo mv git-generate-license /usr/local/bin/
```

### Direct Installation

Just copy and paste this one-line command:

```bash
$ bash -c  "$(wget -qO- https://git.io/fj2J9)" 
```

Or, if you are a Mac user:

```bash
$ bash -c  "$(curl -sLo- https://git.io/fj2J9)"
```

## Usage

Select license

```bash
git generate-license -s
```