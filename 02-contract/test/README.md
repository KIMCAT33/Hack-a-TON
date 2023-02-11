# Hack-A-TON Korea Hacker House FunC Tutorial

![image]("https://oopy.lazyrockets.com/api/v2/notion/image?src=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F6777e345-4bb7-4d93-a538-b0d23e568650%2FUntitled.png&blockId=844d20b5-d961-4259-bade-ceca4fd12abf")

This directory helps us make sure that this tutorial is always working and none of the libraries it depends on has introduced breaking changes. The directory contains a simple automated test that performs all the steps and makes sure they work as expected.

If one of the steps isn't working for you, run the test and see if it passes on your machine. If it does, see where the test code is different from your code. If it doesn't, please open an issue and let us know so we can fix it asap.

The test runs weekly on CI, but you can run it manually in terminal:

```
./index.sh
```

Before running the test, create the file `.env` in the repo root with this content:
```
MNEMONIC="unfold sugar water ..."
```

This should be the 24 word mnemonic for a deployed testnet v4 wallet that contains at least 1 TON.