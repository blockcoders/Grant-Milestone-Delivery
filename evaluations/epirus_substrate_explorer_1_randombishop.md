# Evaluation



- **Status:** Accepted
- **Application Document:** [Epirus Phase II](https://github.com/web3labs/Grants-Program/blob/master/applications/epirus_substrate_phase_2.md)
- **Milestone:** 1
- **Kusama Identity:** randombishop (https://sub.id/5Gnixfp6vnznRkr91JgwkxYnCJCyHr8EaBzYfFsUKcTMzVYF)
- **Previously successfully merged evaluation:** 

| Number | Deliverable                                   | Accepted | Link                                                                                                                                                                                                                                                                                                                                                                                                                                          | Evaluation Notes    |
|-------:|-----------------------------------------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
|    0a. | License                                       | Yes      | Server: https://github.com/web3labs/ink-verifier-server/blob/main/LICENSE <br /> Image: https://github.com/web3labs/ink-verifier-image/blob/main/LICENSE <br /> UI: https://github.com/web3labs/epirus-substrate/blob/main/LICENSE                                                                                                                                                                                                            | Apache 2.0          |                                                                                                                       |
|    0b. | Documentation                                 | Yes      | Server: https://github.com/web3labs/ink-verifier-server/blob/main/README.md <br /> Image: https://github.com/web3labs/ink-verifier-image/blob/main/README.md <br /> Tutorial: https://github.com/web3labs/ink-verifier-server/blob/main/docs/TUTORIAL.md                                                                                                                                                                                      | Good documentation. |
|    0c. | Testing                                       | Yes      | Server unit tests: https://github.com/web3labs/ink-verifier-server/blob/main/README.md#testing <br /> UI unit tests: https://github.com/web3labs/epirus-substrate/blob/main/explorer-ui/README.md#testing                                                                                                                                                                                                                                     | OK                  |
|    0d. | Docker                                        | Yes      | ink! Verifier Docker image: [ghcr.io/web3labs/ink-verifier:latest](https://github.com/web3labs/ink-verifier-image/pkgs/container/ink-verifier) <br /> UI Docker image: [ghcr.io/web3labs/epirus-substrate-ui:latest](https://github.com/web3labs/epirus-substrate/pkgs/container/epirus-substrate-ui) <br /> Docker compose for running all explorer components locally: https://github.com/web3labs/epirus-substrate/tree/main/local-testnet | OK                  |
|     1. | Metadata Registry (now ink! Verifier Service) | Yes      | Server: https://github.com/web3labs/ink-verifier-server <br /> Image used by server: https://github.com/web3labs/ink-verifier-image                                                                                                                                                                                                                                                                                                           | OK                  |
|     2. | Developer Tools                               | Yes      | https://github.com/web3labs/ink-verifier-image/tree/main/cli                                                                                                                                                                                                                                                                                                                                                                                  | OK                  |
|     3. | Updated Explorer UI                           | Yes      | https://github.com/web3labs/epirus-substrate/tree/main/explorer-ui                                                                                                                                                                                                                                                                                                                                                                            | OK                  |
|     4. | Public explorer instance                      | Yes      | https://substrate.sirato.xyz                                                                                                                                                                                                                                                                                                                                                                                                                  | Looks good.         |


## General Notes

Impressive codebase, very well documented, tests pass from first try, and nice end-to-end product.
