# local-besu-setup

This repo provides a convinient way to setup a local 4 node Hyperledger Besu network for application development

## Prerequisit
- For windows, Git Bash or WSL is needed

## Steps to setup

1. Donwload the Hyperledger Besu binaries from [Jfrog](https://hyperledger.jfrog.io/artifactory/besu-binaries/besu/23.10.2/besu-23.10.2.zip)
2. Unzip the file
3. Update the Environment Variable path by setting it to the bin folder in the unzipped folder. With this, you can access besu from any terminal throughout your system
4. In scripts folder in the repo, open 4 git bash terminals.
5. Run each node.sh file in seperate git bash terminal.
6. The network should be able to connect with the nodes as static-nodes have been defined
7. To cleanup the network, use cleanup.sh script.
