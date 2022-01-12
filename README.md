# ERC721 token standard
## Creación de una colección de NFT's end to end 

```shell
- Se compilan los contratos
- Se deploya el Factory Contract
- Se fondea el Factory con Link tokens para utilizar random & unique ids (en este caso en particular)
- Se deploya un NFT como parte de una colección -del Factory Contract-
- Se crea la metadata de ese nft
- Se sube a IPFS (Pudiendo pinearse a pinata para que no es encuentre solo en nuestro nodo)
- Se setea el tokenURI de la metadata -erc721 setTokenURI function- al NFT ya creado. 
```

NFT's factory, y colección de NFT's deployado en Rinkeby testnet, y renderizados en la web testnet de OpenSea para su venta
- `Factory Contract: https://rinkeby.etherscan.io/address/0x84fd7fe79d4e0f14f32c1570f372a214cd5636aa`
- `Owner del Factory C: 0x709887290F0193FF7A2291beE8EB883Cf1770292`
- `Colección NTFs creada: 
    - https://testnets.opensea.io/assets/0x84fD7fe79d4E0f14f32c1570F372A214cd5636aa/0
    - https://testnets.opensea.io/assets/0x84fD7fe79d4E0f14f32c1570F372A214cd5636aa/1
    - https://testnets.opensea.io/assets/0x84fD7fe79d4E0f14f32c1570F372A214cd5636aa/2
    `

Folders:
- /contracts => solidity contracts
- /img => png's de imagenes asociadas al NFT
- /interfaces => interfaz de Link token
- /metadata => JSON files para setTokenURI del NFT
- /scripts => scripts en Python para deploy, minteo, seteo de metadata de los NFT's

Para mas info: 
- https://github.com/brownie-mix/nft-mix
Patrick Collins:
- https://www.youtube.com/watch?v=p36tXHX1JD8
