# BlockChain-Test
Remember each block is linked to the previous block by a public variable sPrevHash
The constructor signature takes three parameters for nIndexIn and sDataIn
Blockchains use cryptography. therefore here we used SHA256 hashing technique to create hashes of our block. It is also possible that we can write our own cryptography but we need not to worry about it as we can get it from open source softwares.
You can get sha-256 functions in c++ from the following site: http://www.zedwood.com/article/cpp-sha256-function
The constructor starts off by repeating the signature we specified in the Block.h header file
but we also add code to copy the contents of the parameters into the the variables _nIndex, and _sData. The _nNonce variable is set to -1 and the _tTime variable sets the current time 
We specified the signature for GetHash function and then add a return for the private variable _sHash

