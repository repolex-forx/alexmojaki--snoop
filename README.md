# Repolex Knowledge Graph of alexmojaki/snoop

RDF knowledge graph data for [alexmojaki/snoop](https://github.com/alexmojaki/snoop), parsed by [repolex](https://repolex.ai).

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
rlex download alexmojaki/snoop
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f2f345f3ccc67e170b5329d345acd82e146a62b1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f2f345f3ccc67e170b5329d345acd82e146a62b1
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b3ef59ed85e206c18d773b53c169d36f30ffb0.nq.gz
│   ├── 04ed3dfce65b92852bcd351677a9d538fd37aa95.nq.gz
│   ├── 05e77db075ff2bcb078b34279a5876e4aef564cf.nq.gz
│   ├── 08ea2ed1e2663c2af8c64ca5c314846fe5825036.nq.gz
│   ├── 0b3079514b6a578eb9877a23b467264a6404cf02.nq.gz
│   ├── 0b4009842be391fcc2e2c31c0106215ae95527de.nq.gz
│   ├── 112789db810d794667243d348aa022e9ef4ebd80.nq.gz
│   ├── 116790767faba436675d7c889e2745d981b39155.nq.gz
│   ├── 12cb857301b10c68856e0353fd18933a18201758.nq.gz
│   ├── 12f74833f6e513072d6769b541314a36f80eef14.nq.gz
│   ├── 13279308f7c415ce23b4f9857a9db53e026f95cf.nq.gz
│   ├── 139918f6461f00344f7b28cfa28265d30c56c242.nq.gz
│   ├── 14512dc98dd300c3096fd853aa37dbddd992f6a3.nq.gz
│   ├── 17abeddb73082f7d412522da8a400e27d9e66af6.nq.gz
│   ├── 184464c4f06aeee89dbec8dffca24898d4054641.nq.gz
│   ├── 18616294b6c65dc3f95ae7ab1b86f9ad4b0685b2.nq.gz
│   ├── 1c3a9f093f6f9d77dc75130ac3837d79c3352e3b.nq.gz
│   ├── 1c8faf9c421e46ca0b9ebb3081eca46cff57d36a.nq.gz
│   ├── 1ebf0891791883fb056612adda1ad43cb0092d1f.nq.gz
│   ├── 20c5affb048aafb4e4e3dfe8a8202ec849f97da4.nq.gz
│   ├── 22f50d09c70a93fb2e4fb7a57b975c31269e7007.nq.gz
│   ├── 28702552b385d24d3eb80b1c954e4f91043bd786.nq.gz
│   ├── 2976dc44a8c94c457e8404fda43218d6dd95e358.nq.gz
│   ├── 2abbc8b367f72252fd618185a77308b11a94c638.nq.gz
│   ├── 2ac54ec00df693a0469a58eb1a03195d1ad6a094.nq.gz
│   ├── 2b6c67ad47e29e428b1c175fc8b57a6fe7dfbaee.nq.gz
│   ├── 2bb8fd9c6264ec39241e821148e76e69c3e3dde1.nq.gz
│   ├── 2c4d8f85e5e576891cd8e164e36462095a11e05d.nq.gz
│   ├── 2e8cc268e1055071819b4c396848d386cb7554cc.nq.gz
│   ├── 3048bcdfaef09840c19beb12ca97cb843f5adce4.nq.gz
│   ├── 328e3572f71235fb408e729060c8f1acab82fbc7.nq.gz
│   ├── 32f216c4ea2d7254bb61685b887a488c230870ba.nq.gz
│   ├── 33c6f13611fcfbde21bb7c79d1cb27ce55189122.nq.gz
│   ├── 33f457849fbd86fc9fc6b888c66e7a6854f69358.nq.gz
│   ├── 3739760b220d35acdbfc98d61a8d7528e4c4d317.nq.gz
│   ├── 3e677d0574e31ae815bd38f046220966261d5326.nq.gz
│   ├── 3ef5a5259b43693ca0806281c3e74347fb598c26.nq.gz
│   ├── 401816e8d1737f7fb9389fb89d7599e4633302bd.nq.gz
│   ├── 4243932e49524c24824109015a60144e36f0b4cd.nq.gz
│   ├── 496e974e2643c752bb3a4d963f4dde9896f6d049.nq.gz
│   ├── 4a248767097ef0b771cce3446dca098525a9ddc2.nq.gz
│   ├── 4cc92cd9a2394959b475bc4451d8bb5172f14a68.nq.gz
│   ├── 5213f52e5c1b74a907c4c5448b1dcfe8c418b9e8.nq.gz
│   ├── 52848d4481528b7fe426d9fc6c59d575522ad172.nq.gz
│   ├── 533dd94b74982b1a3ca339cdc519d73ba86f8535.nq.gz
│   ├── 5384cb5416605148684ab7c3de755ab5c2cce99c.nq.gz
│   ├── 53a6bb07bd3a878628be18665b9761f328bd561f.nq.gz
│   ├── 542d83d0456acd23ea3e78843d8b06b614b95275.nq.gz
│   ├── 58004aee816475d32162393d2fbedfb089c3ee02.nq.gz
│   ├── 59ed591c0f11d7924437dcf76c30d55d978e29a2.nq.gz
│   ├── 5af5545bc15339d05ddf7a5c50762286ec5c7e35.nq.gz
│   ├── 630ba54bc6ba09a7cb9e4884c26f59aad79d1752.nq.gz
│   ├── 665a3fe71f8fff2c98391ec4cb2ae204c676f308.nq.gz
│   ├── 67711cfce36d25c9005b00b20d6483aac657b911.nq.gz
│   ├── 69cf202404da42c802fd51456a2997c5a77b9a66.nq.gz
│   ├── 6a2fa18af68bb6b5416984672b7efbc438567f4e.nq.gz
│   ├── 6e11047f1563f2c628a6e847adcb6771b8f21bc7.nq.gz
│   ├── 7063835a771a04b01e391def04d20dd6b71725df.nq.gz
│   ├── 7167c87f0bb99e0aa13e020e013c0caa251d7edf.nq.gz
│   ├── 75149525b4c413483d2971af57cd19b8364dfafa.nq.gz
│   ├── 75d6466ab2aef6f693a609d580b36c7dbd05c362.nq.gz
│   ├── 7bd65dfcd12f9026d2737eb8f01ebe6546557e45.nq.gz
│   ├── 7c14bd548a1dc2afb0bf0dc9daf56fd64db682ec.nq.gz
│   ├── 7db2c83066148e041f0d5988d419780437718b37.nq.gz
│   ├── 7f1a1763ca9cebc7bc16576d353d3284ee5d3c7d.nq.gz
│   ├── 88b70ff4482c37af38d6f56c8fa66e711d4a5e62.nq.gz
│   ├── 8a998698cc550128bbacf8ae0321fd8e9bcafb57.nq.gz
│   ├── 8c4fa77dcb36f5838d17b5aa8f270fe85e58623a.nq.gz
│   ├── 8f061aa67533cd21c16a32fa09f8259deccfdc95.nq.gz
│   ├── 914fd36063a15821108b8d826ba374849be329fc.nq.gz
│   ├── 9260538fbc6121cec8af812b4b6589113ad32a54.nq.gz
│   ├── 926dd5119387773c795911979b45d4f2425193a9.nq.gz
│   ├── 97040e10962fd9f8430fa78db0eb87974523cbf7.nq.gz
│   ├── 986ce49946c9e6e07619b6bb300f37f5b7bd6625.nq.gz
│   ├── 989c594894a2f37f22ad1096e0de369a7f822487.nq.gz
│   ├── 98e3b1a1837e43a2873adac0476c4cf9ffbce928.nq.gz
│   ├── 9bb2df28e31b12555dab9a68e6be153eb7f7f670.nq.gz
│   ├── 9c2417556981d8a0785b844d96e6e465c8de13ae.nq.gz
│   ├── 9e0cacd30348b71e49db358de755cbf3612a9a19.nq.gz
│   ├── 9ea88a96650c17603c25064e341776741b2ca81c.nq.gz
│   ├── a34730f0c8e60dd94cdf292190a2ed84c2169093.nq.gz
│   ├── a375206814a10669d64033c67a106930f86421f7.nq.gz
│   ├── a6bbb85bd664239debd8302cf36c1b60e2066120.nq.gz
│   ├── a8f69f72a739806dafe8a8d215d7230e51c7bee0.nq.gz
│   ├── a986f7c5a44626837bcdf04916e646e71a3e382f.nq.gz
│   ├── aa8d5d76c2b99004dd36c33c5613b21584e41357.nq.gz
│   ├── aaf8a78787af0507dc975aea6c3ac6d4e3ff1cad.nq.gz
│   ├── aaf9da745bcff8d17e7fd255bd718692f08efe05.nq.gz
│   ├── acb82efd03a187026251624928296be85d7960ae.nq.gz
│   ├── ad3717cf404caa3cc8531b1e97e5aa3d2864daff.nq.gz
│   ├── adf5470b6e506cd77bae5d79eb501c878da3e617.nq.gz
│   ├── b0519ecaad8f4e255ce8e082528ea5ed51b23ec4.nq.gz
│   ├── b399770f201caa1c7925a8af34ff7f57a5e392e7.nq.gz
│   ├── b3b1b7d4103e921584c6ebd43a130ea0d2a575d4.nq.gz
│   ├── b66a5fa2dc7a392a7852712778125fa042f99c6b.nq.gz
│   ├── be4f886e561a007e2952509e75d37f536dc9b2ac.nq.gz
│   ├── be8b9b1812490ab667b7f1e579104283433f3477.nq.gz
│   ├── c3e172b1c1b9b2dbfc97b5acb601464716c54103.nq.gz
│   ├── c521f97e0d1bd4c006223cce84a8040cb1168b37.nq.gz
│   ├── c7a919eeba6faa6bc614ff5b35c6a686d5f64b4d.nq.gz
│   ├── cbbca56c6e9100f286e7d78049a573b14718691d.nq.gz
│   ├── cfc655cc08a79f13603a577fb25110c46a342066.nq.gz
│   ├── cfd3adcc2f9555cf8e446e8d7cec757a0ff4ef52.nq.gz
│   ├── cfed7001853332a880748f81fbc4d6ebf0a610d8.nq.gz
│   ├── d1a3204412bd6a60f29dee967ef973142563a65c.nq.gz
│   ├── d330b6146c1f080209a4ea18da4d97ed52110820.nq.gz
│   ├── d3f8e336a3381382d12493abd9fdcd3979b0ee08.nq.gz
│   ├── d4029f4f0654f71250e792c8baff4fdb5233cdcb.nq.gz
│   ├── d7ad679e61970ca97b766ae49fd3201bcc72e01b.nq.gz
│   ├── db434724c4d9815432e13e2ec936b6f7edfa2171.nq.gz
│   ├── db60abd54a29bb59764162ecaf1f3134757d4155.nq.gz
│   ├── ddba160b46cced54b229713cd0b7f1f717bf275a.nq.gz
│   ├── e26095b13ed890e783d8f7edfb9fbbe5eae53745.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebadb6386bd064ed8c4e662de135c826f87252f6.nq.gz
│   ├── f23ca83c4f995d4b2a7fc8a0e0c18a63b09c35be.nq.gz
│   ├── f640c90da4b21f7ed6647111af2777c05f1c9090.nq.gz
│   ├── f78e2eeac79e7f9ff7d228f71ceff5f5ca96295d.nq.gz
│   ├── f811092000199c17d22cbc0248694e9a1538c078.nq.gz
│   ├── fd46d74c40572a269ee885ab22386982dfd644eb.nq.gz
│   └── ff473f4df1f941e217a7c843b5ca49efa42d8fe2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f2f345f3ccc67e170b5329d345acd82e146a62b1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 129 files
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

[alexmojaki/snoop](https://github.com/alexmojaki/snoop)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
