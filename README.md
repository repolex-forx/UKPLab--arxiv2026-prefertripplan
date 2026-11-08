# Repolex Knowledge Graph of UKPLab/arxiv2026-prefertripplan

RDF knowledge graph data for [UKPLab/arxiv2026-prefertripplan](https://github.com/UKPLab/arxiv2026-prefertripplan), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2026-prefertripplan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d4b7f0cfd1d9b97165b010ba1fec08b63413bc76
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d4b7f0cfd1d9b97165b010ba1fec08b63413bc76
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ce0d1f91d203b15d40dfc568b71af872cf6f68.nq.gz
│   ├── 022751506ca8d327cb9a0512e7c39b07e38ff82d.nq.gz
│   ├── 053ef06dc68f7c85e590e1f9ab63c7c608ceacc9.nq.gz
│   ├── 0d03bf268c448d14aeb9becbc045bcde4ae6c9b7.nq.gz
│   ├── 0d39a67c24f01c1af1e9cb675f380c3a1d1b2422.nq.gz
│   ├── 0d9360dc35d158ea1ccd025d9520994762579eec.nq.gz
│   ├── 120c6893b8af8f69dddc51b2734ed561b78c6091.nq.gz
│   ├── 14411fd93d699377c6e17280cabaf9a39d67dbdc.nq.gz
│   ├── 20ae46413be426f665fe4b213fbd2a66820cd737.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 25b44b07e9a5dc17571362b92d19f670915a0eff.nq.gz
│   ├── 2c0a27ead02e888f6b0c55adfcf7604b46c09e1e.nq.gz
│   ├── 2dc2a8fa00f487a8b3db7731a440640af682db3d.nq.gz
│   ├── 30ae737ac3bf9d833844aaa1d7fdeeda3580539f.nq.gz
│   ├── 3af26c3e1b90859447743d666d0aa4641cbf6d45.nq.gz
│   ├── 3dc429a6613bf85898a47643fe31d4439fe9d973.nq.gz
│   ├── 3f9297d7e4a0287ac097ffb20ea79250c96ba7de.nq.gz
│   ├── 435e6523bf38d5785b69b6da0ca53d2db2646358.nq.gz
│   ├── 45c94f6d8e39f3b7ace728febbb20e6294eff290.nq.gz
│   ├── 4cef27e61ea9ac6f982e68a89dcb12432298bb71.nq.gz
│   ├── 4db31f8b4ee1e1545c32020dc18a961c03c1294f.nq.gz
│   ├── 55559d8f50aeb2a035b37286f8fdb6cd66c8e87e.nq.gz
│   ├── 570e64b7f187d2e292814d4d37452b74d6066ccc.nq.gz
│   ├── 5b8d1ba8a9ba74513f6608b52cc930f86ca4cf9f.nq.gz
│   ├── 5dcef726f671e400c7a0873dc8e9d9f061889630.nq.gz
│   ├── 607666d9db62aa818ca5b7d22a26c12180368e6d.nq.gz
│   ├── 61b53e6e9f0c9d3299d24fa214fa5f563b961055.nq.gz
│   ├── 682f1dfcb3af33e831774b76db641023344b4df2.nq.gz
│   ├── 68eb69b23434984ce6053d307b6b6b7f709a7e7e.nq.gz
│   ├── 698e9f972a96948e15606d89ceda254e571d2692.nq.gz
│   ├── 6a171a558f6a2db926e56026b27c8a2cc3de9a48.nq.gz
│   ├── 6e96553257859fe508bd21c3262a455874e00e01.nq.gz
│   ├── 6f6526116993a7f684139030852b21aa3c02764b.nq.gz
│   ├── 70a0b1a964adee633bf8085ddcdb7d7dd600e02c.nq.gz
│   ├── 71be9bfb8acd7866056be458bc50b322bafe36c9.nq.gz
│   ├── 7530d997ba5cc89f84ea26612d37e965904103d9.nq.gz
│   ├── 7da17224e471cee2da318c727c9589ed1fb3797f.nq.gz
│   ├── 80edbe69480d266efa7419896f4ca8051d6108b7.nq.gz
│   ├── 80f9dedb22582266a9daa4b5a74a2b7ef60f99a4.nq.gz
│   ├── 817cb003740e5c4d434dd64bb6c2850ee9b240d2.nq.gz
│   ├── 826a8849198cf8c133eb57af1003066f308227ec.nq.gz
│   ├── 829cafe545fbc5b6a622128620b975639019a6ef.nq.gz
│   ├── 8448880e27f2717b9be5846efc2a3ea74ebb0227.nq.gz
│   ├── 8673c52ca81866d2c46b7de30d8a113e26ad688d.nq.gz
│   ├── 871f997c792607b58ab9cf6fec7402b4de38f21e.nq.gz
│   ├── 8871abfdc9c3745a372d1b55952f4d24481e3ea0.nq.gz
│   ├── 89f79d04b69ed907c42ae436aa16e9cfa7cfd9bf.nq.gz
│   ├── 8a32ee34b1603953ed79a91dec01453f67fb93c4.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b14d41f730e3642c5986d15e956bb8af5134367.nq.gz
│   ├── 8b51779c7207823fec1d188ae1337dee1a890245.nq.gz
│   ├── 8c484e9a9f6b3f3c3e669f38c5bf2b6b40f2ee50.nq.gz
│   ├── 8d956b1f65d4b6893e85344ad98105531616a570.nq.gz
│   ├── 92c90a84b14420c8a3970c07a45a1862604e0026.nq.gz
│   ├── 934ec25d21288e6849a87f6588969f2e7a56bea2.nq.gz
│   ├── 961176d027b77b0b1b003388250e0917eb6fb535.nq.gz
│   ├── 9af0498406eb71abc3d61f74c4b2580cab62d039.nq.gz
│   ├── 9b3703a912d40f58fb0fb57d20742e53d9fe7671.nq.gz
│   ├── 9c5d240e27576de8890638ffa7eaa965891436c9.nq.gz
│   ├── 9ccc7363dcc9155dec920e64a9820737d3fff0e3.nq.gz
│   ├── 9e50eb1444db0f70aac33852195e32f07e0a2c4c.nq.gz
│   ├── a39766b3c513650b7f668d02547f55acdd186a05.nq.gz
│   ├── a4b65e9bbce9d23895b7aaa0fce86d3b3ad33f94.nq.gz
│   ├── a5dc05207eabbdc9386eea7bb9efb7f7ca0b6e8f.nq.gz
│   ├── a70d291241eea483a3e2ca58d7c779b17cc164b8.nq.gz
│   ├── a960a5d098a324953e1c61119dff9a47722929e1.nq.gz
│   ├── aa71396a4504b6cd3443ba8bbb80f5f9be4b26b3.nq.gz
│   ├── abffe665b3b078d5e21fd53e0d73cbf8ecaa4409.nq.gz
│   ├── b4289e59a9bd86741301d6f06dd796762ac6e1c8.nq.gz
│   ├── b4425ec7c060208df2d41706dcbb695232866286.nq.gz
│   ├── b4bd791ef42b2476bcc313cca169eda3065bd6c5.nq.gz
│   ├── b818be695572d1e56fc570b506efd98e93da00c2.nq.gz
│   ├── b86ef1816441416f231ae2e0e749dc54b5cc7cd3.nq.gz
│   ├── b96bd0ea9ce41dd6728a920174a3820415a8f272.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c09bab0d48ab19f07252d1851fccac7012a6bea1.nq.gz
│   ├── c0e831e019438a3237f1beeb39f6e22d1ea6ec7b.nq.gz
│   ├── c3e5ab871949126db880afbc54e6b137e96840d6.nq.gz
│   ├── c4e3d979e32c85721a37bab013ee219863c75d96.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c7a351776c6d721e4c4b745d42d4091fc5346cc1.nq.gz
│   ├── c7e9c1453fd5df6ffef7669a9ff3b666a6438006.nq.gz
│   ├── c8d4f344a8837ea007369fa70ba25029622ba946.nq.gz
│   ├── c9e6fdde09d7d9c2ae76436d16d5b7b4502ef678.nq.gz
│   ├── ca9642617204bb5071b68815a3b85040e6cdb9f9.nq.gz
│   ├── cc98b6933cd0df2705fd39225f24282258cd3685.nq.gz
│   ├── cd2e9b3e455b0655b05a9f2d9088a47d5889bd10.nq.gz
│   ├── d1abf33538fed2f0f79ae545c592c1c09de2b778.nq.gz
│   ├── d236c784e4fadbe007ae4c5c6f5a72ec13112cf7.nq.gz
│   ├── d261a3b52e5ba2aa9373d4055ab413a9298d42bf.nq.gz
│   ├── d4f857f39a9d3f36befe572f6b674c90f2c93d27.nq.gz
│   ├── d585f438edf6cb447baed307d9f714a26bd67c82.nq.gz
│   ├── d62fc66df4b9acdd5381753fde4173a5775b1ddf.nq.gz
│   ├── d95a53b27faca6c977bb4de4d4c59c86ef99bc9d.nq.gz
│   ├── dbeefac6061fdfa4db009b4189cfcf328c3db7bb.nq.gz
│   ├── e13dd70454c36169f11fdb9e63552a52a612e78e.nq.gz
│   ├── e1686c89c658a7c77e81f4728e6bf88c2d48fec9.nq.gz
│   ├── e39ded8a459894a20ab04a16a18add1e472bdbbc.nq.gz
│   ├── e3be83ac50716b88b4e58de3417fc36512dcd2d2.nq.gz
│   ├── e69c0b4eb96ff5b14494a750f74c93e775133262.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e766c0bdb0692450fbcdce31cbd1302b6a481b83.nq.gz
│   ├── e7c7be55795792570f4ae70444777f9305684e8f.nq.gz
│   ├── e8d04f8f23dcb7e4449ebef57727513d880b218a.nq.gz
│   ├── eb9a18aa89a310f7eb8bcac49d796a7c7556e949.nq.gz
│   ├── ed1933dad9237c03f2a7829c42f48f3356d48d22.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── f47c06cc18baa434989aa2d46756a0b678957242.nq.gz
│   ├── f7b8f6deb5137f7dedf1ae73ae52fd72c9b4e8c9.nq.gz
│   ├── f7baa12a7cd948969dfa21d59e4ed547064d4284.nq.gz
│   ├── f8419667b66231179240f28bda31fc39cfa25ec4.nq.gz
│   ├── fa2abd27f4d42c3f7c6b1cb34f3b507c6f8b2bbf.nq.gz
│   ├── fdbaf74d129efad9379346eef5e280a538ac5e7e.nq.gz
│   └── fedfdd7269522f033a1cc2b1f6b077f5e9e1bdd9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d4b7f0cfd1d9b97165b010ba1fec08b63413bc76.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 121 files
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

[UKPLab/arxiv2026-prefertripplan](https://github.com/UKPLab/arxiv2026-prefertripplan)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
