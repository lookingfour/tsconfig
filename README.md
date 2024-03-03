# @lookingfour/tsconfig

An tsconfig configuration that is being used by LookingFour.

## Installation

You can install the package and its peer dependencies by running:

```sh
npm install --dev typescript@^5 @lookingfour/tsconfig
```

## Usage

You can extend from one of our preset configurations:

```json
{
  "extends": "@lookingfour/tsconfig/service.json"
}
```

Available configurations are:

- `@lookingfour/tsconfig/service.json`
- `@lookingfour/tsconfig/react.json`
