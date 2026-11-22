# Repolex Knowledge Graph of bitflags/bitflags

RDF knowledge graph data for [bitflags/bitflags](https://github.com/bitflags/bitflags), parsed by [repolex](https://repolex.ai).

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
rlex download bitflags/bitflags
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4ed9ffa949970239cd2d87c775e9fdcf9c438fb5
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 4ed9ffa949970239cd2d87c775e9fdcf9c438fb5.nq.gz
│   └── repolex
│       └── 4ed9ffa949970239cd2d87c775e9fdcf9c438fb5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0139319e91864e2259577139bde868ec642e4fb6.nq.gz
│   ├── 01dc1ccb465aa7efe99580a3723497a143c85307.nq.gz
│   ├── 020f7e927e242d680b0c0632d7dc23f4f31a4656.nq.gz
│   ├── 056cfa6b15968094aad0a0d4177b90462f654522.nq.gz
│   ├── 066f600c0fa2f18522ebe6543c4444d063168ddf.nq.gz
│   ├── 07941f36cfd57c7599782d78ac0ffeb52d6fcd47.nq.gz
│   ├── 08b44a0a3133a95a4d327deb547ba610b7b8378d.nq.gz
│   ├── 0d8e3a460805404de5252328feba952844f7c6a5.nq.gz
│   ├── 10a55db8dd0d3e4e076c289e783751818e4a2dd7.nq.gz
│   ├── 10a8ae9fb6b6a4942524642f021fa001e02f871b.nq.gz
│   ├── 12428ddcb09c7612936f0575c212999c599fa8ee.nq.gz
│   ├── 1310bd01fec503b1d58eef21d3113d53ae1caaab.nq.gz
│   ├── 167ce44ce094fb19bcea6127d57764ddf4dc915b.nq.gz
│   ├── 16d583bdb3cb69d66fe6444e52625e6d2dae373e.nq.gz
│   ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
│   ├── 1ae28a663fd62dcfeabdb9140888cc728ee54af0.nq.gz
│   ├── 1c81656c4209e9710158526887ab6feffab2a011.nq.gz
│   ├── 1d9a4e48b650b3db13671db12506feff8f32ab49.nq.gz
│   ├── 1ecdafcff1f42b448dd9cbff539c6d34adab4949.nq.gz
│   ├── 21ae278ebf23629724703b33fdc1b8ba889da5af.nq.gz
│   ├── 2869a509c91cce8f712b372eff1dc3d56bf84e13.nq.gz
│   ├── 2a9a4a56d9fca44c6046b871827e445a7385cef9.nq.gz
│   ├── 2ab0406655ef6628f18668ed122f3d75f108d486.nq.gz
│   ├── 2d42cce4e3f98b5a8accc0ba86edafd2afa0b902.nq.gz
│   ├── 2d64659c9a8fdd9e0aacb4d45e272ffe8083d759.nq.gz
│   ├── 3052c460ec33ab49d68ffa68ed941703dd21f947.nq.gz
│   ├── 3146d591cf3bbbe0563ccbbb48ccdfcfeddd1e27.nq.gz
│   ├── 323b8583758d7c43e4ad37a43177b4d74f6cccf7.nq.gz
│   ├── 34b432da39b8fdfbc3f9ae5006f6df672c974716.nq.gz
│   ├── 382a458f610b0ffdab97683d0091a0fdbc3aa87d.nq.gz
│   ├── 38f4822f5a5f270601790200f4e0f5976d1d5dd5.nq.gz
│   ├── 393ed8f8df5f7dfa795d45dd0a736a68160d28d9.nq.gz
│   ├── 39d4bdb5acd313c1a92dbeaa1c379aaf0596a315.nq.gz
│   ├── 3b72e1a81ef42298700d5ac248cf01a5b55c63ed.nq.gz
│   ├── 3e6c557bce52acaadd62dfc48e66aa2ba7d01f5b.nq.gz
│   ├── 3fd15191b9794ba5b78971f18dbb811b3cadb923.nq.gz
│   ├── 454eadf49ffdf610ae26c5bb0f10ff2bdc217dd7.nq.gz
│   ├── 47549215948d11c0097c67a691180b7c9f30f7b7.nq.gz
│   ├── 494f104e19dab2b5ddb23b752fcf825293ec3ae2.nq.gz
│   ├── 4abbd630c6e127946a3f78678b6f895d0b6fa9b7.nq.gz
│   ├── 5665dc4f9a8ce4f21786621487cc5f705eaa5d1e.nq.gz
│   ├── 574b1edbf228f2c699767ce09ab08d12c1a28995.nq.gz
│   ├── 57fb1c7cf18789d5977b8beb90713d1d044835f3.nq.gz
│   ├── 586ae158e3bf733f5a654f9662a0e98a26468600.nq.gz
│   ├── 588336398290c441c635919d942eb1493c8f3d16.nq.gz
│   ├── 5a3b81037da15b7a3fbbe61080d8b6d7d23f4b66.nq.gz
│   ├── 5f87dd912d6c2fef09e6dc66903429f30ac22aa9.nq.gz
│   ├── 6190681931cac1c3d3c20f80f4b089e643b5a5fc.nq.gz
│   ├── 61c33314e6d9db539bcd598d5d6a7b300ac2f7a7.nq.gz
│   ├── 678f153e36b15af463e4e06bfbcc138920e42a0d.nq.gz
│   ├── 6a69d2d8d3b8c86098439fd7ca799442fae56e12.nq.gz
│   ├── 6bb2b651dc207a828b1e81c3fc64b86f1daba247.nq.gz
│   ├── 6ce9c0bf1981a3fa51ea8c4683d294521fcc7793.nq.gz
│   ├── 6feba36ed82c138dc35243e938f3ea6f2821f9fa.nq.gz
│   ├── 724b2074cf0c850d01fc0aeb83992417142e0916.nq.gz
│   ├── 7563379005c81360bde75e81b9eec3460e1b637d.nq.gz
│   ├── 75e9123ac5da42911c2d89a8c00e0ef1ece4b9a7.nq.gz
│   ├── 790ac5b59debde1d5dc5547635d6541cb5ae50fd.nq.gz
│   ├── 7a4d204aa587c7942d05041aa670b7da3b467c9d.nq.gz
│   ├── 7a625b312c1ef0d75366cdf5b65d71ac4e18474e.nq.gz
│   ├── 7d10799c191123e591e10f08a77397273688a1e6.nq.gz
│   ├── 869dc17fc81b6125f908e57caff51866e89fec47.nq.gz
│   ├── 87d01cc0cb5f55edb1b3b451cebde8095fbf85a5.nq.gz
│   ├── 8924bfdf31a6e4cb6c8305b370fec3ec79b1e6c1.nq.gz
│   ├── 8cf1c9fbd4787fe6b103992dff4465edf0e9d2f9.nq.gz
│   ├── 8fe1d9003e92bbcb0c868a66d705791326c74981.nq.gz
│   ├── 91d89823018f83787e49ed44dbb72d1edbb629cb.nq.gz
│   ├── 92165f18e36bf05ea7e580c3fe12b62836ee1adb.nq.gz
│   ├── 93190f8bb4ef64301661bdde9cc1b1232cf66ac9.nq.gz
│   ├── 93dbf1b1b039d7695c17aaa32b0caba3451eb9e5.nq.gz
│   ├── 945419c109b69593ac484bc2c47ae069abcc104c.nq.gz
│   ├── 946110ce2c7acbfd1ae3fb2ef7d2916a84d762c4.nq.gz
│   ├── 9779af7629a988ba98d2c8a6bd484d104deee1cc.nq.gz
│   ├── 988db41631c2696d7fc73ad4cd30239e370edc86.nq.gz
│   ├── 9f224b093e550c5fafcff0df555b505146d2b94d.nq.gz
│   ├── a132d2f9ba6795458762b4b201207d624a9ddcca.nq.gz
│   ├── a14ccc9153598c959d699309056a7b705083881c.nq.gz
│   ├── a603233ea560bf5236abb50fcbb1856b31f4403c.nq.gz
│   ├── a7519f2ab410dac4e6b0a11eb7a60bc664dc0e5c.nq.gz
│   ├── a9707a0697af3c106af4022650b814cbe201e7f5.nq.gz
│   ├── a97b6536f2b582666b8ba86186c79c1fbbf04e60.nq.gz
│   ├── ac7a421af0beb6884ec0a8bfa85afe3806f45abe.nq.gz
│   ├── ae0efc930917fa769bc988bdb0f8025e43d0932e.nq.gz
│   ├── afe22532dc538801bf854a886ebd657141261d7d.nq.gz
│   ├── b18cd17235288cf262baf8afa9ad51d1bd0f2ce0.nq.gz
│   ├── b1c57dac9c5b06aec24e868d1777f5247f03e829.nq.gz
│   ├── b4b9d6cab8a3a9285dd38eccccc98d8b6cad2946.nq.gz
│   ├── b5ff3d8eae6d8dc539f181be557eeae8b2893a4f.nq.gz
│   ├── b90f0ce92d1e6f1c30b3f37272540964e47d7a55.nq.gz
│   ├── ba26723f0c4c41b3e3857e48025cfea5d135bf62.nq.gz
│   ├── ba6d21010c011414720c0575fdcec68d5676d01c.nq.gz
│   ├── c11050e3baf0cdf1d7b28d31999af5ea8d80a8fd.nq.gz
│   ├── c531f976509691e873f1bc6142c3bdb9156d635c.nq.gz
│   ├── caa9203451a12e0f7e19a09f3d79d6b1061a20e2.nq.gz
│   ├── ccd535e34a3eb4da022a829c2fd55eff898312c2.nq.gz
│   ├── cceb93a4691b0735dba18098344ef6e285c6c09b.nq.gz
│   ├── cfff19ab29304b840249645a6924711c40e4f79e.nq.gz
│   ├── d17464e512cc2b5063cd37931ae53e8606e8af24.nq.gz
│   ├── d2dba5bf6b441cab9f8c2f8c171e718e51e48e4d.nq.gz
│   ├── d4b2ea068915bca86ffb14f58b48d144ba2f8e96.nq.gz
│   ├── d872a0fbc0204ade5c3166f31dd1eff63d2d5212.nq.gz
│   ├── d990a994bba37de25427ae872c1d8a575ad31edf.nq.gz
│   ├── dada9aff82326c169d95f055f53a8ec727830602.nq.gz
│   ├── de0da54cd1e8ac3334fcd1336f51a8cc67111771.nq.gz
│   ├── e38db4dd11b993b39e9f5c3498892efb8016478b.nq.gz
│   ├── e38df48dc5987082f804023d0fca3afbdadfa387.nq.gz
│   ├── e4f3e537c4a3f19a5ac295d2949972cc64c17395.nq.gz
│   ├── e5b14cfbadd89ce47f60470b9de0b598c2c5e2cf.nq.gz
│   ├── e757dbfe74c53eb6765ff3e73e38cc52c4d2c8fa.nq.gz
│   ├── ed4571877dc44f85d130f3139e5a9d6429378bef.nq.gz
│   ├── f0653b6a492a0935a6e27024d33d9b4b96e510bc.nq.gz
│   ├── f7add90ae35556c9230005e0c83110abda5d4d53.nq.gz
│   ├── fafffd3ae197dca5687d0ba402d5b244512e56f2.nq.gz
│   ├── fb27225ecef60453a1768f81d4cf884c5cc44045.nq.gz
│   ├── fe907981a2ad660171a13f0017bb6fdd1a5c710e.nq.gz
│   ├── fe915d47eb4c356a22fe628e0d59a00b88a8d08d.nq.gz
│   └── ff3d58e5d2f6b5dfbb66f0c1f479309c81a30f4a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 4ed9ffa949970239cd2d87c775e9fdcf9c438fb5.nq.gz
├── filetree
│   └── 4ed9ffa949970239cd2d87c775e9fdcf9c438fb5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 127 files
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

[bitflags/bitflags](https://github.com/bitflags/bitflags)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
