---
layout: post
title: zsh & oh-my-zsh on Windows
description: A guide to install and setup zsh & oh-my-zsh on Windows
summary: A guide to install and setup zsh & oh-my-zsh on Windows
tags: shell cli zsh
lastmod: 2024-04-09T02:28:57.570Z
---

## Installing MSYS2

Install msys2 installer from https://www.msys2.org/.

## Setup zsh

- Install zsh:

  ```bash
  pacman -S zsh
  ```

- Type `zsh`
- if forget type

  ```bash
  autoload -U zsh-newuser-install
  zsh-newuser-install -f
  ```

- Configure zsh as default shell

  ```bash
  if [ -t 1 ]; then
    exec zsh
  fi
  ```
