# SaladQL.com GraphQL Saas
## an alternative to rolling your own graphql

[SaladQL.com ](https://saladql.com) is simple, fast GraphQL deployed
for arbitrary endpoints instantly.

## usage
```bash
curl -v --silent -qgk <REDACTED>/graph?runGraph=‘{bitcoin bitcoinCash bitcoinSv bitcoinTestnet dash dogecoin ethereum groestlcoin litecoin nodes ripple stats stellar tonTestnet}’
```

### This autogenerated server supports the following queries:
```yaml
- tonTestnet()
- stellar()
- stats()
- ripple()
- nodes()
- litecoin()
- groestlcoin()
- ethereum()
- dogecoin()
- dash()
- bitcoinTestnet()
- bitcoinSv()
- bitcoinCash()
- bitcoin()
- XrpChainStats(xrp_chain:, )
- XrpChainRawTransactionhash(xrp_chain:, rw_hash:, )
- XrpChainRawLedgerheight(xrp_chain:, height:, )
- XrpChainRawLedgerhash(xrp_chain:, rw_hash:, )
- XrpChainRawAccountaddress(xrp_chain:, address:, )
- XlmChainStats(xlm_chain:, )
- XlmChainRawTransactionhash(xlm_chain:, rw_hash:, )
- XlmChainRawLedgerheight(xlm_chain:, height:, )
- XlmChainRawAccountaddress(xlm_chain:, address:, )
- TonChainStats(ton_chain:, )
- TonChainRawTransactiontuple(ton_chain:, tuple:, )
- TonChainRawBlocktuple(ton_chain:, tuple:, )
- TonChainRawAccountaddress(ton_chain:, address:, )
- EthChainUncles(eth_chain:, query:, )
- EthChainTransactions(eth_chain:, query:, )
- EthChainStats(eth_chain:, )
- EthChainRawTransactionhash(eth_chain:, rw_hash:, )
- EthChainRawBlockheight(eth_chain:, height:, )
- EthChainRawBlockhash(eth_chain:, rw_hash:, )
- EthChainPushTransaction(eth_chain:, )
- EthChainMempoolTransactions(eth_chain:, query:, )
- EthChainDashboardsUncleshash(eth_chain:, rw_hash:, )
- EthChainDashboardsUnclehash(eth_chain:, rw_hash:, )
- EthChainDashboardsTransactionshash(eth_chain:, rw_hash:, )
- EthChainDashboardsTransactionhash(eth_chain:, rw_hash:, )
- EthChainDashboardsBlocksheight(eth_chain:, height:, )
- EthChainDashboardsBlockshash(eth_chain:, rw_hash:, )
- EthChainDashboardsBlockheight(eth_chain:, height:, )
- EthChainDashboardsBlockhash(eth_chain:, rw_hash:, )
- EthChainDashboardsAddressaddress(eth_chain:, address:, )
- EthChainCalls(eth_chain:, query:, )
- EthChainBlocks(eth_chain:, query:, )
- BtcChainTransactions(btc_chain:, query:, )
- BtcChainStats(btc_chain:, )
- BtcChainRawTransactionhash(btc_chain:, rw_hash:, )
- BtcChainRawBlockheight(btc_chain:, height:, )
- BtcChainRawBlockhash(btc_chain:, rw_hash:, )
- BtcChainPushTransaction(btc_chain:, )
- BtcChainOutputs(btc_chain:, query:, )
- BtcChainNodes(btc_chain:, )
- BtcChainMempoolTransactions(btc_chain:, query:, )
- BtcChainMempoolOutputs(btc_chain:, query:, )
- BtcChainDashboardsXpubextendedKey(btc_chain:, extended_key:, )
- BtcChainDashboardsTransactionshash(btc_chain:, rw_hash:, )
- BtcChainDashboardsTransactionhash(btc_chain:, rw_hash:, )
- BtcChainDashboardsBlocksheight(btc_chain:, height:, )
- BtcChainDashboardsBlockshash(btc_chain:, rw_hash:, )
- BtcChainDashboardsBlockheight(btc_chain:, height:, )
- BtcChainDashboardsBlockhash(btc_chain:, rw_hash:, )
- BtcChainDashboardsAddressesaddress(btc_chain:, address:, )
- BtcChainDashboardsAddressaddress(btc_chain:, address:, )
- BtcChainBlocks(btc_chain:, query:, )
- BtcChainAddresses(btc_chain:, query:, )

```


### More Docs coming soon!

![Data Graph](https://github.com/saladql/BlockChair.com/blob/master/blockChair.png)
