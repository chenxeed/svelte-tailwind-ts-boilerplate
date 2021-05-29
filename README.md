# Boilerplate for SvelteKit + Tailwind JIT + Typescript

## Usage

Clone this repository and initialize your own application with the SvelteKit + Tailwind JIT ready to use for both development and production environment.

To run the svelte app, please check the [Svelte Kit documentation](https://kit.svelte.dev/docs).

## Source

The repository is initialized from the svelte-kit CLI: `npm init svelte@next`.
Preconfigured with `Typescript`, `Prettier` and `ESLint`.
Based on the `create-svelteversion 2.0.0-next.71`.

This repository is inspired from the post: [Sveltekit & Tailwind CSS Combo](https://dev.to/gevera/sveltekit-tailwind-css-combo-gdp), and built for reference.

Once the tailwind is installed, add the `tailwind` and `autoprefixer` to the postcss setup in `svelte.config.js`.

Then, add the `<style>` with tailwind imported in the Svelte template.
