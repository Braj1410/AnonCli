# AnonCli


```bash
$ npm install
```

### Rinkeby
1. Add `PRIVATE_KEY` to `.env` file
2. `node cli.js --help`

#### To deposit:

```bash
$ node cli.js deposit <currency> <amount> --rpc <rpc url>
```


For RPC nodes please refer to the list of public RPC nodes below.

##### Example:
```bash
$ node cli.js deposit eth 0.1 --rpc https://rinkeby.infura.io/v3/4ab7fb02daf842d89fed5600dc7345e2

Your note: tornado-eth-0.1-5-0xf73dd6833ccbcc046c44228c8e2aa312bf49e08389dadc7c65e6a73239867b7ef49c705c4db227e2fadd8489a494b6880bdcb6016047e019d1abec1c7652
Tornado ETH balance is 0.1
Sender account ETH balance is 1004873.470619891361352542
Submitting deposit transaction
Tornado ETH balance is 9
Sender account ETH balance is 1004873.361652048361352542
```

#### To withdraw:

```bash
$ node cli.js withdraw <note> <recipient> --rpc <rpc url> 
```

##### Example:
```bash
$ node cli.js withdraw anon-eth-0.1-4-0xa069379b81dfdc95979585710d7a3f69246615ea926c02927ac87164702c27d41572bdb38d06c0a7b5b86ac749790d197f273f0805b87788aa9514f3136f 0xff09024F06499a8B619717795499cBb91EeDC1F1 --rpc https://rinkeby.infura.io/v3/4ab7fb02daf842d89fed5600dc7345e2

```
