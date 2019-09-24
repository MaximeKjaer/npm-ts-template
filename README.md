# Configuration template for NPM modules written in TypeScript

[![Build Status](https://travis-ci.com/MaximeKjaer/ts-npm-template.svg?token=soqG4sgcMQUgpCtPSUUr&branch=master)](https://travis-ci.com/MaximeKjaer/ts-npm-template)

A configuration template for NPM modules written in TypeScript.

## Using this template
If you want to use this template for your project, you can [start a new repo with the same files and folders as this repo](https://github.com/MaximeKjaer/ts-npm-template/generate). Remember to change:

- [ ] Author name in `LICENSE`
- [ ] Author name in `package.json`
- [ ] GitHub repo links in `package.json`
- [ ] Email in `.travis.yml`
- [ ] GitHub repo link in `.travis.yml`
- [ ] Badge link in `README`

## Commands

| `npm run ...`        | Description                                                                      |
| -------------------- | -------------------------------------------------------------------------------- |
| `build`              | Run all build steps                                                              |
| `build:ts`           | Compile TypeScript files in `src` to `dist`                                      |
| `clean`              | Delete all build artifacts                                                       |
| `test`               | Run all tests                                                                    |
| `test:format`        | Test code formatting for all JavaScript, TypeScript, JSON and YAML files         |
| `test:lint`          | Test TypeScript files for linting errors                                         |
| `test:package`       | Test that paths in `package.json` exist                                          |
| `test:tslint-config` | Test that `tslint.json` does not contain rules conflicting with formatting rules |
| `test:unit`          | Run Mocha unit tests                                                             |
| `fix`                | Run all fixes                                                                    |
| `fix:lint`           | Fix linting errors in TypeScript files                                           |
| `fix:format`         | Fix formatting errors for all JavaScript, TypeScript, JSON and YAML files        |
