# Velluscinum Command Line Interface

|![](https://github.com/chon-group/Velluscinum/wiki/.imgs/CLI/velluscinum-CLI.png)|
|:-:|
|Velluscinum-CLI is command-line API to manipulate the [BigchainDB](https://github.com/bigchaindb/bigchaindb), the blockchain database.|
 

## How to install?

In a terminal, execute the steps described below:

```console
echo "deb [trusted=yes] http://packages.chon.group/ chonos main" | sudo tee /etc/apt/sources.list.d/chonos.list
sudo apt update
sudo apt install velluscinum-cli
```

## Velluscinum FAQ (Frequently asked question): See the [Velluscinum Wiki](https://github.com/chon-group/Velluscinum/wiki/Velluscinum-CLI).

### DESCRIPTION 
|__Argument__|__Description__|
|:--|---|
|[buildWallet](https://github.com/chon-group/Velluscinum/wiki/buildWallet-CLI)  |Creates a pair of files with an ECDSA keyset in Base58.|
|[walletBalance](https://github.com/chon-group/Velluscinum/wiki/walletBalance-CLI) |Lists the content of a Wallet.|
|[showToken](https://github.com/chon-group/Velluscinum/wiki/showToken-CLI) |Lists the content of a Token.|
|||
|[buildAsset](https://github.com/chon-group/Velluscinum/wiki/buildAsset-CLI)   |Generates a file with Data and MetaData about an ASSET.|
|[deployNFT](https://github.com/chon-group/Velluscinum/wiki/deployNFT-CLI)    |Deploys a Non-Fungible-Token in the BigChainBD Network.|
|[deployToken](https://github.com/chon-group/Velluscinum/wiki/deployToken-CLI)  |Deploys a Token in the BigChainBD Network.|
|||
|[buildTransfer](https://github.com/chon-group/Velluscinum/wiki/buildTransfer-CLI)|Generates a file with Metadata about the TRANSFER of an ASSET.|
|[transferNFT](https://github.com/chon-group/Velluscinum/wiki/transferNFT-CLI)  |Transfer a Non-Fungible-Token in the BigChainDB Network.|
|[transferToken](https://github.com/chon-group/Velluscinum/wiki/transferToken-CLI)|Transfer parts of a Token in the BigChainDB Network.|
|[stampTransaction](https://github.com/chon-group/Velluscinum/wiki/stampTransaction-CLI)|Stamps a Transaction in the BigChainDB Network.|


## COPYRIGHT
![](https://i.creativecommons.org/l/by/4.0/88x31.png)

Velluscinum is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). The licensor cannot revoke these freedoms as long as you follow the license terms:

* __Attribution__ — You must give __appropriate credit__ like below:

Mori Lazarin, N., Machado Coelho, I., Pantoja, C.E., Viterbo, J. (2023). Velluscinum: A Middleware for Using Digital Assets in Multi-agent Systems. In: Mathieu, P., Dignum, F., Novais, P., De la Prieta, F. (eds) Advances in Practical Applications of Agents, Multi-Agent Systems, and Cognitive Mimetics. The PAAMS Collection. PAAMS 2023. Lecture Notes in Computer Science(), vol 13955. Springer, Cham. DOI: [https://doi.org/10.1007/978-3-031-37616-0_17](https://www.researchgate.net/publication/372282299_Velluscinum_A_Middleware_for_Using_Digital_Assets_in_Multi-agent_Systems)


<details>
<summary> Cite using Bibtex </summary>

```
@InProceedings{velluscinum,
author="Mori Lazarin, Nilson
and Machado Coelho, Igor
and Pantoja, Carlos Eduardo
and Viterbo, Jos{\'e}",
editor="Mathieu, Philippe
and Dignum, Frank
and Novais, Paulo
and De la Prieta, Fernando",
title="{Velluscinum: A Middleware for Using Digital Assets in Multi-agent Systems}",
doi="10.1007/978-3-031-37616-0_17",
booktitle="Advances in Practical Applications of Agents, Multi-Agent Systems, and Cognitive Mimetics. The PAAMS Collection",
year="2023",
publisher="Springer Nature Switzerland",
address="Cham",
pages="200--212",
isbn="978-3-031-37616-0"
}
```
</details>
