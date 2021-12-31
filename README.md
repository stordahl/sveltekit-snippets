![sveltekit-snippets icon](https://github.com/stordahl/sveltekit-snippets/blob/master/images/icon.png)
    
# sveltekit-snippets

The extension provides snippets for common patterns in SvelteKit &amp; Vanilla Svelte including...
- Components
- Logic Blocks
- Endpoints
- Load Functions
    
All snippets are prefixed with "kit" for brevity and scoped only for their appropriate placement in the Svelte component

## Snippets

|   Snippet   | Output |
|-------------|--------|
|   kitComp   | Scaffolds a Svelte component |
|  ktiCompTs  | Scaffolds a TypeScript Svelte component |
|  kitModule  | Scaffolds a SvelteKit module component for a page or layout |
| kitModuleTs | Scaffolds a SvelteKit Typescript module component for a page or layout |
|  kitLayout  | Scaffolds a SvelteKit Layout component |
| kitPrefetch | Create a sveltekit:prefetch anchor tag |
|   kitEach   | Create a Svelte `{#each}` block |
|    kitIf    | Create a Svelte `{#if}` block |
|   kitAwait  | Create a Svelte `{#await}` block |
|    kitKey   | Create a Svelte `{#key}` block |
|  kitTitle   | Create a title element in the document head |
|   kitLoad   | Create a SvelteKit Load function |
| kitEndpoint | Create a SvelteKit Endpoint |
| kitTsEndpoint | Create a SvelteKit TypeScript Endpoint |

## Troubleshooting

 - To enable intellisense in MD files for use with MDSvex, add the following JSON to your global settings.json
 ```json
  "[markdown]": {
    "editor.quickSuggestions": true,
    "editor.wordBasedSuggestions": false
  },
 ```

## Issues

Issues are welcome and encouraged! Please describe the issue as thoroughly as you can – Contribution guidelines are forthcoming.
