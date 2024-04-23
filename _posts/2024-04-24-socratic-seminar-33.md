---
layout: post
type: socratic
title: "Socratic Seminar #33"
meetup: https://www.meetup.com/bitdevsldn/events/300447303
---

## Announcements

Please join us for our next Socratic Seminar. This Socratic Seminar is sponsored by [Ben Delo](https://twitter.com/bendelo).
Please speak to the hosts if you're interested in supporting London BitDevs.

## General Links

* [Bitcoin Optech](https://bitcoinops.org)
* [Bitcoin Core PR Review Club](https://bitcoincore.reviews)
* [bitcoin-dev Mailing List](https://lists.linuxfoundation.org/pipermail/bitcoin-dev)
* [lightning-dev Mailing List](https://lists.linuxfoundation.org/pipermail/lightning-dev)

## Delving Bitcoin, Mailing Lists, Meetings and Bitcoin Optech
### [Delving Bitcoin](https://delvingbitcoin.org/)
- [Great Consensus Cleanup Revival](https://delvingbitcoin.org/t/great-consensus-cleanup-revival/710)
- [BIP324 Proxy: easy integration of v2 transport protocol for light clients (PoC)](https://delvingbitcoin.org/t/bip324-proxy-easy-integration-of-v2-transport-protocol-for-light-clients-poc/678)
- [Mempool Based Fee Estimation on Bitcoin Core](https://delvingbitcoin.org/t/mempool-based-fee-estimation-on-bitcoin-core/703)
- [BTC Lisp as an alternative to Script](https://delvingbitcoin.org/t/btc-lisp-as-an-alternative-to-script/682)
- [DSL for experimenting with contracts](https://delvingbitcoin.org/t/dsl-for-experimenting-with-contracts/748)
- [Second Look at Weak Blocks](https://delvingbitcoin.org/t/second-look-at-weak-blocks/805)
- [Basic vault prototype using OP\_CAT](https://delvingbitcoin.org/t/basic-vault-prototype-using-op-cat/576)

### Mailing Lists
#### [bitcoindev](https://groups.google.com/g/bitcoindev)
- [The Future of Bitcoin Testnet](https://groups.google.com/g/bitcoindev/c/9bL00vRj7OU/m/9yCPo3uUBwAJ)
- [Great Consensus Cleanup Revival](https://groups.google.com/g/bitcoindev/c/CAfm7D5ppjo/m/bYJ3BiOuAAAJ)
- [Adding New BIP Editors](https://groups.google.com/g/bitcoindev/c/cuMZ77KEQAA/m/cA2P2UalAgAJ)

### Meetings
- [Bitcoin PR Review Club](https://bitcoincore.reviews)
  - [#29221 Implement 64 bit arithmetic op codes in the Script interpreter](https://bitcoincore.reviews/29221)
  - [Testing Bitcoin Core 27.0 Release Candidates](https://bitcoincore.reviews/v27-rc-testing)

### Optech
- [Newsletter #293](https://bitcoinops.org/en/newsletters/2024/03/13/), [audio recap](https://bitcoinops.org/en/podcast/2024/03/14/)
- [Newsletter #294](https://bitcoinops.org/en/newsletters/2024/03/20/), [audio recap](https://bitcoinops.org/en/podcast/2024/03/21/)
- [Newsletter #295](https://bitcoinops.org/en/newsletters/2024/03/27/), [audio recap](https://bitcoinops.org/en/podcast/2024/03/28/)
- [Newsletter #296](https://bitcoinops.org/en/newsletters/2024/04/03/), [audio recap](https://bitcoinops.org/en/podcast/2024/04/04/)
- [Newsletter #297](https://bitcoinops.org/en/newsletters/2024/04/10/), [audio recap](https://bitcoinops.org/en/podcast/2024/04/11/)
- [Newsletter #298](https://bitcoinops.org/en/newsletters/2024/04/17/), [audio recap](https://bitcoinops.org/en/podcast/2024/04/18/)

## CVEs and Research
### Research
- [BitVM 2: Permissionless Verification on Bitcoin](https://bitvm.org/bitvm2)
- [Hedgehog: A protocol for asynchronous layer two bitcoin payments](https://stacker.news/items/481321)

### InfoSec
- [Libbitcoin response to CVE-2023-39910 / Milk Sad](https://github.com/libbitcoin/libbitcoin-explorer/wiki/CVE-2023-39910)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
<!--- Link to query merged PRs since YYYY-MM-DD sorted by descending activity: https://github.com/bitcoin/bitcoin/pulls?page=1&q=is%3Apr+is%3Aclosed+merged%3A%3EYYYY-MM-DD+sort%3Acomments-desc -->
- [Mempool util: Add RBF diagram checks for single chunks against clusters of size 2](https://github.com/bitcoin/bitcoin/pull/29242)
- [p2p: Allow whitelisting manual connections](https://github.com/bitcoin/bitcoin/pull/27114)
- [net: support unix domain sockets for -proxy and -onion](https://github.com/bitcoin/bitcoin/pull/27375)
- [RPC: Add maxfeerate and maxburnamount args to submitpackage](https://github.com/bitcoin/bitcoin/pull/28950)
- [wallet: Add createwalletdescriptor and gethdkeys RPCs for adding new automatically generated descriptors](https://github.com/bitcoin/bitcoin/pull/29130)


### [LND](https://github.com/lightningnetwork/lnd)

- [2/3: Support Forwarding of Blinded Payments](https://github.com/lightningnetwork/lnd/pull/8160)


## New Releases
- [Bitcoin Core 27.0 released](https://groups.google.com/g/bitcoindev/c/bU46ykb2uig/m/JiPyoV70AQAJ)
- [Bitcoin Core 26.1 released](https://groups.google.com/g/bitcoindev/c/3UESYfaGPlM/m/rmTzmSukAAAJ)
- [phoenixd v0.1.0](https://phoenix.acinq.co/server)
- [phoenixd-lnurl v0.1.0](https://github.com/AngusP/phoenixd-lnurl)

## Mining

- [0xB10C: ViaBTC's mutated blocks without witness data](https://b10c.me/observations/10-viabtc-blocks-without-witness-data/)
- [0xB10C: halving stream](https://www.youtube.com/live/C6D9OEjnWmA?si=rKc8n0X__7M6Yx_E&t=13189)
- [0xB10C: mining pools sharing block templates and transaction prioritization](https://x.com/0xB10C/status/1780611768081121700)
- [Mara pool funny block](https://mempool.space/block/0000000000000000000341cc26cda4af82cd25f7063c448772228cbf2836915b?audit=false)
- [Stratum Reference Implementation 1.0.0](https://stratumprotocol.org/blog/sri-1-0-0/)
- [BlueMatt: Stop Calling It MEV](https://bluematt.bitcoin.ninja/2024/04/16/stop-calling-it-mev/)
- [Braiins Becomes First Mining Pool To Introduce Lightning Payouts](https://bitcoinmagazine.com/business/braiins-becomes-first-mining-pool-to-introduce-lightning-payouts)
- [Ocean leaving 37 BTC in fees on the table](https://x.com/achow101/status/1781477641280684382)

## Privacy
- [Teleport Transactions](https://x.com/RajarshiMaitra/status/1768623097819873571)

## Miscellaneous
- [CVE-2024-3094: Timeline of the xz open source attack](https://research.swtch.com/xz-timeline)
    - [Everything I Know About the XZ Backdoor](https://boehs.org/node/everything-i-know-about-the-xz-backdoor)
    - [OSS-security post](https://www.openwall.com/lists/oss-security/2024/03/29/4)
    - [FAQ on the xz-utils backdoor](https://gist.github.com/thesamesam/223949d5a074ebc3dce9ee78baad9e27)
    - [Infographic](https://infosec.exchange/@fr0gger/112189232773640259)
- [Craig Wright Is Not Bitcoin Creator Satoshi Nakamoto, Judge Declares](https://www.wired.com/story/craig-wright-not-satoshi-nakamoto-bitcoin-creator-ruling/)
- [Transaction ordering could be used to store information](https://twitter.com/salvatoshi/status/1772619501370036477)
- [Safety Net](https://wizardsardine.com/blog/safetynet/)
- [ajtowns: Team Slow and Steady](https://www.erisian.com.au/wordpress/2024/04/20/team-slow-and-steady)
