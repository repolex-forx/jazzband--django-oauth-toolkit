# Repolex Knowledge Graph of jazzband/django-oauth-toolkit

RDF knowledge graph data for [jazzband/django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-oauth-toolkit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c6e1bd28349149b7da14bea847c3cbd4577e534a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c6e1bd28349149b7da14bea847c3cbd4577e534a
│           └── chunk-001.nq.gz
└── blob
    ├── 00e738adf58680a6e3da25610e6e72a2ba1dcbe0.nq.gz
    ├── 012df950f055919ff353baca7646a0b4a1065108.nq.gz
    ├── 017e50ddff4e49cd0fffa568bab9b3dbfe873165.nq.gz
    ├── 02e9dd4adc6ceee24c40f69e869a1b9faf2665bb.nq.gz
    ├── 030ccc665a12e10d4e8f3ea1ecf87bb596f76876.nq.gz
    ├── 04040d5d968d4c65e762afe5cfe30f29ce2cbe96.nq.gz
    ├── 04374e44c8a6ebfc6506492924d32b2e07187986.nq.gz
    ├── 04556b783ecdff1d76b0c7d16f529eba07eccc8e.nq.gz
    ├── 04ad9b443326fe9ae2747050d93be89331d9a80a.nq.gz
    ├── 04fc6609c0dbad7dc8c7beda561ccea956353735.nq.gz
    ├── 05bfa8c5b236e8cc9193c09500ccbe68e0d039bb.nq.gz
    ├── 0841996212f0374251a0e137282ad07f6d251a57.nq.gz
    ├── 08530aded7e12d1c34c8b586d54298ac146bbab3.nq.gz
    ├── 0a2b2b12cc575473395543f69c7e4db7f8fb4d17.nq.gz
    ├── 0aca3d090ef20571360d3e194cdd5298b1c56488.nq.gz
    ├── 0ae5e509b541136c85b029f1dd3160b3d2138b76.nq.gz
    ├── 0b51e5c2219bd40051bb57db8259f62506f5d3af.nq.gz
    ├── 0bf53d2553f23552f36741f58fd759b9cc35a476.nq.gz
    ├── 0c05da457e450c0a6fafe36006e17fa39abc899b.nq.gz
    ├── 0c36b3028dab28235433a726416b2c364bf7199a.nq.gz
    ├── 0e1922536c8112e892c1e9d72df3f99b363e8581.nq.gz
    ├── 0e4068d4cc72635a9616fb1eab678180b5d7be13.nq.gz
    ├── 0e4a60229eb7456d77f9a11bb8222bebc672732e.nq.gz
    ├── 0e6d0ccee87b08a065ef42f02e91bafa7d0db6b5.nq.gz
    ├── 0eaddd595e8c7f9b8ae5f9daeeeb85de20003c9a.nq.gz
    ├── 0f1f6d86d2f83235e804cd9a7f87a1de6c62f174.nq.gz
    ├── 0f332e8c15c9c8396d309810b8ccf39bc96a959a.nq.gz
    ├── 102e40cda75c905e9b0c01404516632bca3ecdbc.nq.gz
    ├── 1045133ea28d7eb839f7135a2bfd74259331b1c8.nq.gz
    ├── 104a7b3bcbe36d2caab87552be568044b3faa8a8.nq.gz
    ├── 106ad60d55b1092d2cf3b6f993f7c3103ab8426d.nq.gz
    ├── 109e8377074493aaf3b84bf7e92fdb99fa5b52f1.nq.gz
    ├── 10b7743df1cdea4e36bd1167ba692b703745e02f.nq.gz
    ├── 111596df4c858ba77d7f2cc841dfd545768577f1.nq.gz
    ├── 118e4a04bf97f5955c0d40adf536ff75fc1f8b5b.nq.gz
    ├── 11a0645925d47717be21337bb669482e182e855d.nq.gz
    ├── 11e8934bda087f2f8c7b9eca5c358fa32a013460.nq.gz
    ├── 12e7dd0ae68a4d9415f50108de751f1f212ca2ea.nq.gz
    ├── 130950407b3dd9633a56132816865a582b513d7a.nq.gz
    ├── 13485f4a1fa3d550e967cf9d3a9799a22a3eceda.nq.gz
    ├── 1393963c626a7d14d62e73320b86eb982e328c59.nq.gz
    ├── 151acf36c5f4553d1881792446b198e5e5f330a1.nq.gz
    ├── 15f7022a96ac32ac65e35ad099c1bb08efca0b2d.nq.gz
    ├── 1640bda03fe7eb79c2eb82fe5f62a4c4b1a90c3a.nq.gz
    ├── 167a8474364289b637719ac89b15c76076dafba9.nq.gz
    ├── 16de154276b9abcce59ec9affcbaf216b55a4306.nq.gz
    ├── 1704ec869cec0892201b7de5255fe29d1546be2c.nq.gz
    ├── 17bf54fa954fc07b480afe179cb9f742f6dd1fc5.nq.gz
    ├── 17d0d306709f7a2dad3e7a093f0014b00c43e6d3.nq.gz
    ├── 198b5db0aec16b2ee9346b346b063e991c7c4f34.nq.gz
    ├── 19c4dbe325e3ffa792174d5b7eea06ce5001516e.nq.gz
    ├── 19edc78a4a6920c79c0dc2c8d26f9f177a609135.nq.gz
    ├── 1a43d4c51f316276f2853778a8ffe0376dadf02a.nq.gz
    ├── 1ac7bc22b87a7aa88d0308adbef46b72250bcfaa.nq.gz
    ├── 1ad7cea4cf34085236fe5d89a474b4d29b8fde83.nq.gz
    ├── 1af7e60dd51e71342fbcb078ba385832ca7af1bf.nq.gz
    ├── 1c1551eb3435ef20f184dd4bb489dac7ae2d7422.nq.gz
    ├── 1d17b3cb3c0442a6b7d9850c7cebc0cd4ac29176.nq.gz
    ├── 1d1a38e0e160ac11fc9a006c50591e8451c5d586.nq.gz
    ├── 1dad932a9f07c832858a0d3953cbd6be50ae134f.nq.gz
    ├── 1e2657ce7e1d3cbe74851af06ff76cecdae695c9.nq.gz
    ├── 1e6bfdbd5878012a57cd90bede81f40f9fee994b.nq.gz
    ├── 1ed82f817cf41ba55211d61af4c20927f62c650d.nq.gz
    ├── 2001a786a27062ca9f1f07755104a361d5ea57e1.nq.gz
    ├── 201137ce31b646ce3f4f95f15925ea8ef187d9da.nq.gz
    ├── 201200b00d73b23d7981c876f0184e47716098ab.nq.gz
    ├── 21ac8396377e59d1419c34171f8217d80637fb09.nq.gz
    ├── 2332c89d536e1781bce59aa07b4e9d3596b136c7.nq.gz
    ├── 243b0cb7aa97745f234c73b3fb6b970fcd2108b5.nq.gz
    ├── 24c5d9718194315f449d7ce8ef0cf6c79a0416fe.nq.gz
    ├── 25f5cbfb0f1b8d0dfd0c52fd2eb61b283c30b203.nq.gz
    ├── 2710468d83f9a59e4821a0fc501a54cba935be00.nq.gz
    ├── 274ed81af8c930857ff5df5d4a6dc9f2a226a226.nq.gz
    ├── 2787d51a383a9e8b2b89484b8e159ab8c6ea6578.nq.gz
    ├── 27a357d50d0ee43406ba9954f02bbfdc12def7b9.nq.gz
    ├── 27c5f5b70b61dac16c383372a1812508b0d7c138.nq.gz
    ├── 27fe92969ddacff109e3c9abd580e444fc64e541.nq.gz
    ├── 29119cac7716cb297bcebd78c53a2fac9e5e70d5.nq.gz
    ├── 2a435b96e5e7bf196539b4a8920175c227271de6.nq.gz
    ├── 2a4616c4619d104b0441ffb51983a5051471e3f6.nq.gz
    ├── 2b53564f2e45fd88a09cfbd1db06ed8594f13cd0.nq.gz
    ├── 2b590d9403007cac68c42b200fcd8465cc29ec97.nq.gz
    ├── 2b683a63516def713ec0623adaae59b89d12ea84.nq.gz
    ├── 2bbbf82740010efe9cb46fdc307d785f096d21f7.nq.gz
    ├── 2c01aa821278e06d12ce91882e6ad6e5bcd1d455.nq.gz
    ├── 2c4258cec71533ad19e48b719656307a74b6cd83.nq.gz
    ├── 2c44877f4ce4f8cc8287a186186ac0b939bd3b13.nq.gz
    ├── 2c7b240bbd8613e314ee14c022564373321e6644.nq.gz
    ├── 2cce453212e00279698238c0838351ef868852bb.nq.gz
    ├── 2d2a4fc2acbd7c0d1ee003e10bad4d9a17823f77.nq.gz
    ├── 2d32b12e5566498184c8890866981ee1e9a0a26c.nq.gz
    ├── 2d796cab6040bc39f337d104033fda4c705d134e.nq.gz
    ├── 2e75a16f53f54dcede0139098054c86a4ebe55ed.nq.gz
    ├── 2eade3bb49b1746a5fe3fda8cb73d7c01f161685.nq.gz
    ├── 2ed3b87014fd978314220eb84e81579c6b597004.nq.gz
    ├── 2f39f7f48b7be78dc556d22072145c9e43d74af6.nq.gz
    ├── 2f593c29b02847dccad61f5311bb3af68953315a.nq.gz
    ├── 31fc63b122783be7e280630849bfa5b0470f9fc1.nq.gz
    ├── 323a4b4ccb8e1a2d3ab3c8483f392dbb1d4937fd.nq.gz
    ├── 32dc2fc3f52856a3991b3e7367486d2dc5aee8c2.nq.gz
    ├── 332defbb3b0696cd1885d7d90b5e2be719c4875a.nq.gz
    ├── 35f32875b842fbb5a0c775c699d661fbcd8a849d.nq.gz
    ├── 360bbb60815fc28859b74a7e3aeb999323ce33ef.nq.gz
    ├── 366997da0a63d18b988ef8dcec801d7d9b211cc8.nq.gz
    ├── 37172374f75ce1e60f90616b9081cfc3972290d6.nq.gz
    ├── 3786911dccb74b01aabb920a574940c0710fdba0.nq.gz
    ├── 38972655faff07d2cc0383044bbf9f43b22c2248.nq.gz
    ├── 395e81dc2f6b7d23636baaa83f1a88b6db9fa340.nq.gz
    ├── 3b2b50321ad1727bf56ebc80371d90f57490bdef.nq.gz
    ├── 3bafba8f9b307bbb738840e2e404d2ec3b5c8363.nq.gz
    ├── 3d124dfd5a1474d761712047b576c785b80eed88.nq.gz
    ├── 3d1badb976fb9409169deeff0cbb1f7188ddbf9f.nq.gz
    ├── 3d1db2deb49ffaa51a384defa2beb0de46d57c1e.nq.gz
    ├── 3d46c507ddc28909c25fb1f6ba6f7759f226a080.nq.gz
    ├── 3eb5397853864cffff4594a1eb5babccc8e2a5c5.nq.gz
    ├── 3f26057fadeaa6ee08ca538139c646f7dfb832cc.nq.gz
    ├── 405e2095a483b261eaedc8f96df0c4b9afe2e2de.nq.gz
    ├── 41a8c45e1b7f76ca9bb6f9aaa19d921d76ae5982.nq.gz
    ├── 41aa8244608a728e6d08fc48edfc793027c5a548.nq.gz
    ├── 423ba01fb3db11d4f0b729b5de8c3051778c9c6c.nq.gz
    ├── 436a303aa26de52e5d142b66d2f378d35ab85ee2.nq.gz
    ├── 437066980ae90aff908f9af00110b01f6be1434f.nq.gz
    ├── 43eee5ce2b784e1c08a617f66fbdd735c74c41c9.nq.gz
    ├── 45cbd6e4afe0ad779b4dfa5678df5ee025aad203.nq.gz
    ├── 46010934aa517ffef67307149a96fcc7fa909b7e.nq.gz
    ├── 4622f719cc80d643d69b2ef60c881812162f2606.nq.gz
    ├── 464a866bfb2aad1fbf181c8c2ac7764b74190e0a.nq.gz
    ├── 4660a60d8dd8a248d3787d12450abd00c5e312a9.nq.gz
    ├── 47d52bc473453a8a026c8436ec6ec22d1ffb4054.nq.gz
    ├── 48108f308bdf456dc31a5d1acadc357d4c815164.nq.gz
    ├── 4857021ecd52e37ead416c795e0025b4a715825e.nq.gz
    ├── 4911bf04d0059869da4eab2aea8de1c049f51fc3.nq.gz
    ├── 4931a8d97eed1aee9d2d9370e63322da2b4cda1a.nq.gz
    ├── 494652eb8a30eae22503a5fcb5255574dd22a95e.nq.gz
    ├── 4968b3e0bfa37dd2c479d15de8561eba8fee650b.nq.gz
    ├── 49ea4a13938c2226a4747d794906efd2ba1daa84.nq.gz
    ├── 4afc7d3ff2687745d45a65b6930d5b583c448298.nq.gz
    ├── 4b2d359b13eed226cbb98e069a2b4d8f432f9adc.nq.gz
    ├── 4baa18a57afd123ba878ced5741864a5ffde0f79.nq.gz
    ├── 4bbd031bfbc02ac013b7cb23e6cf69cecf3ab47f.nq.gz
    ├── 4be3a291e80c7f6ca53ba145d5d211467218981c.nq.gz
    ├── 4c13b20dc69789151859af791cdc435e1b7faacb.nq.gz
    ├── 4c23b9116f4236654ece40a476003ebb2e3d7354.nq.gz
    ├── 4c7ea2983fe7bc92ca59f1d7529a966b09d7e073.nq.gz
    ├── 4c9cc5a451573d1522e742887fe126c232398690.nq.gz
    ├── 4d33286f5669a90d7d4a2733f4ccedb5b5f8ad0e.nq.gz
    ├── 4e0131b673fe75cb6c546bce9f6251a18db085a9.nq.gz
    ├── 4eaab86cdd99c4f09cb67864e7fd38143b6d30f4.nq.gz
    ├── 4eac6d2628fe50b0bbde67d594306904040446a2.nq.gz
    ├── 4ee201a2bfea2bb1297208611349c005e8f35fbc.nq.gz
    ├── 4f497cf59d038fce1b20ae17cfa65c577ad932fd.nq.gz
    ├── 4f50c9fa80723a085da9176a1c0e463ebf1925ab.nq.gz
    ├── 5045793728d27eeb621ec05ec2fa8829e04e77fd.nq.gz
    ├── 510ed4f8430d50de682e00b08971a035e59e8b2f.nq.gz
    ├── 510f58aeba20c7fedd495f9547847e56dc315d93.nq.gz
    ├── 51477c7f58e1bb014fea8776296e4c92d320ab80.nq.gz
    ├── 519708fee19b1ad64ae2db3e59bb6801353bf1fd.nq.gz
    ├── 524b4f3a8ac4c0951c1fde1f3c389c9fbb5b00bf.nq.gz
    ├── 54245073d509aeca608663f0eecb5284868494c6.nq.gz
    ├── 54804cb07123f7508a028d0ae91c1cc80795bf27.nq.gz
    ├── 556eab6f5745715d8957231ff98bac37ed2062af.nq.gz
    ├── 5654a2e8af24f81466dcc1a4bb98dfe219ac6403.nq.gz
    ├── 56a84567b7e1bd165046a18287b36f97e748c263.nq.gz
    ├── 56e1c67f3b6b55bddcbefc522069d16d6ed78aa2.nq.gz
    ├── 57884b2b91c9acc1017a1c4a8818af151761da9e.nq.gz
    ├── 57f1db6033078a114d666fbffd2d701306e2d6db.nq.gz
    ├── 5821b12c35bb11ff588e843322438701039b673b.nq.gz
    ├── 58476a827ed741931896fe6f82910f8bd01453f1.nq.gz
    ├── 58fa7a77b624cafe40212e87451a03d2204abd24.nq.gz
    ├── 5a0046cf5e8a8b7d709427ba05938b30c900e048.nq.gz
    ├── 5a47e514e556c89bca8823206fffaa340d58e381.nq.gz
    ├── 5a7ffef02694e4e567b3417fcb0f1583c53d7166.nq.gz
    ├── 5aa9a621381b7af0ba337f9b982d2c84029c2fba.nq.gz
    ├── 5ba7cc5c8da5059f47b06f5fdc4cd78e981349ed.nq.gz
    ├── 5c2e9a5df29849d1f5ed8e302e8f9ecd5f5d2281.nq.gz
    ├── 5c7dfc37ac64db0536923711a4c74b661eaf0509.nq.gz
    ├── 5ca93a26b5d5053ec545647528a87d8471fae6e3.nq.gz
    ├── 5d3a9ebc88a54a80e6670c05b6ac4d60105c7e9c.nq.gz
    ├── 5e7d79bf404f0544d0656a3e188a9028e527b9f2.nq.gz
    ├── 5ece8658ef5d62648967866a6a6312b950b18732.nq.gz
    ├── 5f3e325b3624fad6e21e897270458267245a5a7e.nq.gz
    ├── 5f7ceb89c2a1600b0965d985afcb9915cba84c78.nq.gz
    ├── 600c13910fecf55189089478df2688dd6ce269cf.nq.gz
    ├── 6184f6d3d4a6b7900c36d7ef13d9773a54ec9cd6.nq.gz
    ├── 61935a8cbf569dd2d13fe03f8d2f387fb2d57b03.nq.gz
    ├── 61a2e7ffdd96433fd159302c889b9cea1fd3c7fd.nq.gz
    ├── 633da2cb70f918aba564bf620fde50f35f4f8dd5.nq.gz
    ├── 63c47083d3b6a889173e2a0ce554301ce3839374.nq.gz
    ├── 63ce0ac98fdce91d2be29adfbba5eab4cf068d3a.nq.gz
    ├── 6448a81373747a2267104b864a2bf63ef9649f94.nq.gz
    ├── 64a0801ea0dba4e1bcb79c4e9d43c9828b456dd2.nq.gz
    ├── 653cb53140f9f67f2b86696d9688271ecee8d5ee.nq.gz
    ├── 659ad36be8aa8552a122803a07a8c7766bdba40e.nq.gz
    ├── 65fe48c540540cbaf193c13f1bd6306d858d3931.nq.gz
    ├── 665b5d2d738f9302fa6a055aa3675990bed3c7bb.nq.gz
    ├── 675e3502110b7b4af62921e33239610e8b40d666.nq.gz
    ├── 67c9d3cc1e23487c58c91e597a1b019ae06eb1d7.nq.gz
    └── 67edf994bda0ccb48bafacc02760a182dbd73414.nq.gz

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

[jazzband/django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
