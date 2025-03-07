### Block Development Examples - Block Supports 6aa4dd

The goal of this example is to showcase the implementation of a block with `supports`

<!-- Please, do not remove these @TABLE EXAMPLES BEGIN and @TABLE EXAMPLES END comments or modify the table inside. This table is automatically generated from the data at _data/examples.json and _data/tags.json -->
<!-- @TABLE EXAMPLES BEGIN -->
| Folder                                                                                                 | <span style="display: inline-block; width:250px">Short description</span> | Tags                                                                                                                             | ID ([❓](https://github.com/WordPress/block-development-examples/wiki/04-Why-an-ID-for-every-example%3F "Why an ID for every example?")) | Download .zip                                                                                                                                                                                                                                                     | Live Demo                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [📁](https://github.com/WordPress/block-development-examples/tree/trunk/plugins/block-supports-6aa4dd) | Block Supports                                                            | <small><code><a href="https://github.com/WordPress/block-development-examples/wiki/03-Tags#supports">SUPPORTS</a></code></small> | `6aa4dd`                                                                                                                                | [📦](https://raw.githubusercontent.com/WordPress/block-development-examples/deploy/zips/block-supports-6aa4dd.zip "Install the plugin using this zip and activate it. Then use the ID of the block (6aa4dd) to find it and add it to a post to see it in action") | [![](https://raw.githubusercontent.com/WordPress/block-development-examples/trunk/_assets/icon-wp.svg)](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/WordPress/block-development-examples/trunk/plugins/block-supports-6aa4dd/_playground/blueprint.json "Use the ID of the block (6aa4dd) to find it and add it to a post to see it in action") |
<!-- @TABLE EXAMPLES END -->

## Understanding the Example Code

- The block has a [`supports` definition](https://github.com/WordPress/block-development-examples/blob/e804d8416775de94fccae27be6f26ae0ae75b3d9/plugins/block-supports-6aa4dd/src/block.json#L25) in its `block.json`
- The generated properties for `support` are properly added to the wrapping element of the block in both the `Edit` and `Save` components via the `useBlockProps` hook.

## Related resources

- [Block API: Supports](https://developer.wordpress.org/block-editor/reference-guides/block-api/block-supports/)
- [`useBlockProps` hook](https://developer.wordpress.org/block-editor/reference-guides/packages/packages-block-editor/#useblockprops) 

----

> **Note**
> Check the [Start Guide for local development with the examples](https://github.com/WordPress/block-development-examples/wiki/02-Examples#start-guide-for-local-development-with-the-examples)