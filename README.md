# OpenZepplin Subgraph ERC-20 ERC-721 ERC-1155

`npm install`

```
npx graph-compiler \
  --config configs/sample.json \
  --include node_modules/@openzeppelin/subgraphs/src/datasources \
  --export-schema \
  --export-subgraph
```

get username and subgraph from hosted url

<img width="1320" alt="Screen Shot 2022-02-24 at 9 53 07 PM" src="https://user-images.githubusercontent.com/19412160/155644989-4f3fb46a-9667-42ef-ba4b-290bfb7de683.png">

```
graph deploy --product hosted-service \
  leon-do/ropsten-erc20-erc721-erc1155 \
  ./generated/sample.subgraph.yaml
```