# Sync OAS files via GitHub Actions
Uses to show how to update spec on readme.com. Check https://docs.readme.com/reference/intro-to-the-readme-api
Only branch `main` is connected to README. When you change `petstore-API.json` in the `main` it will update API spec on README.

Step by step instruction:
1) Commit and push the new version of `petstore-API.json` to `from-build` branch. It could be done in scope of TC or octopus relase build pipeline. 
2) Merge `petstore-API.json` from `from-build` branch into `main` branch and apply needed changed. It should be done manually.
3) Resolve pull request in the `main` branch and commit changes.
4) Check result in the README
