# Repolex Knowledge Graph of testing-library/dom-testing-library

RDF knowledge graph data for [testing-library/dom-testing-library](https://github.com/testing-library/dom-testing-library), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download testing-library/dom-testing-library
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 225a3e4cfaa8f8046989d51b9051df507354b644
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 225a3e4cfaa8f8046989d51b9051df507354b644.nq.gz
│   └── repolex
│       └── 225a3e4cfaa8f8046989d51b9051df507354b644
│           └── chunk-001.nq.gz
├── blob
│   ├── 0168ba889828e5e6781c4826529fb05783e24ca3.nq.gz
│   ├── 05d096f7576c926f584ae42c355bb7ff88685d8b.nq.gz
│   ├── 086767595365922313bacc7d4ba598eac5008783.nq.gz
│   ├── 0c2c51e957a7a50c97a8fdc59c4b559adfbd72c0.nq.gz
│   ├── 155939d93af18e6f94093e04904c4157ec3dc88e.nq.gz
│   ├── 1a6afba85f5336973e24844f06a31f19136724c8.nq.gz
│   ├── 1df2a6d8579b70495787fe6685f698941e2acb49.nq.gz
│   ├── 2011260acf6436e88aecb2197debae83aac4d3b9.nq.gz
│   ├── 21729a58dfe49e2f08e737325fba93fb01d87321.nq.gz
│   ├── 29aa4797db4f440096ec0b192f3d2b00ef48a775.nq.gz
│   ├── 2a6752990103f99ba7cbc2653dad53eccf0fd6a3.nq.gz
│   ├── 2b5bcb9a9bf85e117a7e69dc1ec76785c590467b.nq.gz
│   ├── 2b6ae6b447b3bd9336a64edd61c559a0d8f4d217.nq.gz
│   ├── 2b8ea3f1f2e26f4d47229415ce2016cd37e13b98.nq.gz
│   ├── 315b2549bd2064c884df79b538f12dd22c2820ab.nq.gz
│   ├── 33d13de8a6ec4465bac442dcf9030c6e5430e66e.nq.gz
│   ├── 33eaba6b02821e958c3b004d15c6f038c50ce9e9.nq.gz
│   ├── 38f5b3ddea05dcea5944fe13d46e4bce5e787eb6.nq.gz
│   ├── 39bbe1079c36a9f00152a6f9fe4aab0d468fe37b.nq.gz
│   ├── 3f01b6291142c8f6a90ad9a8ef73d8157ee01bac.nq.gz
│   ├── 3f36bc935c4d673cc076b90f278428d0fdc6c2c7.nq.gz
│   ├── 4069bb414989a31ec7e2cbf5127a38a0302d7937.nq.gz
│   ├── 41594ce7af1c528b35b0afc7894a1af9a90bdc43.nq.gz
│   ├── 42356436b56c40a31cc7afe6563d4a5e93b5d726.nq.gz
│   ├── 42559954d7736d35af8c38118e4a6095f79c5293.nq.gz
│   ├── 42bc84aee0c1bcea67126baebc8d666627aeaea3.nq.gz
│   ├── 44328e69914aecb1c163422afee9c3581f625b6d.nq.gz
│   ├── 44a52fb48d0dbc2d1a60c953b05b8ef0978699e2.nq.gz
│   ├── 44a8c96b8ede2a71c4ed849655c2c5d150b2787e.nq.gz
│   ├── 4679d9bf6be92cd766e6d59d40d7da8bdf42335f.nq.gz
│   ├── 47681ae0d4f1ba33314a7fb920584919041129bf.nq.gz
│   ├── 4787d031de2d13cd22d2121e45a11053c9981988.nq.gz
│   ├── 47b4d8965bf408f431e32ef609277aaeb3d0cd40.nq.gz
│   ├── 48d79a8b896c9f1bdb5f9dd083245b4c1f9f4532.nq.gz
│   ├── 4b6732e8694e0320b04085b020e01fd12c5196b7.nq.gz
│   ├── 4bc12816cf989f4001b6dc3919b6d60e673a285d.nq.gz
│   ├── 4c43675bc4da5d353732ebb199ebaaf5eeeef014.nq.gz
│   ├── 4e1a3fed81b92ec002011934560ad57f4ee412f0.nq.gz
│   ├── 4e1a4fb2f4536bbaf92d8a4e991521da70e1c43a.nq.gz
│   ├── 4f6b2047d0d9702041381fec5db84809de624094.nq.gz
│   ├── 4fd2448fdb41ef028b9b97ce58727482dc69c82c.nq.gz
│   ├── 563f29abe4832b7877b6d93412f73069415ba592.nq.gz
│   ├── 56b283fa549d3a1faf4cf0755de8852264fe7ea9.nq.gz
│   ├── 59a1123b8c762a52141db16b48fb9f203aa71d76.nq.gz
│   ├── 5e45c45dba483c9d907b4e6e7dc7cba401f93710.nq.gz
│   ├── 629c283b928e198a3645f8d4b5a1b2c29e8c3189.nq.gz
│   ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
│   ├── 63e1c3ce7ec17c9fd2e04cb9bf9830d2f71382b9.nq.gz
│   ├── 64761025de2cb81d92e7f562043808eb1dfd1bcc.nq.gz
│   ├── 6796a87427f500e79128983a19cff3f5cf1fdce4.nq.gz
│   ├── 6aca2443f2e63c9767170f728160e96f6cab717b.nq.gz
│   ├── 6b413b3bb09ef95f81ea44619dbcb424577085fa.nq.gz
│   ├── 6c663360e66f13ae15f4efef85484811c49bf7d2.nq.gz
│   ├── 6cf7ca5f1fdb93304325cc4a9760454e75ae2940.nq.gz
│   ├── 6dba2399474aa1647f706023e930981b780ff966.nq.gz
│   ├── 6fab4ee4e6057ad8b467fb76598fb5d1ad2377ed.nq.gz
│   ├── 7177a84a2a43c5a9c40a73de66702481e0ac4df1.nq.gz
│   ├── 72faa5f47075905f11a0bf220f01526360d2ab6e.nq.gz
│   ├── 7366855ff24465456123e035066cbcbe2b9f495d.nq.gz
│   ├── 743c4e3bc524d68415941f72f2099022a9499b09.nq.gz
│   ├── 75bbed7fa78f46bbb2c7d89322d74e83e63ec013.nq.gz
│   ├── 77d30d6a98b20e0cea839be943e7dd28d0899f71.nq.gz
│   ├── 7984d5e03f8699627e6b27d19345af0aba008c7d.nq.gz
│   ├── 7a60d8d1ee33a165ea611ff9256a45044c2e1b0c.nq.gz
│   ├── 7a7a2b5001acb87225c284fa69434536129f2fa7.nq.gz
│   ├── 7af3d5073270664677c59b9f91bbb33efd37dac8.nq.gz
│   ├── 7b9904b1959800bad328c7e1d5505019e684d9d0.nq.gz
│   ├── 7e53ab033a40b265be855fa713ead2b0422503a4.nq.gz
│   ├── 816b629b7db2eeaa71e883b1ff5daf7868601897.nq.gz
│   ├── 8469a87d9bad156dba63cd7c3289e9cb7d3ad794.nq.gz
│   ├── 8c4a5552f82dbce817a2711783acebb4d90f1b77.nq.gz
│   ├── 8d7e7cb0fe8b6b98b49b64142fff88d0d524fb16.nq.gz
│   ├── 8e0c70cb093496f582f9e12365e74d2e657ced6a.nq.gz
│   ├── 906ac9bb694ed85cebf7c66785e24dfc385312ff.nq.gz
│   ├── 9271f36b6488bf117b2dc41efed189b8f01b8e4e.nq.gz
│   ├── 9c628283b98527a803e7edaef15fb592ab4b562f.nq.gz
│   ├── 9df516803758aa2dab89dfb9755a47e3e5f340ad.nq.gz
│   ├── a2f1a47872aec931e6f69163f0a78867dc10a559.nq.gz
│   ├── a8e0001194d9d3013aa618b2d7b552195b933e30.nq.gz
│   ├── aacd51e74f47025546fec591de2f87f5d4a94ee6.nq.gz
│   ├── ab1941695690e41923b1227ec10326e87fd01ba1.nq.gz
│   ├── ab5c7106645b8e305e696801000cd84f26c4ee1a.nq.gz
│   ├── b3c83a00f65b4506dc9c4eed73d50a103a2714f4.nq.gz
│   ├── b524c189b2181c16902e56d9094945373ff75139.nq.gz
│   ├── b5dcfbc2833c28c9d796074ca2bb7429f652467f.nq.gz
│   ├── b964f305ce7961304d49db829104bce32f8ec4c3.nq.gz
│   ├── c2f1b02e723b49042b85a10832192281c68c2c4f.nq.gz
│   ├── c3617ef087f1fadf67f964e3afb9754f50b058cf.nq.gz
│   ├── c49c7cca7dded0307c27fd0b13f3a49bed1f5391.nq.gz
│   ├── c4ce9c436258d9472ecf75e79ad87fd516f1d16d.nq.gz
│   ├── c66df417c4c50ea6541a9e3aeef8d7cdec8cb366.nq.gz
│   ├── c6ce905465972c8decfe7ba98257bf8ecb866b67.nq.gz
│   ├── cc81578b94b8b9b65863e70a483c495b035a9013.nq.gz
│   ├── ccec24b48d8423c70c8efbea4842e28a6deee954.nq.gz
│   ├── cf59858309d21ee3b6bd25a2b18248268e185cda.nq.gz
│   ├── d67874d913fc85e4ccd27f933827f13add560844.nq.gz
│   ├── d6a52e62dd4bda27bee7bbbb0f3b62748d0aeeaa.nq.gz
│   ├── d8b426665c604b8106c4c7fabec8d9f5153a513d.nq.gz
│   ├── dca681e274af627b505a725ac677916e5769afb4.nq.gz
│   ├── e0098c0879918560835fb885db1a1f56be84e791.nq.gz
│   ├── e1e77e6759259aaa83a53181c8acd2ebeb361577.nq.gz
│   ├── e332dfdb9dacdcc9753b248f2d9036c8a515bc51.nq.gz
│   ├── e36a0456500a5fc2a425dbe9b9f3479c2c46c318.nq.gz
│   ├── e387de9a6557ce2cde754e496eae1a7e91853a51.nq.gz
│   ├── e4dd395ff15cf5a1ee076f1beafa33af5870f201.nq.gz
│   ├── e570aac7c7dd0e0f2707f71c9767f94f43936c58.nq.gz
│   ├── f47daa42afb73a14974c720b9c3d72cd7b8b6bc8.nq.gz
│   ├── f5a193357f100ce6d6c97ba4f4c532e8e86fffc7.nq.gz
│   ├── f96c0da141e8c4219668b88e7ff35bc6a7ffc6cf.nq.gz
│   └── fe14c13a293f91a90ca70bddae74a3fa6180c08e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 225a3e4cfaa8f8046989d51b9051df507354b644.nq.gz
├── filetree
│   └── 225a3e4cfaa8f8046989d51b9051df507354b644.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 120 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[testing-library/dom-testing-library](https://github.com/testing-library/dom-testing-library)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
