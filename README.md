# Repolex Knowledge Graph of ansible-collections/community.kubevirt

RDF knowledge graph data for [ansible-collections/community.kubevirt](https://github.com/ansible-collections/community.kubevirt), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download ansible-collections/community.kubevirt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f36232c303b519a73f5d29b616a39af855d772a5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f36232c303b519a73f5d29b616a39af855d772a5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0972cd2e8e58d51f20c6b0d23d8f89154c7ac076.nq.gz
│   ├── 13694b4ebd2263d09b09589888e873453d582d64.nq.gz
│   ├── 182b1430a5b1059ee252be07f68a33e95e840b42.nq.gz
│   ├── 1a1f0df5442994d01c701e86d3cdb9dac529703b.nq.gz
│   ├── 1e86dbda2842d4a45a6fbb2103567d83f94b4b14.nq.gz
│   ├── 2104e210a9cbfba5f18fcc22a6e42b26c321129f.nq.gz
│   ├── 23e302a5e72351059b7121227543585f2148db5e.nq.gz
│   ├── 280cf578f655702a6f20d924d146b69129cbeb2e.nq.gz
│   ├── 376889e7d19b0b3789fbe8a91285f31ddb50fd2d.nq.gz
│   ├── 4fcb1b30712bf2052e5dca938f27111e08884c04.nq.gz
│   ├── 5526dc12da0397ec5609cae7d8f7213e7898ab8e.nq.gz
│   ├── 5cec7d4e8bb105872d05eee6408316679036a5eb.nq.gz
│   ├── 61432a7dc6d3b71f1cfb2a51ac22fd5e70784ed4.nq.gz
│   ├── 62e53c078f55d7db67031ce65f9f4b1b6ae721c3.nq.gz
│   ├── 645c70ca3fdc71278c5195db1e71dd9ffd5db182.nq.gz
│   ├── 6541cf7cf0727c4d67993100c4d2224c736da0a6.nq.gz
│   ├── 740c8115458b12e3a8f24220e718e0b33ef2e16d.nq.gz
│   ├── 765b70da7963c6da8b061924e900cd5271e3a44f.nq.gz
│   ├── 88276760562cb58bb9bc47fa890e8a3df1125b9b.nq.gz
│   ├── 89d17a9963508d49d2903ab1f860fb2a9ac2f188.nq.gz
│   ├── 932aade09ad56475c71f082506f5eaee49e61739.nq.gz
│   ├── 975876e7826854ff05f72c5c68f9238213348097.nq.gz
│   ├── 98f08ad6a8474fbcc3e338436bae46663d4aa4ae.nq.gz
│   ├── 9dccf7ef174657345b77b37626c52cdc0390117f.nq.gz
│   ├── 9fad0d343c07aa82e21752481014bb870092c693.nq.gz
│   ├── a340d28d62ac7f2b580e33cabf4cae8fc6ba8fda.nq.gz
│   ├── a80c0811fbe519bb5ae7d839e985ff2824e727bb.nq.gz
│   ├── a82dd6fd0bce1c1742b2d5523fe06b8a51a84c8c.nq.gz
│   ├── aafdc9d3c01f78b0c95569129b4b352bf2bb4d26.nq.gz
│   ├── ab6063c03edc216d0802883c0357b70576cf69fb.nq.gz
│   ├── b05439d10b763f6935241480bd5a58cb2ea72fb6.nq.gz
│   ├── b2d06468323738c06c6255b9a3a2d6cd38bee844.nq.gz
│   ├── b9425ee917f56614066ccfc1ca74fe7ab4d2cf25.nq.gz
│   ├── c44f44e9dee5d66dd4d840a7cfe54afe07784bb5.nq.gz
│   ├── d62fbf6a59faba377bffe14b9f4fe4142a619134.nq.gz
│   ├── d9c8ffc6a2fe01658c2c8d1431801302f84a6e52.nq.gz
│   ├── db8af8b68198cd4e97c643f8b83d8edf7b19fffa.nq.gz
│   ├── df5a7661f7742569f7918950b71322552b212c26.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea163ab17670152eebddbaa662287b90d144b95e.nq.gz
│   ├── ed25b72415b00711c66f4fda708939a68b42708d.nq.gz
│   ├── edcfe55bca05a7b6823d76cdbdd470669b0804e4.nq.gz
│   ├── ee478b8dc5653da6c30f4878a6fb79bd104c60f2.nq.gz
│   ├── f13b9f9a01fbd5882314ece2b94fe7113550899d.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   └── f357e2949c4a74494f5858c146fe6f7081a91149.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f36232c303b519a73f5d29b616a39af855d772a5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[ansible-collections/community.kubevirt](https://github.com/ansible-collections/community.kubevirt)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
