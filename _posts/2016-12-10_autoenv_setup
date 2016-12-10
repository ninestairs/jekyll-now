---
layout: post
title: autoenv setup
---

```
venv=textminer
currentvenv=""

if [ $VIRTUAL_ENV != "" ]; then
  # Strip out the path and just leave the env name
  currentvenv="${VIRTUAL_ENV##*/}"
fi

if [ "$currentvenv" != "$venv" ]; then
  echo "Switching to environment: $venv"
  pyenv activate $venv
  nvm use v6.9.1
#else
#  echo "Already on environment $venv"
fi
```
