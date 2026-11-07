# Repolex Knowledge Graph of sanic-org/sanic-openapi

RDF knowledge graph data for [sanic-org/sanic-openapi](https://github.com/sanic-org/sanic-openapi), parsed by [repolex](https://repolex.ai).

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
rlex download sanic-org/sanic-openapi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 872d38f2599bdeab0b5456595ab81612344a7f3d
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 872d38f2599bdeab0b5456595ab81612344a7f3d
│           └── chunk-001.nq.gz
├── blob
│   ├── 02b49151464e84a58a4657a9c237d58da398a13c.nq.gz
│   ├── 052b4c4bf40bb0f3f825918c9fe4081879f2c1b4.nq.gz
│   ├── 05481b41781ada1d62311d237612a9cb22be5516.nq.gz
│   ├── 06934909d0d36fae9fd79c30ef18a6ad517d0e9a.nq.gz
│   ├── 06e570f747b9160706ef7ea69ad57a5ba80f3070.nq.gz
│   ├── 0bd894af2060900354737d28988b910799d9896c.nq.gz
│   ├── 0ddb4c989d35b71645a101848c666ac003b30ce3.nq.gz
│   ├── 0de33fdf842e18bf0cda2a78126bec0659c6435a.nq.gz
│   ├── 10a1a4411e5f0f919e0442e12d3480f4fa090891.nq.gz
│   ├── 10e4bb28999fa87656036403c3fbaa48a6ccd2e5.nq.gz
│   ├── 122b5016b3a836bd5765521b37b2b4940d790e22.nq.gz
│   ├── 1254d2111aa975a6f1d8cd31a11dabe2a7ab41b3.nq.gz
│   ├── 128b2bf346cbf651101ca5f566257fd227370369.nq.gz
│   ├── 132c39e9d349e7dc6b2b5cee13ec732eae42e092.nq.gz
│   ├── 1377edf4cd8bd9666ba8d5145e4d974130826b28.nq.gz
│   ├── 156e4ed99ee245bf1e70040f0b168fe43d5b1b79.nq.gz
│   ├── 15e0def2499c8acfd07388469cb46b0bce908e94.nq.gz
│   ├── 176a458f94e0ea5272ce67c36bf30b6be9caf623.nq.gz
│   ├── 1991821e62ec6c517448883b616bdb8901d08e46.nq.gz
│   ├── 19fdefaa32c212f760e8eff0520a4f13d209811b.nq.gz
│   ├── 1a03a7b6c4911d25a0ae237e496971b25ff6fdd7.nq.gz
│   ├── 1a715e6dba4c755330eb310c89dd7920edfbc5bf.nq.gz
│   ├── 1a9e4422654c0b2ab424471ea74ea5bf46d9f118.nq.gz
│   ├── 207d10099e8a5444a015cf93a8f8ec3f5ef5d8fb.nq.gz
│   ├── 2267bfdc928d3f8ddc58db6c4c9f8f5f9ea1e3d7.nq.gz
│   ├── 242e4376c83fd72d01418ee3cee989834283a1fc.nq.gz
│   ├── 248e543f4212397da7280e42e804481fbbc640c2.nq.gz
│   ├── 249737fe44558e679f0b67134e274461d988fa98.nq.gz
│   ├── 2842844723f8d9e3fd1b84f0cfbe856311db8fcf.nq.gz
│   ├── 2a3e7bb6424cac8c319e8123fe0a9fa4e43a5c5b.nq.gz
│   ├── 2b014cfd95acc970acba160a8a004b83f033a60a.nq.gz
│   ├── 301d44bb69ef35f9c9408e2c89bf3a53c484d0f1.nq.gz
│   ├── 3029fed3efc1ce0efcdb1c8aeec39ea357502161.nq.gz
│   ├── 30cbc5be87282c54e2a3149c70c7b907be6f2b16.nq.gz
│   ├── 315b9a4c8e4dd14b331e28287d15b83e266cc484.nq.gz
│   ├── 326f2c181f120f340c3511b71721760bdefecc79.nq.gz
│   ├── 343d6628add694b328bcfe262155a3f798bc245d.nq.gz
│   ├── 35d8f4f0c02dccecc73aa2f70b556fb916b574af.nq.gz
│   ├── 365731c12bd21860cee3166cd4b72a30f31e2dd6.nq.gz
│   ├── 3833e4f5b95a99d308668f3c5a21fb9b7ea52177.nq.gz
│   ├── 39261df0532116e0e18ca6a6c08b927d5781f442.nq.gz
│   ├── 3c49d92772cd25f3bf2763aa0ab26193fcd0e0c2.nq.gz
│   ├── 3c742702a7e21e0f6afb84e80fe0be747e2601fa.nq.gz
│   ├── 3cfe09b5304e2f1d44e04fda2342b6b2f6b70242.nq.gz
│   ├── 3d92710a876a88c8d40e22523c1569a4a5331434.nq.gz
│   ├── 3e1c428f9d48a1c7118cd71a546b0bf09332d147.nq.gz
│   ├── 3e332883a1d624554d64b79612b79d14948d3228.nq.gz
│   ├── 41c8f177cf1186df9d0e65ee26228662a9d1b4aa.nq.gz
│   ├── 44e64fa2f4d9508d272ecb4a80c378cb8dbc53a9.nq.gz
│   ├── 45f8d08a039610c6122c4f5772a5e6a1a8474248.nq.gz
│   ├── 45f9567c8a2af11816250700a514ff622dd75d9a.nq.gz
│   ├── 46a2a205cd423aaa216ebfeb4d8a92bc44bbc4c8.nq.gz
│   ├── 46d3b950833d4bfc052266646852ff10bb884684.nq.gz
│   ├── 4b39a0420c694022a814613c2fedea5f4ea2b338.nq.gz
│   ├── 4beab95fa11899ae25567bc8b230f2e5bf910b73.nq.gz
│   ├── 4e306fe5d78ac3995f4b3d50cd68d14a522d905f.nq.gz
│   ├── 4f0549ef626693720ff2aef3a099d9bcbf5b93d0.nq.gz
│   ├── 51eb80e568db94afbc136f517a15c7865dd5fcec.nq.gz
│   ├── 5324f9bbfc5f9a5d84ec26039053d9073d74904b.nq.gz
│   ├── 5420959e6d641f9a188bcd991369ff91a9be6b18.nq.gz
│   ├── 54f6bd0e697cea9daa8bd75053edeb9af957b57c.nq.gz
│   ├── 577b345b36899ad3c28b3ade250c4460e6f28647.nq.gz
│   ├── 597439ed02755c8c7bad0396f112ca060964ab1c.nq.gz
│   ├── 5b05640399920aae624519676786d45a5b2d57e4.nq.gz
│   ├── 5ce28bad554150bcb072ef1564b9210c05378982.nq.gz
│   ├── 5ced150f0684a1c1460c81aeeffa4d20d114b517.nq.gz
│   ├── 5f51f9d87f15b2c1ae34e24537f157da59a59a7d.nq.gz
│   ├── 652f6bd765b1e0ac64d96109b3109027ec3a85b6.nq.gz
│   ├── 667210d0c5a9ed37e00c8aeddd02c7744ff80ce5.nq.gz
│   ├── 69561e216f5fcd65baf89a2290132e1a22f042c1.nq.gz
│   ├── 699df12cd289404c38d18bf1ba86702b862f69bf.nq.gz
│   ├── 6e698965b03a94a887e1d0b0095a7385c157d6de.nq.gz
│   ├── 6f1fa6a41db007ecb9c00b01438cda2f277802db.nq.gz
│   ├── 70e418338e108df45eeb00d6b3908e4077fcee99.nq.gz
│   ├── 71a9360d058d4c084e4a19744ff60e7a1d142b52.nq.gz
│   ├── 720dfc83e6f4f4cf792a11a8ff4e11704cd7941a.nq.gz
│   ├── 7230a7cde37de176b635506ef581649c074e6516.nq.gz
│   ├── 72f1b901111a2a8083c7c29582ec6ec2b5702380.nq.gz
│   ├── 7643f5066d283b5ab1a0539994379b5cd11e6989.nq.gz
│   ├── 77479ae8c677bc71d59e3c03974af15adf947420.nq.gz
│   ├── 7747c5f4e0ee5fc43c098ec568f64634757a0556.nq.gz
│   ├── 7a2e0d32ec13eada7a8495122f4e75d8dc81ac36.nq.gz
│   ├── 7ab6b8afde6df51f183d1d2ae2de4be46ac606bb.nq.gz
│   ├── 7b6e32d0afcb2aa18475b0afd3c362bdc01103c2.nq.gz
│   ├── 7e3205e200f822c4f0c64f327cd58e5a5f760609.nq.gz
│   ├── 8210251fbf285fa0c41eae0294e3fa1d2780fd41.nq.gz
│   ├── 83159eec9aeace367a42af0e88a488b2b6ab6934.nq.gz
│   ├── 872e5f27ab7d150d4cc510395c17625a08cf3964.nq.gz
│   ├── 8878a99101781dd1b053286b2b1dea5184eb0de8.nq.gz
│   ├── 8a2dcb1b157fd071f8baebc2d3581b3fa6acaaa7.nq.gz
│   ├── 8b194e617af1c135e6b37939591d24ac3a5efa18.nq.gz
│   ├── 8beebe7f631f265c9ac18507c6c132ce71cd260e.nq.gz
│   ├── 8d0a28675d177ffbdb4d2f749210105e76767995.nq.gz
│   ├── 8d552af4464492fecb26055620011cf9bee724a1.nq.gz
│   ├── 8ed85a93049ab891f073c2f9bd72a174a07a0596.nq.gz
│   ├── 8f6bc50d200681a2e2c1eeeed0044ab7faa9c477.nq.gz
│   ├── 90fca6d352f133fb7d6fd192e8cd633a347e6cda.nq.gz
│   ├── 91af4e4cae81deb095587bf37a60014a3902b688.nq.gz
│   ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
│   ├── 95733571e9795b51269953bbd6bf90ca4da05663.nq.gz
│   ├── 95c0d5f61738f719942ba17b4278f9a403ab7435.nq.gz
│   ├── 9603a7eda7ecfc90061fabe9a4c35a5cd07f1e1c.nq.gz
│   ├── 9a69ea175f439cae9018ba27b9dd1d1cf8f34f5c.nq.gz
│   ├── 9d116b0dc7cf13f644d3bb7e86267d04817612a9.nq.gz
│   ├── 9de790adf78dbda79492a0497a8c5ab389714ceb.nq.gz
│   ├── 9e0e6c016c93fcd62c2cb2eb1808d842d71ad244.nq.gz
│   ├── 9f121ec1708c4d19c87583c6afbda311a06e1449.nq.gz
│   ├── 9fc0ec5b050d4554f2ae647c4c65523f4730349e.nq.gz
│   ├── a0ec65fb115fa72bcd2c1086f408c6da2c736d1b.nq.gz
│   ├── a27c9816714d44d7fbfdfe619baef14aeaa6a72a.nq.gz
│   ├── a30dcae4c295295ce769cc8531718978b9664d31.nq.gz
│   ├── a4b9c5b56717e3477340294b952620f5e7453a18.nq.gz
│   ├── a63582e0b1f09506d72ec1658b33b3fb0e9706c4.nq.gz
│   ├── a704c5bccba317d6e9d263e8e28893dbce44d8a6.nq.gz
│   ├── a80b807c5a9be69602682843e10652b0319b7e74.nq.gz
│   ├── a870a31d5f6652a5ffe652265b95998173aa82d8.nq.gz
│   ├── a9d4681d3e4c202e0162e9f8dacd5407529d5474.nq.gz
│   ├── acc566d368b206c7cf70ae914a2fc7991dc8dbd1.nq.gz
│   ├── af75670b6ef79510b2dd942a4d29f445d8b45bcf.nq.gz
│   ├── b0cb2001d81fe8a96e8a96556ace7373026c985e.nq.gz
│   ├── b2b9ec5cdc515a4db1ea6ee0b295aecb9ed7310b.nq.gz
│   ├── b2d99642cea7252c9bbfe23f12030b9156f3f2b5.nq.gz
│   ├── b45eb36cbf8bf7a3d77f33a7a5cd81a621bc8519.nq.gz
│   ├── ba1e38015b1691d7189645a252c390584decfd12.nq.gz
│   ├── bdd9eeb85ba1506f69fdff05bf9a8236c4be856f.nq.gz
│   ├── be1f6680982acd229462d92a89f6ad4df19210a4.nq.gz
│   ├── be84616da4db4f1d7353654bc3c144d012ac5b83.nq.gz
│   ├── be8965265de831a11b2070c1e89f0c13db024500.nq.gz
│   ├── bf06bf4801bd61e72f9698f6f686ba2e4dcc48fa.nq.gz
│   ├── bf74382fea9f8905c3a1dcdcb906608e40f133fd.nq.gz
│   ├── bf9b0fb3d5438f6c52f2f2a8d8783c3ca5cd2d12.nq.gz
│   ├── c23ac128b3e50b907857c6b39ba90748d1b6a872.nq.gz
│   ├── c2e3408f2641644f9ffde7526661c9c437247e74.nq.gz
│   ├── c3141290b6e7d6cab69e0b2b6dbeb3a95d876aaa.nq.gz
│   ├── c7f1f36f7cacdbfa38fa4f42e6ab47a631b91a77.nq.gz
│   ├── c887e3598a28f088c7bc2688f5338528c3cbebca.nq.gz
│   ├── c8c6bcc8bc5618551f70196c8f8fffc0542d35d3.nq.gz
│   ├── cdccf4bef8c2e3072d888bf6bd0fcd6fd4493e9a.nq.gz
│   ├── cf7fe3a4c7f633f824fd81e259f75eff6ed8e9e6.nq.gz
│   ├── cff498634421c8d10fd37eefa8d4933484e29608.nq.gz
│   ├── d1b9093f82d818ff1899069cfd27e7c9bca491ca.nq.gz
│   ├── d450f9ddab7557e70723bac52417c6c83959c859.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d60880f06ecd09e968670ce9846827b1c29fba04.nq.gz
│   ├── dd542efb040085f94ef52b2c752387441550925d.nq.gz
│   ├── df69f4d36b71575c6449e3546047c3f9f58513da.nq.gz
│   ├── dfe2800ebe64234b1e30300745571bd54da3eceb.nq.gz
│   ├── e1a37607f31fa68875b5f7a250f6a592c77aa88c.nq.gz
│   ├── e6a0854287a4d0913300131c5718f8ece1157403.nq.gz
│   ├── e8a46828c47cfdc40e9efea150856acbb07d6022.nq.gz
│   ├── e8a8609982a22ef64e640dcddab2e907888a5a55.nq.gz
│   ├── eb185571efc87429c4bd2f6264869910854e2bd4.nq.gz
│   ├── ebb57dc26db7e45af5430033d5fcb3319e674e48.nq.gz
│   ├── ebe8a8ff9d8ccaeb88f938547e380b6146d278ad.nq.gz
│   ├── ec5c9e301f261b7155ffbfd2606e8a526018b7a4.nq.gz
│   ├── ee23c753dffe81c77434293f4c92da554a63586f.nq.gz
│   ├── ef602c1da7d291aceddbc8dc2694782d3c1a7a10.nq.gz
│   ├── f0c5d3503cea34d3729c5aaa0f80495a206c7cf0.nq.gz
│   ├── f1117cc10fac1b031699622bde79fdf81adb4dc5.nq.gz
│   ├── f13746778c37e2cf61a3c337e4631b5580c41e38.nq.gz
│   ├── f181c1c51142e7ed3f5513e6054faee3432360b1.nq.gz
│   ├── f2d888fabbc14701e1fe778e39c53ae4d6b1a2cc.nq.gz
│   ├── f3b875a7df6061d484b4f5d5bcb63b6e98357990.nq.gz
│   ├── f579f4d044a3b7e02bbf552bef5e5424e6302262.nq.gz
│   ├── f58d21105c01b1f039d7ea262beaaaefd0f67f6a.nq.gz
│   ├── f66fe4819ac25d026adb0870cfce80fe7dd12450.nq.gz
│   ├── f7b5de41baf807104cfdb838670cca6f6ce88fa6.nq.gz
│   ├── fcce84be00092ad71473c7fa014af206c98131d4.nq.gz
│   ├── fcfc9dc11e4e3b438f09b7fe4ff44e02f28cb3d0.nq.gz
│   ├── fe201ef9af90ee7078602794bfea8396a09eea97.nq.gz
│   └── ff38a5daa98b97fb420a06d4613adc9373de56b8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 872d38f2599bdeab0b5456595ab81612344a7f3d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 180 files
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

[sanic-org/sanic-openapi](https://github.com/sanic-org/sanic-openapi)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
