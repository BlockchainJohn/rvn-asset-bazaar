# rvn-asset-bazaar

**Note: Lightweight vs core-tap.  For low volume assets, API calls should work, but for large volume a version of this app that uses ravend needs to built 










curl -s https://blockchain.info/tx/25ecdc29903aa8f80efb51a6b41ac036a91fe441aefd0d26df383827b9578cae\?format\=json | jq '.inputs[0]."prev_out".addr'
