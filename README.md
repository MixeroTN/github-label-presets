# github-label-packages

A list of GitHub repository labels meant for recycling and usage with [@Financial-Times/github-label-sync](https://github.com/Financial-Times/github-label-sync).

## Installation

### 📦 — NPM:

```
npm i github-label-packages
```

### 🧶 — Yarn:

```
yarn add github-label-packages
```

### 📀 — pnPM:

```
pnpm add github-label-packages
```

## Usage

### A few default packages are provided to get you started:

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
github-label-sync --access-token XXXXXX --labels nodemodules/github-label-packages/src/Strict/default.json myname/myrepo
```
