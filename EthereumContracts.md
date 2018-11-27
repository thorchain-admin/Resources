# CanYa Project Ethereum Contracts

> All ethereum based contract addresses and notes used in the CanYa project

### MainNet

**CanYa SmartContracts**

| Name | Address | Owner | Solidity Version | Notes |
| --- | --- | --- | --- | --- |
|CAN20|0x1d462414fe14cf489c7a21cac78509f4bf8cd7c0|CanYaHQ-1|0.4.15|ERC20|
|CAN223|0x0|CanYaHQ-1|0.5.0|ERC223 with network fee|
|TokenSwap|0x0|-|0.5.0|Swap from CAN20 to CAN223|
|AssetSplit|0x0|-|0.5.0|Splits to DAO recipients|
|CanWork-Escrow|0x6890f982416a44589cb044d2b136d8dce44483df|-|0.4.24|Proxy contract -> current impl of CanWork|
|CanWork-Admin|0x7c0d049bcc125c3276da0a2fc59e36b89bab1ff4|-|???|Proxy contract -> current impl of admin app used to manage user auth|
|CanHire|0xfd6fa39c22412de6bbc3684b130fb4cab89bebae|-|???|Main contract handling job posting etc|
|CanHire-Escrow|0x4c540ae83ebe431ea17493bec3805f607085a5a9|-|???|Controls flow of money between user and CanSeek|

**ThirdParty SmartContracts**

| Name | Address | Owner | Solidity Version | Notes |
| --- | --- | --- | --- | --- |
|PriceOracle|0x6B22026eb0B17D4d5e48cE99B7104e90baB1c652|-|?|Price oracle for CAN:BNT used in value calculations|
|PriceOracleBase|0xB50DDE894b4083db9cb1F2eFC57deAA11C7cB485|-|?|Price oracle for BNT:DAI used in value calculations|
|BancorConverter|0x5142127A6703F5Fc80BF11b7b57fF68998F218E4|-|0.4.21|CAN - BNT Bancor Converter|
|BancorConverter|0x587044b74004E3D5eF2D453b7F8d198d9e4cB558|-|0.4.21|BNT - DAI Bancor Converter|

**Multi-sigs**

**Addresses**

| Name | Address | Owner | Notes |
| --- | --- | --- | --- |
|Ops Wallet|0x8c7C4814d2512AF1029719803c42fe7b629d51c8|CL1-2|CanYa Ops Wallet|
|DAO|0x685678927216DF235A4A5A952EfE88ed55e62Ff2|CL1-3|DAO Address|
|CanYa|0xF6C969DEaAb707a4F5B2Ce2103CC00d084cc893E|CL1-4|CanYa Wallet|
|Charity|0xcB6f7fD9A84452d23d44106A8aA3f8C62520Bb89|CL1-5|Charity Wallet|
|CAN-BancorRelay|0x856D41AB6e3128bd9f49E168230CD78cE7C1E045|CL1-12|Bancor Relay Owner|

### Ropsten

| Name | Address | Owner | Solidity Version | Notes |
| --- | --- | --- | --- | --- |
|CAN20|0x38d89a3bd248f238fc467cd8a45c548a5b70659e|CanYaHQ-1|0.4.15|ERC20|
|CAN20|0xee9154ab6366416e80a1eb718954abe2ae406274|CanYaHQ-1|0.4.15|ERC20|
|CAN223|0x0|CanYaHQ-1|0.5.0|ERC223 with network fee|
|TokenSwap|0x0|-|0.5.0|Swap from CAN20 to CAN223|
|AssetSplit|0x0|-|0.5.0|Splits to DAO recipients|
|CanWork-Escrow|0xae713a4428e61bfedacde3480b8699cef2940930|-|0.4.24|Proxy contract -> current impl of CanWork|
|CanWork-Admin|0xe7da39f5edd865f0d52f2793dc8e4d82dfa10f10|-|???|Proxy contract -> current impl of admin app used to manage user auth|
|CanHire|0x43461f82584da6e714d4745470a97ee745629ba2|-|???|Main contract handling job posting etc|
|CanHire-Escrow|0x021224710e96181acf84a5eeb5114652e3e622c9|-|???|Controls flow of money between user and CanSeek|

**ThirdParty SmartContracts**

| Name | Address | Owner | Solidity Version | Notes |
| --- | --- | --- | --- | --- |
|PriceOracle|0x2d60C66E51Da17384ED2E05f6aBFE63551979eA3|-|?|Price oracle for CAN:BNT used in value calculations|
|PriceOracleBase|0x625A2E3Ca1EBfa4c580C97cfc5187D4A46a7C14C|-|?|Price oracle for BNT:DAI used in value calculations|
|Bancor-Converter|0xf388f8bD7aAEE44524CFA8f91Eb78A799F71060E|-|0.4.21|CAN - BNT Bancor Converter|
|Bancor-Converter|0x634bE2E2a1Abb279F08A071a2d05DAD3c2282c9D|-|0.4.21|BNT - DAI Bancor Converter|
