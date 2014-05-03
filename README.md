yacli
=====
yet another command line interface

## What?
A dumb micro-pseudo-framework for writing CLI apps in go. 

## Why?
All CLI frameworks suck. This one just sucks slightly less.

## Micro-pseudo-framework?
It's not a library - just a loose template that's generic enough to maybe kinda be useful for writing basic new CLIs.
It supports subcommands and global/per-command options and not much else.
It's simple. It has no dependencies. It works.

## How?
1. Copy `{main,help,version}.go` into your project
2. Slice and dice as necessary
3. ???
4. Profit

## Examples?
[`fleetctl`](https://github.com/coreos/fleet/tree/master/fleetctl) 
[`locksmithctl`](https://github.com/coreos/locksmith/tree/master/locksmithctl)

## Skub?
[Pro skub.](http://pbfcomics.com/20/)
