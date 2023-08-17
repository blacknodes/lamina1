# lamina1
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

## Delegate Tokens To a Validator Node
https://wallet-test.lamina1.network/wallet/earn

### Congratulations All The Steps Are Completed


