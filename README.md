# Repolex Knowledge Graph of canonical/zookeeper-k8s-operator

RDF knowledge graph data for [canonical/zookeeper-k8s-operator](https://github.com/canonical/zookeeper-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/zookeeper-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b26927942784d419557cbf0fead13a85fd2768b6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b26927942784d419557cbf0fead13a85fd2768b6
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c54dcbeb3865ee2e7d191a9fb91c0aa689cb55.nq.gz
│   ├── 01d9c85504c4b23494d38dae196ecb869dc42bc9.nq.gz
│   ├── 0277e50e0f243ce4c0777a96d2e2247fcdbcc9cd.nq.gz
│   ├── 042361e396e255c3c80eeeccbb1e8044a2cc7bab.nq.gz
│   ├── 043b06c17089b82350362e2cd38b070222769b8a.nq.gz
│   ├── 0634150429f9517e79105bc83bf38d01b9e451ea.nq.gz
│   ├── 07147d636129b3048545ff09371cf03e718cebca.nq.gz
│   ├── 084890c8b95347511b8d52a8156b7b063606ae4c.nq.gz
│   ├── 096918629019ad243714dfecf2af3fcc483d7600.nq.gz
│   ├── 0a6449794b5d2e4038107d795d353726450c5c06.nq.gz
│   ├── 0b88d3f4ba0d07ac28d2e0738cf94790da07952c.nq.gz
│   ├── 0d2d1d100c8dc49c232cc59fb26cf713f763a330.nq.gz
│   ├── 13adde58b3692a06b14db329b22e238dd5e20d49.nq.gz
│   ├── 1427abf83aa1e16882656a071ebd228d43394851.nq.gz
│   ├── 1491ff4b90f3a08868725c065a97b5915d9dec51.nq.gz
│   ├── 149c6171d72f8659aec6bb8da9080acd6d30492b.nq.gz
│   ├── 18fc1bb64948e1f0e49015d4fbe02e1048c91567.nq.gz
│   ├── 23d7c9aed10e0a7188322e7d62b0cf93b2fbbcb5.nq.gz
│   ├── 2580c9ef4c6e7bba3a97c91f6c7a3c6e90e18abd.nq.gz
│   ├── 26af2183d1845550f715e35b1cfd3999a3bf88dc.nq.gz
│   ├── 2831c8720da9a7ebb4a1f2957e42c6fab19e1329.nq.gz
│   ├── 2900c4b7fcd0ad07d0bf3e63f1335fb24a30d070.nq.gz
│   ├── 29dfdef7df16544157b841d70afa06795dfe8087.nq.gz
│   ├── 2b66a0529db184ca57e42d974c33cb19ca5a7394.nq.gz
│   ├── 2be56995e51ddd4d87812e1214f426e35be33da5.nq.gz
│   ├── 3058adb222821c95fb39a04c3d3d08a97d52d1e1.nq.gz
│   ├── 31a71b3d34492de2cda5e8eb71d126beb3262c07.nq.gz
│   ├── 3312557f980a79bba55d2606632969cdb95c868c.nq.gz
│   ├── 34d66a822a04ad3c18d18bc0883e14bc7e112999.nq.gz
│   ├── 365fa5ebc465c95fff12f84f2f4c4104e5fc196a.nq.gz
│   ├── 38300828cc874afff586f69bc01c32136a7768db.nq.gz
│   ├── 388907898807998da07d0c4a9f3623f86f546319.nq.gz
│   ├── 3b379fea8d5e3af953e9000b0690645bf3b8d0af.nq.gz
│   ├── 3bad24dfbb1882369c725aa51c4e7d7de1fdbc79.nq.gz
│   ├── 3d058478711df6cd060ef4bd9dff68fa11163715.nq.gz
│   ├── 40d2496c8dd104940797e6b149e7c6d83b3368c5.nq.gz
│   ├── 451e45544385a447699bf524f16c3bbce5e1720f.nq.gz
│   ├── 499a268890a64d342893ca344c268ce4be4ddee3.nq.gz
│   ├── 4b0a78e25254216ac4b54cccc2c5ab751d400c96.nq.gz
│   ├── 4d93299d514fd0e8f4280ff8eed0ab5e9ba205c9.nq.gz
│   ├── 4e2b1290dcf8b9318a67dd3d6aa3f4f8f1be72b6.nq.gz
│   ├── 5161e7d1e142e26e19fda83f89ec30516c45215b.nq.gz
│   ├── 554bee1e22bef0445083a531dee0375c6bec0bdb.nq.gz
│   ├── 5638ed2ae55a35296229e27786575822f099629b.nq.gz
│   ├── 5a6f570b8e6fce14b4863de0b4b60318bf24d2e0.nq.gz
│   ├── 5ab2f7e97ab9e45ab3f0a6ea475df0871af3f68d.nq.gz
│   ├── 5e390664e3417ff921cdb6521bf403e0b76cfb58.nq.gz
│   ├── 5f3d1ec6ff4d55cebb26540a6181cce3a66815e9.nq.gz
│   ├── 61cbb070fccabedcc52c8caeb6668060da2f53bd.nq.gz
│   ├── 6248444882427e7211f86d39f26ec2444aa13218.nq.gz
│   ├── 65e7b1e5507877b6ab24cf42840ea51e17d01247.nq.gz
│   ├── 6bf02c2fe9c9c550db29995766157fe75090cf8a.nq.gz
│   ├── 738bedced2fbe40c80fa3460aee7403b696f63a1.nq.gz
│   ├── 73c30a5066d684148962eddb9e148f26ffb3d6e1.nq.gz
│   ├── 751152559b57afc87bb05ed57911f6cc9aa708eb.nq.gz
│   ├── 7513b120b71dd57881273f772ae11b01f8dfbf59.nq.gz
│   ├── 780e4ef2c814296464069e6ea77133492dc74fdb.nq.gz
│   ├── 78b1939b96d01ac535170364ea338d2113dd5733.nq.gz
│   ├── 794137f61a534af30dc16be0e72a171080073af8.nq.gz
│   ├── 81762c909b8b0003aed86346e57fc7826e4c3519.nq.gz
│   ├── 82602878e817f2010eb513a5038bf07ac80ccc41.nq.gz
│   ├── 86e8c3eaba63d4c16f703c1b7625fe13009721a7.nq.gz
│   ├── 8cab71336fee34dfee11cb67dcfc82dd34df6172.nq.gz
│   ├── 8d21f1f1f5a093f5d39956510b473b82f2a60605.nq.gz
│   ├── 9ce8d59eccb2a49c8d171290cc35991c310f5f60.nq.gz
│   ├── 9ee2d0b5f669507a30afdfff5fdee60d486c1fc0.nq.gz
│   ├── 9ee9ae71302c0315f19ae6761c0f4b360890de18.nq.gz
│   ├── 9ff666cdca3f44accdd82dec646694b83fc0a46c.nq.gz
│   ├── a145eaf271a779539e2018a45ffd496c28895e5c.nq.gz
│   ├── a1dbb8299afdaf3fe254eba61ee68f42e2399ec6.nq.gz
│   ├── a2162aa0baca2efe9885e61e43a8cdb4d4c7fbaf.nq.gz
│   ├── a2991a5e82dbb33766e34c81648f58106a0817d8.nq.gz
│   ├── a3e2751d2cba8bb2cce1a5c000a0b182366dd26b.nq.gz
│   ├── a6b7465dddd793d074a7378d8e12a131e6276988.nq.gz
│   ├── a75457cc078e708942e981422e1ea04b880a6489.nq.gz
│   ├── a780288377e6c8e11a7fe017845526a9df6ecc4c.nq.gz
│   ├── a79e5d4343e09bc07819c1a444ef89d509067388.nq.gz
│   ├── aa5b30892910b75598c4135cc467f8e89b4eb8f7.nq.gz
│   ├── ad5513d3bebdfd935cff45acba6e28428fedf8cd.nq.gz
│   ├── aed4677dd1a08df89fe93aa6bd9e0f06e458182d.nq.gz
│   ├── af69d813e9e17953f3536dc361dbd0d6214593a1.nq.gz
│   ├── b2632184ed4c4d0c27133d943871b5ed4d729e98.nq.gz
│   ├── b7859bba0e28c09db48bbf1960c87d96a1132b80.nq.gz
│   ├── b89ffbf8b3bc9bb72e4729fdf449b314c8976abf.nq.gz
│   ├── bbe131546238608cb70f136499ddd7a95eb51198.nq.gz
│   ├── bd1ff1cb4c75ef924d6edd2e38f3d0077d966e1e.nq.gz
│   ├── be5021a1f649b0ace30de68c85fb981ccf378877.nq.gz
│   ├── c20ab2b1597d6c6a9e5ea743b5969fdebcc728bd.nq.gz
│   ├── c31f6a6efd59adcb0467e747c06bcb4f8215d40b.nq.gz
│   ├── c504e3df964fbca9969819c0290c08219d45c300.nq.gz
│   ├── c6101ee5b86e5c7501b5546bc357c7700302183e.nq.gz
│   ├── cac364e342b5aa98294cb7842a1c4993d6b0dd32.nq.gz
│   ├── cb17dbb003f1d0f870493d5df790eee4a2db780f.nq.gz
│   ├── cb1aaf8c189a5c5185a997a24d548d9ad0e19d0a.nq.gz
│   ├── cb25f10006b8d6e89f918c0d35c7a3f9e11f63cf.nq.gz
│   ├── cc01d46a3234817c7cc9b8722470b47cbf5f6e1d.nq.gz
│   ├── cc9f23502d4f79183be76016a599f9ef9e277540.nq.gz
│   ├── ce4d7f0cc1f2260f550decf083dfc9d470cdc476.nq.gz
│   ├── cf069ab2e31e0bc00e91379b7b654734cb6bc72e.nq.gz
│   ├── cf21143e5c6e8cc374c129e89d44a665d5bc642a.nq.gz
│   ├── d0b2d78ad11fe69a0296ba64159f33f2ec4aeddc.nq.gz
│   ├── d3369ee2210ee59bb3eeb4ab79db3be89ac15d71.nq.gz
│   ├── d4d2f2a7bc973d88ad179f1b2304e72739086509.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dafb55b775757bc86b150ca62269c14702673e92.nq.gz
│   ├── db3bfe1a652400bb6963dfc7ede76820781ee928.nq.gz
│   ├── dd252e1d5f2977730ca15e06327c9cad3e17f313.nq.gz
│   ├── e0de019db351743fd9a5848cf6051e58df4b93d9.nq.gz
│   ├── e13cdf0524167865f819f360d50e342be789f8fa.nq.gz
│   ├── e36852b2b45dfd93c48ae80b5bd9e447d86f230c.nq.gz
│   ├── e4beb29a215142ecad24d6fb397f1322835188cd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f50a03021a7b0b18d870be0832d920e144764850.nq.gz
│   ├── f5614aaf6b449c7c45703795fc80e276c60877a1.nq.gz
│   ├── f59918978042828b1c99546b915d8c97210a59a9.nq.gz
│   └── f9ee650010f7a64b1e5e5f0c64abf4d1af2e6a96.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b26927942784d419557cbf0fead13a85fd2768b6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 124 files
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

[canonical/zookeeper-k8s-operator](https://github.com/canonical/zookeeper-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
