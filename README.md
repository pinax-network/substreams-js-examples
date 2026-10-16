# Substreams Examples

## Requirements

- [Node.js (LTS or Current)](https://nodejs.org/en/)
- [Bun](https://bun.com/) >= 1.4.3

## Quickstart

```bash
$ git clone https://github.com/EOS-Nation/substreams-js-examples.git
$ cd substreams-js-examples
$ bun install
$ bun run start

Downloading: https://eos.mypinata.cloud/ipfs/Qmdf7GT6jaT9NB3XPLvss8YxuHiSAC1PP1xm9UqLbuouYT
Download completed: https://eos.mypinata.cloud/ipfs/Qmdf7GT6jaT9NB3XPLvss8YxuHiSAC1PP1xm9UqLbuouYT
ActionTrace {
  blockNum: 283000005,
  trxId: 'ee944bf8bc0591291a93c88cb7113f3196cda021b9c65a62bfe9c0bbf447d674',
  actionOrdinal: 3,
  account: 'prospectorsg',
  receiver: 'prospectorsg',
  name: 'transfer',
  jsonData: '{"from":"prospectorst","memo":"migration from wax/qepcpara1234","quantity":"0.6170 PGL","to":"lisrx13t21po"}',
  timestamp: Timestamp { seconds: 1670679060n, nanos: 0 }
}
```