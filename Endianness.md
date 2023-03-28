In general, Bitcoin data structures such as transaction IDs, block hashes, and some integers are represented in little-endian byte order. However, some values such as script lengths are represented in big-endian byte order.

Here is a breakdown of the fields in the HTML form and their endianness:

## Little-endian:

- version
- inputTXID
- inputVOUT
- inputScriptSigSize
- inputScriptSig
- inputSequence
- outputValue
- outputScriptPubKeySize
- outputScriptPubKey
- locktime

## Big-endian:

- inputCount
- outputCount

Note that some fields, such as public keys and private keys, are not represented in any particular endianness since they are just arbitrary strings of bytes.
