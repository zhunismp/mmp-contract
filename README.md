# MMP-CONTRACT
*This repository is part of MMP project. Only Centralized protobuf repository to stored contract between among services*

## Import client library
We are using [**Buf schema registry**](https://buf.build/product/bsr) to store protobuf and publish client library in many programming languages.

To download client library, you can follow below instruction
1. Checkout buf schema registry for **mmp-contract** repository [here](https://buf.build/zhunismp/mmp-contract/sdks/main:protobuf)
2. Select your desired programming language.
3. Follow instruction show in Buf schema registry.

> Note: We do maintain backward compatability in our system. You can trust that newer version won't break your service.

## Contributing
You can open a pull request to add new contract for new service or editing existing contract. This should be add under `/proto` with proper versioning.
