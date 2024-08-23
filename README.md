# URL-Validator

A python based utility to search, validate, calculate stats and export URLs. 

## Info

You can use this package with github-actions to check if links on your hosted website or docs are outdated.

## Install

```bash
git submodule add . # or just git clone
cd <>
poetry install
```

## Run

To parse all files in given directory recursively for URLs and print results:

```bash
poetry run url_validator -d <path> 
```

If you want to show only failures:

```bash
poetry run url_validator -d <path> --only-failures
```


