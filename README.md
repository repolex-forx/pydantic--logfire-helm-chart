# Repolex Knowledge Graph of pydantic/logfire-helm-chart

RDF knowledge graph data for [pydantic/logfire-helm-chart](https://github.com/pydantic/logfire-helm-chart), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/logfire-helm-chart
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5ac371653e0c109d3b54b761b5dc2b400666e403
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5ac371653e0c109d3b54b761b5dc2b400666e403
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ca644b23c14659ea2485eefdd4c858624470df.nq.gz
│   ├── 05b83594d01d7f68d727eada3e4e4b54539d39e0.nq.gz
│   ├── 07ec4f4c2c7337df55798dad935a97257fa06693.nq.gz
│   ├── 086f30e5105d1d3f0cb383b295ca0c4df39c9b9e.nq.gz
│   ├── 092a4772d396d6f1f43f6457465f16fcac0588f3.nq.gz
│   ├── 0b9f3e7f77479420b0181b858ddb2004ae4caed3.nq.gz
│   ├── 106656bd89ef39b7df7ae408521a0e344df0195d.nq.gz
│   ├── 116850e035303e71ea4bf9b255503671978f2b6d.nq.gz
│   ├── 1803c3b5c0d3ec086b6a00aac19febbd32325ebd.nq.gz
│   ├── 1b6ce2a4d20457a7da0c79fe4947e5a9c23cfd5f.nq.gz
│   ├── 1d4facec33372f8091d3b8449ff7903ebb63cace.nq.gz
│   ├── 1e4e13b4f66876c1c0f033b574d9abca05eb5c63.nq.gz
│   ├── 20a2ec83178190a1126ff0d49830f262ede35313.nq.gz
│   ├── 232d643f0b2319af8715e54af79235ab3c86bec9.nq.gz
│   ├── 23ccc777abec3ff2e7c98b695df12a91bbdd88b0.nq.gz
│   ├── 2636aab565da17e8b6102e9fed32ed02b698708b.nq.gz
│   ├── 27ce986f79ca7f91a68de55aa26de84d92d7c8d5.nq.gz
│   ├── 283e5016c591b595e0365cffa4777a5e9095d1f5.nq.gz
│   ├── 2855ba6eee6a34dbb72bfbf0aab73fc1e8038762.nq.gz
│   ├── 2ec4addbf3c29f7abd5da8792ebb5286a34848dd.nq.gz
│   ├── 32543bcca868900067be21edc16e936c0a399093.nq.gz
│   ├── 332e6b7f3cac41aca4eb9aa269dcbb2f57de7b1e.nq.gz
│   ├── 34b838995dee297697739da40c06b09334a963e6.nq.gz
│   ├── 35405d18902efb588505ccb4056506a7fa6f2845.nq.gz
│   ├── 39c60582a1af68accb4402d22423de2fbc49f746.nq.gz
│   ├── 3c75c4714d458233deaea802b87fbc700b87263f.nq.gz
│   ├── 3ccbecc06211cc98d87e34432ab4dac3041602c6.nq.gz
│   ├── 3f816e47ca2611cb5a272fd94c8d70acc5f92c07.nq.gz
│   ├── 446f3d2acc1a4670fc651d4756b9d5d33d9b54ee.nq.gz
│   ├── 4bd3f21b66f7c013a3e3b097fb511433c069defc.nq.gz
│   ├── 5325c4b71450cafe72cae1fb7b3f7211ab98b5a0.nq.gz
│   ├── 56ef3f818f2c1dc6efb49aba74a3c24d54320274.nq.gz
│   ├── 587297fc7f9016b01d417cba63080c1bf51a2502.nq.gz
│   ├── 59641ae43e0eb79ce8baa128b5f1a5054f7650e1.nq.gz
│   ├── 596a098264bbd3c1c139d3b5d1682a2e5498ce32.nq.gz
│   ├── 5a647649e75d715e030e05fb3db9e8a998af2695.nq.gz
│   ├── 5bf82967dbf64e2ff60f2fddbe19465bd05b38d8.nq.gz
│   ├── 5f96af392fde3abc63ed23ab79c2a47384746ef5.nq.gz
│   ├── 6565af88d956d5f97dccbbf3f661ef6361e3e3e5.nq.gz
│   ├── 677016fc5fc3346796a1663c692dca14a0938a10.nq.gz
│   ├── 6d918425627e3b400f39abf4e3c11d2e63838162.nq.gz
│   ├── 70ef7b8bdb8d3b98a481e11b20f2b0c1c4f5c730.nq.gz
│   ├── 711a39c541afc04f86b51e268b350d204f48c875.nq.gz
│   ├── 799e80728230fc8514081cf34f1d6296b70104d5.nq.gz
│   ├── 7a404ac54598495cca144ab7c90cf70616320784.nq.gz
│   ├── 7b52b62cd7f390615f70771712083fa68e8c9740.nq.gz
│   ├── 7d526f750c61ef5f494173da8c3f1b878115df1d.nq.gz
│   ├── 7fcb45dbbd123ffe170ea55f23883a3be25353e5.nq.gz
│   ├── 8077668ef748f292dd0a277897845e185c8acf88.nq.gz
│   ├── 8304f0b93858ea9a4db92ae23c652e85426fcd8e.nq.gz
│   ├── 837c26f90ce0927418c843767187a91012710aa0.nq.gz
│   ├── 83ab35a2611271481e64f8959c362556847fe5cd.nq.gz
│   ├── 8769aa3cb9f9064309356bf1dc89d493a28bcbac.nq.gz
│   ├── 8792df79a9da82fbe57957ddbf0002fe79236c15.nq.gz
│   ├── 882f5257d6fe217e56b12548dffc3cb5568f1cc3.nq.gz
│   ├── 88b735be78aa61f743e47875bd9e938827f7c755.nq.gz
│   ├── 8c3486ea7f7297b7fa226890a378a00486329012.nq.gz
│   ├── 8fe7bc6dd269131c5942ed67f5383f4a21be99bc.nq.gz
│   ├── 907cab4930c06d8970e78429ce3d6c49b2f85451.nq.gz
│   ├── 9231c94be0689222dfe7656201dab4172b3f6c42.nq.gz
│   ├── 92587a565e905b546818e858a05c5de4e97e7248.nq.gz
│   ├── 93c0c7279c2217325fe12726de1db7866275a0c3.nq.gz
│   ├── 98742c18be9fc29f4c3eb69909669214d64d67cb.nq.gz
│   ├── 9b6496f6e0708794b5abb99c446c36a7b6236465.nq.gz
│   ├── 9eba82799e9c433dc9fb15b3f69bfaed2103d88a.nq.gz
│   ├── a0845bc59a03ad81f06b8a237770b0d08c2cad7b.nq.gz
│   ├── a358ed42c601ddd1eb28b5787c238e87b24d2eda.nq.gz
│   ├── a5a0798f1c38d820533248d2c5828db8542ce94e.nq.gz
│   ├── a665f776844ba7dc47f58dae2308fce74d23770e.nq.gz
│   ├── a8d85b7ce6b0bfd675fa88533a6991388ec22c55.nq.gz
│   ├── ab083d5376743b7b8de33ff1a10988d753396794.nq.gz
│   ├── adb58fe403ba815ae1e4bb59f56bb591e7938411.nq.gz
│   ├── b0729ab0d23d1273f83fa464ae82811be94ccf26.nq.gz
│   ├── bb7c6211111d4b37b3cbec2f048decaffcd8d296.nq.gz
│   ├── bdfd2cc2f74f0e8ff014a6b36682fad78381d905.nq.gz
│   ├── bfb35eb8bb7d6278e5c13c65885ffe20c1312417.nq.gz
│   ├── c185c268b53eae6b137b111f7f8c523069d10965.nq.gz
│   ├── c229c136b3c50fb46dbae0364a2bf8b221ffa35b.nq.gz
│   ├── c48840223a0e39a301b042af81b1ea1f10d7d9fb.nq.gz
│   ├── c549f4f2acc9b84c9aedb0a68ca815cc0b8bd5e4.nq.gz
│   ├── c9244e699a49f825af584be21c46d495ae269339.nq.gz
│   ├── c991d2635f101cf5ab1f706a2523c664fe20396a.nq.gz
│   ├── ca13c71ae48865e24bb9733e369114523b55e24f.nq.gz
│   ├── cb0f0ad8924ee0870b3c33b7a6b2807cf97d56e2.nq.gz
│   ├── cd9161bee8d297d0b68da74f1f2c6c4ec979aaae.nq.gz
│   ├── cfbbd19360d419e7cbb6c104698eb2221350d346.nq.gz
│   ├── cfc2f969f40873378e7f90affc6e819939d5c4f3.nq.gz
│   ├── d09180e43a5fd3baaad91354fa57f8b3ca0a2b3c.nq.gz
│   ├── da8a036fcc5534b2f49d987c31a70d702c4ba68b.nq.gz
│   ├── db1c8a367d34e2671ddf6d6b5cd3023a18bf3c6e.nq.gz
│   ├── dc937ccdc78ef527fe32144e4a5368d9a5980287.nq.gz
│   ├── e15c4b5a2d89f2371494942394b40c3b93bd3d91.nq.gz
│   ├── e63c2571db07cf47e718322f51e667d75d91aa32.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73253dad06c6739f91639fa7150c2496760e6a0.nq.gz
│   ├── e931a3499413e5c459fbfa412f4510143f71d6ba.nq.gz
│   ├── eaa0899bf5253d388ca6286d4eb3a6b32c7046d0.nq.gz
│   ├── eb7d9c36d1635a94ab387bd473c317bbb027b871.nq.gz
│   ├── f16c919b7ec2fc66c648b8ae36762ba210fc1382.nq.gz
│   ├── f4b003faf48e2063aba26e573c5fc5f24c4ca2f5.nq.gz
│   ├── f81bffcbea42194c0ba521829f98c263bd41fcd1.nq.gz
│   ├── f8bca8ad6f1b6982383cfc3c6a78304252d3bf10.nq.gz
│   ├── fa2255159b48d7a33acdd141cdace5b802fc1ecd.nq.gz
│   ├── fb07bc730989b6a7dfd8502666e723e0a82850c9.nq.gz
│   └── ffd756436d0cd153cb4465a168426bcf47f9954a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5ac371653e0c109d3b54b761b5dc2b400666e403.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 113 files
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

[pydantic/logfire-helm-chart](https://github.com/pydantic/logfire-helm-chart)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
