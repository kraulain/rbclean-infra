# rbclean-infra

### How to render the documentation

- Open a terminal window and move to the root of this repository
- Install Redoc CLI with the command `npm i redoc-cli g`
- Serve the spec file with `npx redoc-cli serve rbclean.yaml`
- Create a deployable zero-dependency HTML file
- Generate the html with `npx redoc-cli bundle rbclean.yaml`