# Connect to Rocky
```bash
./target/release/crust --chain rocky
```
# Run as Dev
```bash
./target/release/crust purge-chain --dev
./target/release/crust --dev
```

# Bootnodes
## Alice
```bash
./target/release/crust \
  --base-path /tmp/alice \
  --chain local \
  --alice \
  --node-key 0000000000000000000000000000000000000000000000000000000000000001
  ```
  
  ## Bob
  ```bash
  ./target/release/crust \
  --base-path /tmp/bob \
  --chain local \
  --bob \
  --port 30334 \
  --bootnodes /ip4/127.0.0.1/tcp/30333/p2p/12D3KooWEyoppNCUx8Yx66oV9fJnriXwCcXwDDUA2kj6vnc6iDEp
  ```
 
 
 # Polkadot
 ```bash
 yarn run start
 ```
