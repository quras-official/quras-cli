<p align="center">
<img
    src="http://blockapi.quraswallet.org/quras/img/logo1.png"
    width="250px">
</p>

# quras-cli

This is the full node with console.
We can use quras-cli as consensus node with command.
For detailed documentation, see [blockapi.quraswallet.org](http://blockapi.quraswallet.org/quras-js/docs/en/whitepaper/wp-virtualmachine.html).

## Running consensus node
Run Quras-cli.exe.

Then open the wallet.
```
<i>open wallet [wallet_path]</i>
```
Run consensus.
```
<i>start consensus</i>
```

## Configuration

Open 'protocal.json' and check if protocol configuration is set correctly.
Objects in protocol configuration is as below.

|Object|Description|
|---|---|
|StandbyValidators|public key set of consensus wallets.|
|SeedList|network addresses of other consensus nodes|
|SystemFee|System fee for transaction|

## Runtime Environment
|OS Type|Version|
|---|---|
|Windows|Windows XP, 7, 8, 10|
