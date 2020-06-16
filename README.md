Français:
# Election - Tutoriel DAPP
Créez votre première application décentralisée, ou Dapp, sur le réseau Ethereum avec ce tutoriel!

Suivez les étapes ci-dessous pour télécharger, installer et exécuter ce projet.

## Dépendances
Installez ces prérequis:
- NPM: https://nodejs.org
- Truffe: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Métamask: https://metamask.io/


## Étape 1. Clonez le projet
`git clone https://github.com/mouka99/ElectionDappEth

## Étape 2. Installer les dépendances
`` ''
$ cd election
$ npm install
`` ''
## Étape 3. Démarrez Ganache
Ouvrez le client Ganache GUI que vous avez téléchargé et installé. Cela démarrera votre instance de blockchain locale.


## Étape 4. Compiler et déployer le contrat intelligent d'élection
`$ truffle migrate --reset`
Vous devez migrer le smart contract d'élection chaque fois que vous redémarrez la ganache.

## Étape 5. Configurer le metamask
- Déverrouillez le metamask
- Connectez le metamask à votre blockchain Etherum locale fournie par Ganache.
- Importez un compte fourni par Ganache.

## Étape 6. Exécutez l'application frontale
`$ npm run dev`
Visitez cette URL dans votre navigateur: http: // localhost: 3000

English: 

# Election - DAPP Tutorial
Build your first decentralized application, or Dapp, on the Ethereum Network with this tutorial!

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites:
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/mouka99/ElectionDappEth

## Step 2. Install dependencies
```
$ cd election
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.

## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000
