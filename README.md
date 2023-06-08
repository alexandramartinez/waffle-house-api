# Waffle House API

API spec + implementation created during the ACB live stream for June 2023

## Live stream

During the live stream, I was following these docs: 

- [What's New (June 2023)](https://docs.mulesoft.com/anypoint-code-builder/whats-new#june-2023)
- [Implement a Local API Specification](https://docs.mulesoft.com/anypoint-code-builder/implement-local-api-specification)
- [Work with Code Snippets](https://docs.mulesoft.com/anypoint-code-builder/work-with-code-snippets)

The recorded video can be found here:
- [What's new in Anypoint Code Builder?? | June 2023 update](https://youtu.be/tiyRtvQJypw)

## About the Project

1. I created a `waffle house` folder, which is where the API specification is located (in `waffle-house.raml`).
2. After scaffolding the API spec, the `wafflehouseapi` folder was created with the API implementation.
3. When there were changes done to the API specification, we could re-scaffold the implementation by opening the command palette (`cmd+shift+P` for Mac) and selected `MuleSoft: Re-scaffold this local API`.
4. We created User Snippets by clicking the `+` button in the canvas and selecting `User Snippets`.
5. Click on the `+` button from this window to create the `mule-xml.json` file. I added this file as part of this repo, but in reality this file will be located under a different folder.
6. We created our snippets to try them out. After creating them, you're supposed to click on the refresh button from the snippets window, but this didn't work for us immediately. We had to refresh the whole browser window to see the changes.

That's all!