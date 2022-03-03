## Schedule

2022.3.3 Stop the lending business and liquidate the staking assets
2022.3.7 The Vapor stops running, and the assets take a snapshot
2022.3.8 BMC goes online, regular asset mapping

## Migration Process

### 1.Bycoin

#### For auto-mapped assets

1.Update to the lastest version of Bycoin and creat the BMC wallet
2.Wait for assets to be mapped automatically

Auto-mapped assets:
BTC
ETH
ERC20 assets（USDT，DAI，USDC，HT，GT，LINK，OKB，ZKS，mBTM，SHIB，HOKK，KISHU，Bytom(erc-20) ）
BTM
BAP20 assets（SUP，MAG）

Mapping business scope: including balance, superconducting pool, lending pool, node voting and locked assets

#### For unmapped assets

Contact the Bycoin official, provide the address, cross-chain proof,  main chain address for transfering out and other information, and wait for transfer out

Unmapped assets：
LTC
DOT
BTMC

### 2. Byone

Enter Secret Recovery Phrase of Byone into Bycoin and migrate it according to the Bycoin method

### 3. Vapor full node wallet

Contact Bytom official, provide address, signature and transfer out main chain address, wait for transfer out

### 4.FAQ

**1.What will happen after Vapor stops running?**

After stopping, blocks will not be generated, transfers and transactions will not be generated, and all operations on the chain will be stopped (including Super TX, Magnet TX)

**2.When can get the mapped assets after BMC goes online?**

Because mapped assets needs to be bound to BMC address, so needs upgrade to the latest version to generate a BMC address at first. The system will regularly detect the new BMC address, and then map the corresponding Vapor assets to this address. Generally, this process may take several hours.