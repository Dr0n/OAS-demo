# Sync OAS files via GitHub Actions
Uses to show how to update spec on readme.com. Check https://docs.readme.com/reference/intro-to-the-readme-api
Only branch `petstore-relase` is connected to README.
`petstore-API.json` is the simple example of OAS file
Step by step instruction:
1) Commit and push the new version of `petstore-API.json` to `main` branch. It could be done in scope of TC or octopus relase build pipeline. 
2) Merge `petstore-API.json` from main into `petstore-relase` branch and apply needed changed. It should be done manually.
3) Commit and push merge changes into `petstore-relase`
4) Check result in the README
