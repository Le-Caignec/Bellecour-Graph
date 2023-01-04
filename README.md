# Bellecour-Graph

This subgraph is used to index all the ERC721 smart-contract data of the Bellecour blockchain. So it will index all the NFTs, Datasets, WorkerPAss, ...

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

```bash
npm run create-local
npm run deploy-local
```
