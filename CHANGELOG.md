# Change Log

All notable changes to the "sveltekit-snippets" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

## [1.0.0] - 2021-11-23
### Initial Features
| Snippet     | Output                                                                 |
| ----------- | ---------------------------------------------------------------------- |
| kitComp     | Scaffolds a Svelte component                                           |
| ktiCompTs   | Scaffolds a TypeScript Svelte component                                |
| kitModule   | Scaffolds a SvelteKit module component for a page or layout            |
| kitModuleTs | Scaffolds a SvelteKit Typescript module component for a page or layout |
| kitLayout   | Scaffolds a SvelteKit Layout component                                 |
| kitPrefetch | Create a sveltekit:prefetch anchor tag                                 |
| kitEach     | Create a Svelte `{#each}` block                                        |
| kitIf       | Create a Svelte `{#if}` block                                          |
| kitAwait    | Create a Svelte `{#await}` block                                       |
| kitKey      | Create a Svelte `{#key}` block                                         |
| kitTitle    | Create a title element in the document head                            |
| kitLoad     | Create a SvelteKit Load function                                       |
| kitEndpoint | Create a SvelteKit Endpoint                                            |

### Troubleshooting

 - To enable intellisense in MD files, add the following JSON to your global settings.json
 ```json
  "[markdown]": {
    "editor.quickSuggestions": true,
    "editor.wordBasedSuggestions": false
  },
 ```

