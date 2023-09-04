# Dokument Site

This is the source code for the [Dokument](https://github.com/cthit/dokument) site. The currently deployed instance can be found at [docs.chalmers.it](https://docs.chalmers.it).

It is written in Astro for its simplicity and speed, as well as the fact that it makes it easy to write components for the site.

## Development

### Prerequisites

To run the site locally, you need to have [Node.js](https://nodejs.org/en/) installed. You should also use [pnpm](https://pnpm.io/) as your package manager, as it is faster and more secure than npm. You can install it using the following command (assuming you have Node.js installed):

```bash
npm install -g pnpm
```

### Running the site

Run the following commands:

```bash
pnpm install
pnpm run dev
```

This will start a development server on port 3000. You can then access the site at [localhost:3000](http://localhost:3000).

## Deployment

The site is deployed automatically using GitHub Actions on the `main` branch. However, it is deployed using the [dokument](https://github.com/cthit/dokument) repository, as the site should automatically update when the docs are updated. To deploy the site immediately, you can go to that repository and run the `deploy` workflow manually (assuming you have the correct permissions).
