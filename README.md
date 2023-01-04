# Openzeppelin subgraphs for bellecour

This repository contains scripts with configuartion : erc20.json, erc721.json, erc1155.json to generate the subgraph for the following standard tokens: ERC20, ERC721, ERC1155.
You can add more json files to generate subgraph for other standard tokens.

### Suported modules

- AccessControl
- ERC20
- ERC721
- ERC1155
- ERC1967Upgrade
- Governor
- Ownable
- Pausable
- Timelock

## Install the dependency

```bash
npm install
```

## Generate the Schema & Subgraph

```bash
npm run build -- --config erc721.json
```

## Deploy the subgraph

#### Deploy to the graph on a local node

Don't forget to modify the name of the subgraph that you will creat in the `package.json` file.

```bash
npm run create-local
npm run deploy-local
```
