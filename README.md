# linuxsolver
Linux Solver - Diagnostic Tool for Debian / Ubuntu Linux distros

A hardware configuration diagnostic and troubleshooting tool written in Bash. It consists of a set of modules that attempt to answer questions (hypotheses) about why a piece of hardware isn't working and seek to solve these issues.

## Available Modules:

- performance
- video
- sound
- bluetooth
- wi-fi
- ethernet
- touchpad

## Installation:

```bash
git clone https://github.com/boctulus/linuxsolver.git
sudo ln -s $(pwd)/solver /usr/bin
```

Usage:

```bash
./solver
```
