# Tezos_4IBC Project (2024)
![Logo](https://socialify.git.ci/CoralieBo/Tezos_4IBC/image?font=Inter&language=1&name=1&owner=1&pattern=Brick%20Wall&theme=Dark)

This project contain a Vesting contract (locked tokens) and his tests.
## Authors

- [@Coralie Boyer](https://github.com/coralieBo/)

## Features

- **FA2 implementation**
- `start entrypoint` *transfers vested tokens to the contract, and set the starting time and the vesting starting time.*
- `addBeneficiary entrypoint` *add beneficiaries befor the starting time*
- `claim entrypoint` *transfers available amount of tokens to the beneficiary.*
- `kill entrypoint` *retrieve funds, and pay beneficiaries (on time elpased basis).*
## Installation

Install ligo to run this project

[Ligo compiler installation](https://ligolang.org/docs/intro/installation?lang=cameligo)
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PRIVATE_KEY`

`PUBLIC_KEY`


## Running Tests

To run tests, run the following command :

```bash
make test
```

Or run tests on a single exercice :

```bash
make test SUITE=file_name
```
## Compilation

To compile this project run :

```bash
make compile
```
## Deployment

To deploy this project run :

```bash
make deploy
```
