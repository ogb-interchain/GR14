# GR14 OGBInterchain 👽
Let's create a public good research dataset to introspect about the world we are helping to bring about!

**_Note:_** this grant and adjacent ideas started as a hack @ GraphHack 2022 in beautiful San Francisco; several of our teammates have won prizes for their work in indexing CosmWasm smart contracts, Cosmos Hub / Osmosis / Junø chains. The repos involved in the original and individual hack(s) have been forked for extension as a part of this grant: https://github.com/ogb-interchain

Importantly, this is a very narrowly scoped project - and once the dataset is submitted and accepted into OGB-LSC, this group will consider our mission complete and similar to ConstitutionDAO, disband after voting on the final allocation of the funds (currently, the idea is to sponsor a scholarship for travel + accommodation for qualified graph ML researchers who want to specifically improve performance of their methods on our dataset).

As a project creating what is effectively a **public good** (a canonical research dataset outside of the confines of academia, but close to its value set), we will not seek to profit from this endeavor and will commit to full on-chain transparency of fund allocation and compensation of labor at market rate after a fair opportunity open to the qualified contributors regardless of their race, ethnicity, or national origin (think about this as a self-regulating equivalent of posting a newspaper ad in the labor / immigration rules for fair opportunity in some jurisdictions, except we'll actually make an effort this reaches _every_ emerging web3 labor marketplace)

The submission is for a (4/5) **Gnosis Safe Ethereum** multisig instantiated as of https://etherscan.io/tx/0xe8b4cb456d435893cfa158ee38e07e20c4119d4f83faba3539f967b34627e4c4

Any labor compensation or allotments related to the operations of OGB Interchain are to be determined at the going market rate for the relevant skillset and postings will be submitted to ReSource Mutual Credit marketplace, https://clarity.so and any marketplaces that established groups like developerDAO and LexDAO suggest for us. One-off expenses will be itemized, expounded on, subject to governance, and aimed at the market rate for DAO contributors of the same skillset, using the formula agreed upon ahead of time by core signers, and as some of the markets will be established by us for the first time, additionally open to permissionless Twitter Spaces townhall style feedback gathering session.

TL;DR let's build a public good research dataset for graph ML students, postdocs, industry professionals, bored gentlepeople, and others (whoever you are, dear 1/1 👽) to cut their teeth on and effortlessly try their architectures on within a context of a well-estbablished (now in 2nd year) benchmark recognized by the credentialed academic community and run this as a challenge with diverse participants, to be incentivized from whatever remains after our final mission of delivering this reference dataset is accomplished.

**Summary**
This grant is for a group of graph ML engineers, researchers, and product designers to gather a representative dataset of transaction data from several chains and ecosystems over a period of time, submit it using the official Open Graph Benchmark Dataset process in time for the third Open Graph Benchmark Large Scale challenge (currently in its 2nd iteration): 

https://ogb.stanford.edu/neurips2022/
(https://oxu4g46q3shfjkyunbg3b7piznojzzu4f7jgrolgvswjr7pu.arweave.net/denDc9DcjlSrFG__h-NsP3oy1yc5pwv0mi5ZqysmP30)


**Why is this important?**
The aspiration of our movement is nothing short of finding systems of coordination that converge on better equilibria for global finance, global governance, and global fun, systems that are better than what we have today.

In order to achieve the fullest extent of this vision, we need to allow for the a degree of dynamism, reliability, and trust and safety features that the next billion to join have to come to expect from SWIFT, ACH, Forex, their voting machine and so on, and so on...

Given the current state of progress in machine learning research, and emerging practices around web3+ interoperability interfaces in the face of complex sanctioning regimes and increasingly multichain / "endgame" environment, to the extent any machine learning approaches can be useful, they 

-   you have a lot of compute and a lot of data to build so-called Foundation Models
-   you want to understand the Geometry of your Data, frequently through graphs
-  generations of researchers have cut their teeth on your data and it's available to the them without 

Unlike vision and natural language tasks, graphs present [a significantly more challenging](https://www.youtube.com/watch?v=WsgIcq-Q4LQ) optimization and learning task, and the field has only recently settled on a set of promising approaches (message-passing, smth smth topology, neighborhood embedding et alia) that allow for graph-level, node-level, and edge-level understanding of the networks they represent.

Pressingly, as a nontrivial portion of the public are seeking refuge in these radically transformative technologies (remains to be determined), amidst a growing set of crises, we need all the best tools to understand the nature of our broader dystopia, and cannot just entrust it to a yet-another for-profit entity, cryptofund, or a clever financialized instrument backed by wishful thinking ponzinomics. If anything of value to others, end-users as well as those securing them and building for them, especially if monetary value is involved, in our view it needs to be a pluralistic public good - if it can be abused, when it gets valuable enough to do so, it _will_ be abused.

As of writing and to our knowledge, no such benchmark dataset for the multi- / interchain graph of blockchain transactions, is being contemplated as a public good contribution, or even allows for its own future existence by having a properly welcoming on-ramp for those doing graph ML research outside the goblin town. We seek, above all, to contribute to value pluralism and diversity of perspectives, and trust in emergent serendipity of these chance encounters to provide something.  Let's take this one-time snapshot of our transaction data out of the proprietary labs of Binance, Coinbase, a16z / Paradigm etc. and turn it into a public good that is convenient for researchers to try their novel graph tasks with in perpetuity.

**How, devs?**
At the conclusion of this grant's fulfillment is **a very simple finite deliverable - a benchmark dataset** of full node firehose transactions (if we reach a funding goal that exceeds our computational costs), or transactions of most widely instantiated and used contracts, at an equal contribution for each ecosystem listed, and transactions fixed number of degrees away from all the wallets involved in these limited contract interactions; this blockchain data will be recorded between governance-legitimized START_TIME and END_TIME, and after raw data acquisition, will be transformed to normalized datastructure of transactions as a composable set of chain-graphs. An initial set of graph tasks and baseline performance will be suggested and recorded and submitted as an academic work / preprint. All raw, intermediate, and finished stages of this process will be shared.

Concretely, at the conclusion, we will seek to submit this new research dataset to Stanford SNAP group focused on blockchain use-cases using the official process outlined for the OGB-LSC competition here:
https://ogb.stanford.edu/docs/dataset_overview/
(https://doejlxvasuuvnlrakdsvymjrj4mfkxfi6f2wksxrbjrjgvbtoe.arweave.net/G4iV3qCVKVauIFDlXDExTx-hVXKjxdWVK8Qpik1Qzcc)

To the extent we can, we will pick up the datapoints from existing indexing effort with sufficient degree of transparency, but, funds allowing, seek to verify this data.

The team  will additionally participate in the second iteration of the challenge at NeurIPS 2022 as a separate effort, and advocate for inclusion of the blockchain dataset into future iterations of OGB-LSC - as luck would have it, the third installment.

For indexing the transaction data, we will use a combination of **Graph Protocol subgraphs**, **SubQuery**, and **original full-node indexing approaches** to gather a firehose dataset from mainnets on:

-   Ethereum + largest testnets (think you have fresh PoS MEV?! let the graph guide you 🐀)
-   EVM L2s (Optimism, Polygon, Celo, Gnosis Chain etc.)
-   Tendermint / IBC chains in the Cosmos Interchain ecosystem (Osmosis, Junø, Regen Network, Cosmos Hub etc.)
-   NEAR
-   Solana
-   Cardano
-   Bitcoin

Additionally, we will include several testnets that in our opinion will be at the core of pluralistic rough consensus technologies in web3 _and beyond_ 👽 As of writing, this list includes (as of submission):

- Penumbra
-  Celestia
-  Nomic (IBC)
-  Namada
-  Radix

Given the size of the dataset, we will index the chains and interchain interaction only for a period of time and additionally advertise the indexing event in the ecosystem -- those participating who tweet #OGBInterchain will get a POAP for participating in the indexing event knowingly (i.e. showing off on-chain) and will additionally form the initial high-signal network for inclusion in any incentivized focus group research on graphs for distributed ledger technologies.

If we fail to reach the funding goal sufficient to gather the dataset for a sufficiently large window of time (minimum 48 hours) fully, we will instead focus on the most widely used instances of contracts and simple wallets for the largest chains and still index / release / submit as much as we are able at that point before the conclusion of OGB LSC v2 by test-challenge submission deadline for existing datasets, which we will also attempt separately from this effort (November 1st, 2022 https://ogb.stanford.edu/neurips2022/timeline/). 

For historic reasons and in terms of whole-perspective indexing of this multichain graph dataset for future benchmark tasks, we will have it as our reach goal to time the data acquisition:

-  with Ethereum Merge event
-  carry out simultaneous indexing for all indexing targets to be able to run cross-chain correlation, i.e. to test the strength of mixers / new shielded asset targets we identify that rely on several chains.

On the data engineering side, we will use the DataSaver format suggested by the official OGB repository: https://github.com/snap-stanford/ogb/tree/master/ogb/io when submitting, together with this document and any additional justification of the importance of this data being exposed to researcher community that results.

Raw data, any data processing steps, and the resulting artifacts will be open-sourced in a way that is reproducible by any member of the community. Our reasoning in processing will be recorded using the Data Sheet format https://arxiv.org/abs/1803.09010

  We will suggest several tasks that are appropriate for various views of this data, and baseline models to accompany them. The models will additionally include a Model Card, and the architecture, weights, hyperparameters likewise recorded https://arxiv.org/abs/1810.03993

The processed dataset will be added to the Permaweb using Arweave / ArDrive so that all researchers can benefit from the data processing we perform prior to submission. https://www.arweave.org/yellow-paper.pdf

**What will the funds be used for?**
- compute costs to be exclusively allocated to `$AKT` for DIY compute in indexing, graph data processing, storage, and GPU compute
-  costs of incentivized permanent storage of the dataset, baseline models, as well as metadata of their provenance `$AR`
-  `$GRT` for use of subgraphs that already exist
-  community tokens sufficient for participation in the chains being indexed at a level of the full node, with additional data availability expenses as native tokens (e.g. `$OP`)
-  compute costs for execution of GitHub Actions (via a `$USDC` payments method)
-  license cost for specialized compute (access to be given based on a GitHub commit of code that 4/5 governance multisig finds gmi)
    -  Dune Analytics `$390 * gmi user * month + tax`
    -  Google Colaboratory pricing for interactive experimentation by data scientists / engineers `$49.99 + tax`
-   development labor costs for additional indexing improvements and data processing
-   data scientist labor baseline models
-   other expenses discovered in the execution, transparently itemized for governance, and open to public town hall feedback on a Twitter Space if not included in the above list as stated

We will seek to ensure our best understanding and counsel on fair labor practices and equal ability to contribute to this effort that is based on meritorious competition open to the many, or as close as we can get to it, so the membership and selection process for the labor to carry out any tasks open to more than just the core and announced to all members of the broader ecosystems as postings on the emerging marketplaces (i.e. ReSource (Celo) mutual credit, clarity.so, others you suggest), open new categories of tasks if they don't exist yet if requiring reasonable effort and documented how, and any decentralized labor market places in active use as suggested by the broader community of DAOs who have thought deeply about this aspect.

**Team SSIs and other socials**
[Gnosis Safe](https://docs.gnosis-safe.io/introduction/security/security-audits): `0xa814e9a53803E424DFa115c956101d950C74417a`

-   Barton Rhodes ([@bmorphism.lens]($AR` for storage of the processed artifact)) - securityDAO founding member, DAO DAO contributor, DEFCON AIV resident degen; prev. graph MLOps @ Lacework, Airflow Helm / Kubeflow Anthos ML platform development, Google Cloud Partner startup co-founder Optfit, [sciencing security data](https://arxiv.org/abs/1811.08705) and (formally abandoned, fondly remembered) academic pursuit of mathematics
    -   `bmorphism.eth`
• Gavin Doughtie - Principle Engineer @ Google, Rust SF Meetup founder and organizer, DAO DAO contributor, UIUX, winner of GraphHack 2022 challenge category
    `0x5b7126A90e93C0Af0b45dd5F68a34CF9C8FcCb13
-   James Ortega (@entrancedjames) - Distributed Systems Engineer @ Twitter, DAO DAO contributor, winner of GraphHack 2022 challenge category
    -   `0x41C8dEA30C6f5eFdCDD3eF842b0c9ffB8E46089a`
-   Nikita Trifan (@nikitatrifan) - WasmSwap UI contributor, prev. UIUX front-end engineer @ Adobe
    -   `0x39D2f20c0EF14FD4e65a1aDA9b65C0B39443B1aF`
-   Patrycja Zawadka (@patiee) - open-source contributor to Graph Protocol, developed Cosmos chain integration into the Graph while at Figment
    -   `0x46ea86aaec5178a2C047BE00abe85E45650e1357

Any additions to the team, treasury allocation, or any governance of import will be additionally socialized through @OGBInterchain Twitter account holding a Twitter Space, with soft consensus subject to polls, Commonwealth, and ultimately an on-chain footprint.
