# My Personal Site

## About

My personal website. Contains a bunch of the stuff I'm working on, some info about me, and my favorite tools for SWE / general software development.

## Usage

### Getting Started

Clone the repo like you would any other repo:

```bash
git clone https://github.com/DrewDalmedo/drewdalmedo.github.io drews-site
```

Then, `cd` into the site's directory and update the git submodules (used for the website's theme):

```bash
	cd drews-site
	git submodule update --init --recursive
```

### Updating

To update the site to the latest version, you need to `git pull` like you would with any other repo:

```bash
git pull
```

Additionally, you should also check for any theme updates:

```bash
git submodule update --remote --merge
```



