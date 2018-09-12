# parity-trace-decoder

Parity Trace Decoder to call tree

# Usage

Install dependencies
```
npm install
```

Run main script with file name argument, containing parity traces JSON array
```
node index.js 1.json
```

Example of transaction [0x1d3aac5004de6d3027eb6c8ec86bde589db4d563f26428e8738d36d07ef7994e](https://etherscan.io/tx/0x1d3aac5004de6d3027eb6c8ec86bde589db4d563f26428e8738d36d07ef7994e) parity trace decoding

```
* [1] approveAndCall(address,uint256,bytes)
    [2] makeCall(address,bytes)
    * [3] 0xfae9e186
        [4] tokensCount()
        [5] transferFrom(address,address,uint256)
        [6] 0xb4dc3dc7
          [7] balanceOf(address)
          [8] balanceOf(address)
          [9] transfer(address,uint256)
          [10] balanceOf(address)
          [11] balanceOf(address)
          [12] balanceOf(address)
          [13] transfer(address,uint256)
          [14] balanceOf(address)
          [15] balanceOf(address)
          [16] balanceOf(address)
          [17] transfer(address,uint256)
          [18] balanceOf(address)
          [19] balanceOf(address)
          [20] balanceOf(address)
          [21] transfer(address,uint256)
          [22] balanceOf(address)
        [23] tokens(uint256)
        [24] balanceOf(address)
        [25] approve(address,uint256)
        [26] claimAndConvert(address[],uint256,uint256)
          [27] transferFrom(address,address,uint256)
          [28] validateGasPrice(uint256)
          [29] getAddress(bytes32)
          [30] owner()
          [31] isSupported(address,uint256)
          [32] conversionWhitelist()
          [33] allowance(address,address)
          [34] allowance(address,address)
          [35] approve(address,uint256)
          [36] change(address,address,uint256,uint256)
            [37] getAddress(bytes32)
            [38] owner()
            [39] balanceOf(address)
            [40] balanceOf(address)
            [41] getAddress(bytes32)
            [42] calculateCrossConnectorReturn(uint256,uint32,uint256,uint32,uint256)
            [43] balanceOf(address)
            [44] transferFrom(address,address,uint256)
            [45] transfer(address,uint256)
            [46] totalSupply()
            [47] balanceOf(address)
            [48] totalSupply()
            [49] balanceOf(address)
          [50] owner()
          [51] isSupported(address,uint256)
          [52] conversionWhitelist()
          [53] change(address,address,uint256,uint256)
            [54] getAddress(bytes32)
            [55] balanceOf(address)
            [56] owner()
            [57] totalSupply()
            [58] getAddress(bytes32)
            [59] calculateSaleReturn(uint256,uint256,uint32,uint256)
            [60] totalSupply()
            [61] destroy(address,uint256)
            [62] transfer(address,uint256)
            [63] totalSupply()
          [64] withdrawTo(address,uint256)
            [65] 0x // => 0.000435095750715584 ETH
        [66] tokens(uint256)
        [67] balanceOf(address)
        [68] approve(address,uint256)
        [69] claimAndConvert(address[],uint256,uint256)
          [70] transferFrom(address,address,uint256)
          [71] validateGasPrice(uint256)
          [72] getAddress(bytes32)
          [73] owner()
          [74] isSupported(address,uint256)
          [75] allowance(address,address)
          [76] allowance(address,address)
          [77] approve(address,uint256)
          [78] change(address,address,uint256,uint256)
            [79] gasPriceLimit()
            [80] gasPrice()
            [81] owner()
            [82] totalSupply()
            [83] balanceOf(address)
            [84] formula()
            [85] calculatePurchaseReturn(uint256,uint256,uint32,uint256)
            [86] transferFrom(address,address,uint256)
            [87] issue(address,uint256)
            [88] balanceOf(address)
            [89] totalSupply()
            [90] decimals()
            [91] decimals()
            [92] gasPriceLimit()
            [93] gasPrice()
            [94] balanceOf(address)
            [95] totalSupply()
            [96] owner()
            [97] balanceOf(address)
            [98] formula()
            [99] calculateSaleReturn(uint256,uint256,uint32,uint256)
            [100] totalSupply()
            [101] balanceOf(address)
            [102] destroy(address,uint256)
            [103] transfer(address,uint256)
            [104] balanceOf(address)
            [105] totalSupply()
            [106] decimals()
            [107] decimals()
          [108] owner()
          [109] isSupported(address,uint256)
          [110] conversionWhitelist()
          [111] change(address,address,uint256,uint256)
            [112] getAddress(bytes32)
            [113] balanceOf(address)
            [114] owner()
            [115] totalSupply()
            [116] getAddress(bytes32)
            [117] calculateSaleReturn(uint256,uint256,uint32,uint256)
            [118] totalSupply()
            [119] destroy(address,uint256)
            [120] transfer(address,uint256)
            [121] totalSupply()
          [122] withdrawTo(address,uint256)
            [123] 0x // => 0.000313196114317456 ETH
        [124] tokens(uint256)
        [125] balanceOf(address)
        [126] approve(address,uint256)
      * [127] claimAndConvert(address[],uint256,uint256)
        # [128] transferFrom(address,address,uint256)
```