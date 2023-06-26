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

### 📀 — pnPM:

```
pnpm add github-label-presets -D
```

## Usage

### A few default presets are provided to get you started:

-   [cla](src/Packages/cla.json)
-   [default](src/Packages/default.json) - _Default Github Labels_
-   [priority](src/Packages/priority.json)
-   [status](src/Packages/status.json)
-   [type](src/Packages/type.json)

### If you are looking to strictly use one format, consider using these instead:

-   [strict-cla](src/Packages/Strict/cla.json)
-   [strict-default](src/Packages/Strict/default.json) - _Default Github Labels_
-   [strict-priority](src/Packages/Strict/priority.json)
-   [strict-status](src/Packages/Strict/status.json)
-   [strict-type](src/Packages/Strict/type.json)

## Usage With [@Financial-Times/github-label-sync](https://github.com/Financial-Times/github-label-sync):

```
github-label-sync --access-token XXXXXX --labels node_modules/github-label-presets/src/Strict/default.json myname/myrepo
```
