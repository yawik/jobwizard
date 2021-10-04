# Wixard for entering job ad

Standalone wizard based on [quasar](https://quasar.dev/). It is a single page application (SPA) running in the 
clients browser. The result is a static HTML content.

## Task description

https://gitlab.com/yawik/rewrite/-/issues/1

## Status

In development.

## Requirements

- [nodesjs](https://nodejs.org/)
- [yarn](https://yarnpkg.com/) (recommended)

## Installation

```
git clone https://gitlab.com/yawik/jobwizard.git
cd wizard
yarn install
yarn dev
```

## Configuration

The form is .env-aware.  

| Name                         | Value                               | 
|------------------------------|-------------------------------------|
| YAWIK_URL_PRIVACY            | Link to the Privacy notes           |
| YAWIK_APP_KEY                | Shared App Key                      |
| YAWIK_API_URL                | Yawik API                           |  

It's possible to show a toolbar with the Logo and a navigation drawer by using query parameter with any non-empty value.

| Param        | Description       |
|--------------|-------------------|
| tb           | show toolbar      |  

## Demo

http://jobwizard.yawik.org/

## Documentation

Currently in development.
