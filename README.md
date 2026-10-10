# Repolex Knowledge Graph of astral-sh/packse

RDF knowledge graph data for [astral-sh/packse](https://github.com/astral-sh/packse), parsed by [repolex](https://repolex.ai).

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
rlex download astral-sh/packse
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18be7766b14aa3e03db37bc575959b3f4c6fbacb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 18be7766b14aa3e03db37bc575959b3f4c6fbacb
│           └── chunk-001.nq.gz
└── blob
    ├── 001ae7b83a343cd492149f38d39501fac2d6c888.nq.gz
    ├── 013edf7450b5d48af4baccd38941e56b0bf7a17c.nq.gz
    ├── 0342a0ccd6d8365e08a8b724e39f6f32d2987baa.nq.gz
    ├── 036b0a0138e41142275e08cd64de22a6ee92468a.nq.gz
    ├── 03c3fed78ab7dbc4864fb7e0892b69ea5be78481.nq.gz
    ├── 0478f08906ab5ca90b25c511336840e2fa88d7e5.nq.gz
    ├── 0637e4b7ca6316c5c538204a32a3c5af61710eb4.nq.gz
    ├── 063c79491a829b4354612f5a9642f03a9406b2a9.nq.gz
    ├── 075c869c56e04afad98d09bd50ac8dc6e8121625.nq.gz
    ├── 08b8a9798a47600b68a7dbb1f30563315a94ed5a.nq.gz
    ├── 0a690322a452d2da8990615bc9823cda6cd055c9.nq.gz
    ├── 0c646b3905869d058cd76574cdf6dc74dcabf08e.nq.gz
    ├── 0ccd75136b2981f88a34fff90e2457a8e3fd1c17.nq.gz
    ├── 0d7a8fb2c40957be06b5181b2a97898d36dc95ba.nq.gz
    ├── 0e1c24c1e9c0be46604b57f3ef3a6efc1711bdba.nq.gz
    ├── 0e63ea4a1c09a9d918da6f9754ad05a2625a1d42.nq.gz
    ├── 0fba514ab8c4f48753719a20d873a0ab681856dc.nq.gz
    ├── 0fc4ddd17914532adcf4d2104b9eb7a1f83c7a1d.nq.gz
    ├── 1076721a62619862b8c51fcbcb5f3c9ba632cba1.nq.gz
    ├── 10a4874cc1cc935d1cbf04d16af2ff604296ba4e.nq.gz
    ├── 12b38fdabaf51f39b64b12e11054c0b9c776679a.nq.gz
    ├── 12bc128c283ca1b8d04e4893fdb5202846ff66e5.nq.gz
    ├── 13443f79238e5223892fb061a3cc1265ec5cea7b.nq.gz
    ├── 14933ebffddace175c67f596b9b0b20c759a4079.nq.gz
    ├── 14ad87ca7cb9109158e1b4bd5aef7cfd134fec8c.nq.gz
    ├── 172aa818c0ca77794457e17017a6d85c816b7408.nq.gz
    ├── 1804c370b552d8759cc671456ee29ab9cd7dc0ef.nq.gz
    ├── 199c267a82a50b480bf858704d1cf0a48d6a6de9.nq.gz
    ├── 19b48e3db5511cbb1cc8534d3afe94e754688740.nq.gz
    ├── 19d0fbbe7bae33493601e77ad7c14beb6441bf9d.nq.gz
    ├── 1c72792063a497c2c96b7c27457bbc0c880a7e42.nq.gz
    ├── 1d22292db3d170a0a978ed47edc8830b9dc4c055.nq.gz
    ├── 1d5661e66ee676c10e00da5f8b7e35883c3a464d.nq.gz
    ├── 1ed33341a8918ae76cdc895d766b17147962fbdb.nq.gz
    ├── 1fe20d66e2fb8cb9bad4d0f2d1485cb5b04b7501.nq.gz
    ├── 20263756a4c6562e40c2f00aaf556fc7b127c85b.nq.gz
    ├── 220a191b9664eddd42052784527239cdce0a3880.nq.gz
    ├── 229d8c9d24fa62641869b42873db97bef2b51eb4.nq.gz
    ├── 235eeee9a388f248ad81f289b71449828c008096.nq.gz
    ├── 23c44b3f16c8f7f455abe25acb101743366c04df.nq.gz
    ├── 24d81314de43c3643f4eecb04efbbdca7c400de0.nq.gz
    ├── 26988918a5b1f754d91263c6f3059c9dce5dca1b.nq.gz
    ├── 281970204644be49ea01e9eb77465ed63b75ce88.nq.gz
    ├── 284a637330527ef1299d7b530409636ea974f80f.nq.gz
    ├── 28f66a04da82f547f07bce8e3992eb7310f92dd1.nq.gz
    ├── 293ba8625741eb72389b1da02ed5961b27c038ea.nq.gz
    ├── 2ab72aeddd67dc59bcb60ba041c87ace866deabc.nq.gz
    ├── 2c443824ad4e01a302dbe55dbd3843977f5b9b21.nq.gz
    ├── 2c8a7f0bd69b5aa2dbccbe5d6b91de418d5ed1d4.nq.gz
    ├── 2c93a5d864e7e6c46d8db348654ef87c9d2bd79e.nq.gz
    ├── 2d5e92e3118e76ad334448e5bb5a44a398a2c6aa.nq.gz
    ├── 2ffff88712b373bb167e7b8b5514b5106b652813.nq.gz
    ├── 324848a99c09460a8adaf47fdc344b47909d1891.nq.gz
    ├── 332a5a4fb59adb22a0b66e411c686c97dc334310.nq.gz
    ├── 3492a8159e80830b2b49f80c2a757c57fcd7aca9.nq.gz
    ├── 3577b0207f0c1cd8fd1c09221c6c15974f14e7b1.nq.gz
    ├── 35a6bb2c99cbaa36a1b7fab9895b8561b7813ee7.nq.gz
    ├── 35ddcaa5d88b4608a56156700fe704a53cda749e.nq.gz
    ├── 375b1308931931dae282515777aa729f416b977c.nq.gz
    ├── 375b14ee22e2fdaf1235f0d813033db5e2717662.nq.gz
    ├── 392d51a6be5500e1fa9e4746e9519efce5111a27.nq.gz
    ├── 395c109ab23fafbd9f6bf9630206807c96f03040.nq.gz
    ├── 3dd1c1471851e10717d9ca004e2af571efc4b064.nq.gz
    ├── 3df108d6d35ff5bc2f0a33720e5a7544904adcaf.nq.gz
    ├── 3f0a3d5d2d114bac85998f32b0ca821d92c60cfd.nq.gz
    ├── 3f9b32f7209c80743a9997691b6ff990f2d92d2d.nq.gz
    ├── 4019066912a1169fcba2fa43e5066620a5b91553.nq.gz
    ├── 407deca81714e45cd6b46ad1f13c508cc7cde13b.nq.gz
    ├── 410ff39b30d1addf8af5cc9fb5d689018f3c7cb4.nq.gz
    ├── 4217bd4a2d5158ab6f9f38840faacfd525b1c3d7.nq.gz
    ├── 42f065d42cf48d5075be157a2b0c9cbb5fdae14f.nq.gz
    ├── 4650a461b3db8ea8b602c594044706b26f774632.nq.gz
    ├── 47295a7d074f9b82fe6da8b89520450d65effab3.nq.gz
    ├── 4885889ab29eb2e14dd765bf284d7e7bdaf3bd22.nq.gz
    ├── 492fabc6dec0f405bbe3448d8ad953292c58040a.nq.gz
    ├── 4c8e7e367ce0890d3995759b5a9b7b5e4d2d953e.nq.gz
    ├── 51124ab1bc8109b3843e0e1e54701f0443716b1f.nq.gz
    ├── 511892dcdd3b8f2a8ad05bff9dcb33a0a742852e.nq.gz
    ├── 51aae438b1f47583761eecf0a4eda9605bc8302d.nq.gz
    ├── 52b573a3de6914451ed2a0375813673865738ebf.nq.gz
    ├── 56fc546b5d850cbc6bf22862eb669b8dbb52e310.nq.gz
    ├── 576ff5ccb2b2a5803412f722a9b0edf292d4ebd0.nq.gz
    ├── 5d208b06adbbb066ff2643c7357b4cfd996e426c.nq.gz
    ├── 5d3961616960307fda0db804d7c512cd464dc121.nq.gz
    ├── 64141058631df8e3542d2c6ad3764d40a3d5870c.nq.gz
    ├── 64b45e95c9a5c3aaadfd79a9b567b39976af151c.nq.gz
    ├── 6554650ca8f939120c9ab2c066a3560704b481c8.nq.gz
    ├── 66b5e2677977b1f9c49fa227a739a5fa6e120c11.nq.gz
    ├── 677407a7d174e51abed37c40495f693d59b85fda.nq.gz
    ├── 6ab9c6714e225252e027f552bdbb0e30b488f9f0.nq.gz
    ├── 6d5317155cc6f7392cc0654d0480449ff47a80da.nq.gz
    ├── 6f26a62d2f0982b9a690194df8cada5fceea5574.nq.gz
    ├── 719960db0d61f91d9cc80b28ace69c51bea6f44d.nq.gz
    ├── 735c2c623069dd0fe1b9dcfb42e167360c6fcef6.nq.gz
    ├── 73a5a4f0c6c1ac11d5f5762b13cbe45e54b995c2.nq.gz
    ├── 75f08c6ab414faff941b491561a78c211c49a41c.nq.gz
    ├── 77359d79a28c3ddcccbff547fd774f06696fb4c4.nq.gz
    ├── 792c25bf080acc9d988a483e50111b5eb9501f04.nq.gz
    ├── 79704c31f3bdd33678e4941771d925b506fc4cdc.nq.gz
    ├── 7a5d6fffa07005945d6a4febfb5aac877bc2e41e.nq.gz
    ├── 7a966c6e4e9316584ad60ee6d5e52c27328ad405.nq.gz
    ├── 7c84007033b36c793fb8d22b8c6f2ba5f4194255.nq.gz
    ├── 7cdc16f30d360fa4c6ea1ab19ee39dbf1a9f2110.nq.gz
    ├── 7d7f976b8d43ab1ee673af7c2622f8b1d8df2d51.nq.gz
    ├── 80c34babc46ac94b0f27994d8cf18e60e912ec35.nq.gz
    ├── 8133d224eb5ffa1d8afd9218d10c71725b02a203.nq.gz
    ├── 814eec721e82c183fec6fa838f83a7f638fcbec4.nq.gz
    ├── 81cc05913af6c29d5c4d74de574deda9d04190c8.nq.gz
    ├── 826d3a7280a4c119680badb9e3d3666802f67077.nq.gz
    ├── 82f84ce78c4721a201ad91ec1030f813dcb0a610.nq.gz
    ├── 8486c2994888980bfff2c373a47696ff13d44f88.nq.gz
    ├── 85e29f255f1cc918bf1f751818caad6ba9c4bf96.nq.gz
    ├── 875b3332d30d72c2414e8383847d83ab7976a3e8.nq.gz
    ├── 886cd54f8c434b0079e95f8430c843738a558a60.nq.gz
    ├── 8d35cb3277ff6eb0d637147c09e95934604a431c.nq.gz
    ├── 8d6f10f6683072c9c81985995ec9407d90a67188.nq.gz
    ├── 8d7b78265dfb0d0a012c7f69996122b44ee7e5dc.nq.gz
    ├── 8e608a93d5d68ebc5df8836a980b6259dceccc5c.nq.gz
    ├── 8e7b21e04e296a22d16f4ce31d9eaa6b6fef8155.nq.gz
    ├── 8f1bcacb1e2f318c7cb969e05f5347c5fcac31a6.nq.gz
    ├── 8f645daa5093186e0a85344424efb8f88e1e0949.nq.gz
    ├── 9094d18373c583c588287f9ebf0d92eca5d8a215.nq.gz
    ├── 915dd4d08677d80363cb34eade9f69b1b6bc357f.nq.gz
    ├── 92d360e2f1293506195292e99f2ee8a6d632c738.nq.gz
    ├── 95701722d388808587b8c648aac148143f1debf7.nq.gz
    ├── 95cfcb1f463d5f82e70b88d023a567a461ea45b9.nq.gz
    ├── 97e3a1e35683cef6e1e38b21274673c0e2798fdb.nq.gz
    ├── 97f7043268d3dbb6b5b5fa734e4da59d2359c5cc.nq.gz
    ├── 9abd287e34ad7a1af55a7c06123f81f229bcc72c.nq.gz
    ├── 9b5d28cba39d6f81c7082c3ce2a4c511a602fce2.nq.gz
    ├── 9be759f6fb5f2f517d70a364e9bf08a4bb891771.nq.gz
    ├── 9f4481fee3d6c452094ae36a524335c3eeaf23fb.nq.gz
    ├── a0b8bf4f2d5ee40fb6bca64738d543af9a3ebf1a.nq.gz
    ├── a2049b6ba0e30d95da9cdcb4d3263045b57b722d.nq.gz
    ├── a24d461b745eb29145f067bc4f6acc7b4a32a70b.nq.gz
    ├── a3f12979c3d4974846ec3c8945ada1e2589540c1.nq.gz
    ├── a5d31897ff8b56599a155a6b0caba33c87820c12.nq.gz
    ├── a9279468891fa212e9032ecc2e1b4b472e58031a.nq.gz
    ├── a9847c196b237600264308549fe4cc616044e85c.nq.gz
    ├── a9bc3592326ab61fe0538f7140a7881630a188b5.nq.gz
    ├── ac07da46e0a746f1600e854112b4b70656c6f95d.nq.gz
    ├── b03335b6228fbcc4f12e3ad4fdd852fd1910bbdd.nq.gz
    ├── b1de6a1ba63d4c1d1b35bcd51240df498aa91390.nq.gz
    ├── b2162e019316117348662a86148725f5e3570ae4.nq.gz
    ├── b240a4647bedecc6e9397f8bf08b75fab873f16c.nq.gz
    ├── b2e72d8fd323eee4f1b43c3cada91e9942abed36.nq.gz
    ├── b529642bf5ea793566da694eaed19acc5df4bedc.nq.gz
    ├── b690544c6baaaa9a8a3f82cf86f2fa433300888d.nq.gz
    ├── b6dd2ae5ccdf516acee77b1ab7b0769d5612f5a4.nq.gz
    ├── b9a005aa7f7077fd4b327feb1418896784c5fab0.nq.gz
    ├── b9a54213a27e49965fb24a5ab5e950ac188b43b9.nq.gz
    ├── ba1db63c47a8a9bfd5f17a1b854e860a30c5fa72.nq.gz
    ├── bc697e9fabf13220f7cda94601c095db9ef04899.nq.gz
    ├── bcda82754a1da85fa088c8c5cebb912c332ca121.nq.gz
    ├── be6ace0f4d8d6446ad4b7af9542e293ebc5ddd50.nq.gz
    ├── bead9a54274651452879958240e26d4e0259c620.nq.gz
    ├── bff6d03e83e27f7877e386dd3de91db8da9a88a7.nq.gz
    ├── c023fa82c8960b30e08feafec266e2b3124c1548.nq.gz
    ├── c05bc7218d6358715dbc73ccb6181919c7344b07.nq.gz
    ├── c2b35031b893a117c8be6dc716cb9bfb33126357.nq.gz
    ├── c2eb78a3207ac209fd1ac4754c2c2c4817d24fb3.nq.gz
    ├── c39abe828aa5fb4e8dce8dc0587e5a2466d869eb.nq.gz
    ├── c3e43951bae8c12bf3a964077249def40b8b0414.nq.gz
    ├── c62e2a96ec9323f93d4e239fcf75196e6f7f4731.nq.gz
    ├── c65b6851f71fd918bd82da6e045af7d385aab547.nq.gz
    ├── cbaed09eceeb8f8af73ea6f8ef8418a41b764f40.nq.gz
    ├── cc66787830ddf213352681ccd85fa863650a585f.nq.gz
    ├── ccea44c70e7bd53546a2fcf4a7d28c52644622a0.nq.gz
    ├── cefaed42170b67ea44d1b50957a7472b8de6c5dd.nq.gz
    ├── d1f8bd5b615ad60fa63f418b45429efb76186ff5.nq.gz
    ├── d24d42f956f40f70cfd771dfb9a4720150576963.nq.gz
    ├── d3e0c00a30a8526f4239e810cc114b346cba5fa6.nq.gz
    ├── d6531c8c490d1408a0b8706fc2e39ed0a1f39500.nq.gz
    ├── d89eaa479e415ed82e5e0ba7a03448bd3f5860cd.nq.gz
    ├── da09e9a3122dea02acbea4d763cf04acc974b081.nq.gz
    ├── da7219cf86aa26602eca456c69e49e9c4a9a202c.nq.gz
    ├── dafd2bf4108bbcb26c45d16abb3667202bd10c7c.nq.gz
    ├── dc08e4bca8504cd741a5d09262d223beed63e18b.nq.gz
    ├── dcfe62da24f7e8d96596068103a912ad52240542.nq.gz
    ├── ddc5da7d80fac2ae3e0048fd501a7b79804985ed.nq.gz
    ├── de4957bb979125a9de2e06fe251c1e12a54f8ce4.nq.gz
    ├── de7ef552b5701a0369cc60a3c3cebbb545856e20.nq.gz
    ├── de808d48b9d00326d8702b69eeba24583c698d95.nq.gz
    ├── df08ab73cbaebb1894959dc9991d002a098e9a8e.nq.gz
    ├── e104f17c0fc79dc3923762d3b9239893d1512665.nq.gz
    ├── e1413e3759a83e13f08667059c3d23626121b171.nq.gz
    ├── e214eae6193e5c7b5a975f68ca21bf910beed65f.nq.gz
    ├── e4e12f84d8f75a6f7ac29707c609def277b2c111.nq.gz
    ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
    ├── e660f915b8de897454edf549418ef0092200e5b2.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── ec2236bb89949a3353f85b9884c2c453b7ebe36e.nq.gz
    ├── ecbe97a9b9aa2828172a09583b1420c5e28d2b79.nq.gz
    ├── ed189eb8aa5dc74f18ac0d4dd6b997482995e37b.nq.gz
    ├── ed38f310cf75a5e546ded575b844edcbf74e2710.nq.gz
    ├── eede687dddf6980f6e5ed51528dc529e68fe7811.nq.gz
    ├── f1705e5a366392b63dddd609a3dd25549eb1140e.nq.gz
    └── f1a082fad332c06c37d6cc59c7ed52b0c7507048.nq.gz

7 directories, 200 files
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

[astral-sh/packse](https://github.com/astral-sh/packse)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
