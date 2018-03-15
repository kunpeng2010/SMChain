# SMChain

SmartMesh Chain is an [Ethereum-based](https://github.com/SmartMeshFoundation/SMChain) and use new consensus and new block reward for SmartMesh ecosystem devices and IOT. 


SMChain is still in the development stage

SMChain is still in the development stage, and this version is just for testing.

## Building the source

Building smc requires both a Go (Version 1.9.2 or later) and a C cimpiler. You can install them using your favourite package manager. Once the dependencies are installed, run
    make geth

or, to build the full suite of utilities:
    make all

## Running full node test geth

    $ ./build/bin/geth --testnet console


## Connect to the testnet

    > admin.addPeer("enode://963ab76ecf41a5a214f5892bf4679d0f421b216aa514a942a20d865334689610cb50ceeab8f9fe44404d40eb1b9aa41bb61e2b04485895afb7bc02f1184b0b6d@49.51.11.222:60303")

    wait a few second, and you will see the block sync is begin

## View the miner node
    > tribe.getStatus()

    then you will see the following message,
    {
        number: 243,
        signers: [{
            address: "0x4110bd1ff0b73fa12c259acf39c950277f266787",
            score: 3
        }, {
            address: "0x76d564fe610ddf349333acbfe4a58abfd1d3ca04",
            score: 3
        }],
        volunteers: []
    }

    that tell you there are two miner in the testnet

## more works
    more functions is now under development, and will show you later.

