# github-label-presets

A list of GitHub repository labels meant for recycling and usage with [@Financial-Times/github-label-sync](https://github.com/Financial-Times/github-label-sync).

## Installation

### 📦 — NPM:

```
npm i github-label-presets -D
```

### 🧶 — Yarn:

```
yarn add github-label-presets -D
```

### 📀 — Pnpm:

```
pnpm add github-label-presets -D
```

## Usage

### A few default presets are provided to get you started:

-   [cla](src/cla.json)
-   [default](src/default.json) - _Default Github Labels_
-   [priority](src/priority.json)
-   [status](src/status.json)
-   [type](src/type.json)

### If you are looking to strictly use one format, consider using these instead:

-   [strict-cla](src/Strict/cla.json)
-   [strict-default](src/Strict/default.json) - _Default Github Labels_
-   [strict-priority](src/Strict/priority.json)
-   [strict-status](src/Strict/status.json)
-   [strict-type](src/Strict/type.json)

## Usage With [@Financial-Times/github-label-sync](https://github.com/Financial-Times/github-label-sync):

```
github-label-sync --access-token XXXXXX --labels node_modules/github-label-presets/src/Strict/default.json myname/myrepo
```
