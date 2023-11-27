# Sandbox Quick Start Guides
Sandbox quickstart guides on EDS 

## Environments
- Preview: https://main--quickstartguides-eds--adobepartnertechnicalservices.hlx.page (This will change in future)
- Live: https://main--quickstartguides-eds--adobepartnertechnicalservices.hlx.live (This will change in future)

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Checkout the code from QuickstartGuides-EDS repository
2. Update the mount point of local copy in "fstab.yaml"
3. Install the [AEM CLI] using command`npm install -g @adobe/aem-cli`
4. Start AEM Proxy by command `aem up` (opens your browser at `http://localhost:3000`)
5. Open the `{repo}` directory in your favorite IDE and start coding :)
