# snarkWrapper: zksnarks on ethereum helper

A snarkWrapper that takes two files `vk.json` and `pk.json` and deploys a contract verifys the proof in `pk.json` 
with the `vk.json`.

## Using snarkWrapper 

The intention is the include this a submodule in a project and to add your required contracts in a fork of the base. 
The libary expects to find `vk.json` and `pk.json` in the parent directory in a folder called `zksnark_element`.

## Usage 
`npm install`

place in a directory where `../zksnark_element` contains `proof.json` and `vk.json` containg vk.json and proof.json. 
See examples folder.

To deploy and test verifcation do `node deploy.js` with an ethereum node running on the default port
