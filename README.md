# Lamina1
Guide To Run a Lamina1 Node

## Install Node
```
echo "deb [trusted=yes arch=amd64] https://snapshotter.lamina1.global/ubuntu jammy main" > /etc/apt/sources.list.d/lamina1.list && 
apt update && 
apt install lamina1-node
```

## Connect To Lamina1
```
sudo systemctl status lamina1-node.testnet
```
## Generate NodeID
```
lamina1.get_my_nodeid.sh
```
`NodeID-[string]` is your NodeID

## Create Lamina1 Wallet
https://wallet-test.lamina1.network/

## Claim L1 tokens From Faucet
https://faucet-test.lamina1.network/

## Transfer Tokens From C-Chain To P-Chain
https://wallet-test.lamina1.network/wallet/cross_chain
![Screenshot 2023-08-17 233034](https://github.com/blacknodes/lamina1/assets/85839823/627ed3fc-3a3d-4486-824b-9467fa9d67b6)


## Delegate Tokens To a Validator Node
https://wallet-test.lamina1.network/wallet/earn
Click on add Delegator
![Screenshot 2023-08-17 232959](https://github.com/blacknodes/lamina1/assets/85839823/175de957-f734-4c73-8fcb-3ec9b9dccf6a)

Search NodeID to whom you want to Delegate
![Screenshot 2023-08-17 233234](https://github.com/blacknodes/lamina1/assets/85839823/042cca17-7af3-4727-bba8-a7049a2d83ed)

### Congratulations All The Steps Are Completed


