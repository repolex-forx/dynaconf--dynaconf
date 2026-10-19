# Repolex Knowledge Graph of dynaconf/dynaconf

RDF knowledge graph data for [dynaconf/dynaconf](https://github.com/dynaconf/dynaconf), parsed by [repolex](https://repolex.ai).

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
rlex download dynaconf/dynaconf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 455ee38569d76cd3707c73209b660cf60bd97b29
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 455ee38569d76cd3707c73209b660cf60bd97b29
│           └── chunk-001.nq.gz
└── blob
    ├── 001605da8b542364c63bf6d178def20d051c2f2d.nq.gz
    ├── 00364d3b7501c20291ab97c62af81671e4dfb631.nq.gz
    ├── 0179c1ae9f4a28637b90e8ea34480c3589763bfe.nq.gz
    ├── 0180d1bc585ed48523dcd86dda13c2ce95b32fe9.nq.gz
    ├── 01d3e140d5d4140131129705e484d1281606902e.nq.gz
    ├── 02bedcf4af428c5a7397a50806ae821e16021565.nq.gz
    ├── 02c24df2c51bd123fcee35dd5fd1772c46eb3a4e.nq.gz
    ├── 03095263b2e61f7cb36a6e36bd9674791bb7f99c.nq.gz
    ├── 0310a81bf1970f53812a2d34bb05a6411653d469.nq.gz
    ├── 04782487801e1ae42dcb5ba78f0d5eb57890d3eb.nq.gz
    ├── 053001056b4b0192a5649eb7b0971b31515b9ab9.nq.gz
    ├── 057acbd8b3cb4895895767537fae559fe1717e09.nq.gz
    ├── 05a75f5cb27597dd93c4963c308c88aa9f513721.nq.gz
    ├── 061686d546a20c2860faebf108770c17428f4a36.nq.gz
    ├── 06b100b4dfc96df256ab88f2e26ddfce0d4b158f.nq.gz
    ├── 0728055341477f901950f2f82adaeed837b45bb4.nq.gz
    ├── 0756b1f09b85134607752b052e6aaa41de0ca270.nq.gz
    ├── 07d1b999f97257abbfa70e83320b5531e78e6adf.nq.gz
    ├── 07d205914cce72dc8cc9b9fffbb9d3d269c6b647.nq.gz
    ├── 08529827fff6b20fbf52aec535b1e15f6c888dad.nq.gz
    ├── 08d59def1eb7b8e6e4e83866c2f60b23013d5ae6.nq.gz
    ├── 0900cd9ae426cf71a4971afaf93f910c26ee2d37.nq.gz
    ├── 0936bdcbc10234a7e5f68765bf6a37082655b88f.nq.gz
    ├── 097a65bb74ccb89ba3455aab5aca329bebc6fb36.nq.gz
    ├── 09b97b199bc3fd700305ee02686b5f56795a96e8.nq.gz
    ├── 09daebbc117fc1db29ce547b5cade55d7c9850ff.nq.gz
    ├── 0a1e207a520bf36ae35e45c4129733c571b8239b.nq.gz
    ├── 0a8953fbec84610c645dfd98d117d9c5e1025de2.nq.gz
    ├── 0af54fe7ff11620bf1743376afdd2b321fe0190a.nq.gz
    ├── 0b61e07f52a1305f3ce4c27eabd522a7bb0d821b.nq.gz
    ├── 0b6c2d8f731224fbdf57d18a9addd423b9c88d63.nq.gz
    ├── 0bd845ef57faf791f0533d17df33556b7622827a.nq.gz
    ├── 0bddb469c9f6446590eaee2d9b717b0bc5bb24f8.nq.gz
    ├── 0c20dc0ea76c87afa8171ebc92ae0632ff21267b.nq.gz
    ├── 0e017a3629f7e3bd84576254e0ae29c14bbba4c9.nq.gz
    ├── 0e9a9bcca27750850958576c3578c95271bf2b38.nq.gz
    ├── 0ed0e9aa2cbbf18189f24dd36d6b04c27c637b91.nq.gz
    ├── 0ed31d7077e84e25da5b995440ea795a43c68395.nq.gz
    ├── 0f18b83819b97b6a02d585ca837465792845672e.nq.gz
    ├── 0f4e2722a6880acccb2e400ceeed5aee29e8f810.nq.gz
    ├── 0f8b95a27de50b52070c23206ad95a4038f8ea76.nq.gz
    ├── 0ff7e6a021b95ea4cd85455795cc410778ac7426.nq.gz
    ├── 10907b83d6119e7b64cd53bc5a037060d71d07f1.nq.gz
    ├── 10aa21d0c837c7e5668350f1a57b97b923fa0a81.nq.gz
    ├── 10e17e9d2450942989077b1ad92ca7aa07cc7d08.nq.gz
    ├── 1244a52562118063496e188c9b0299a01e4b912e.nq.gz
    ├── 1248a6a3a453c6a3dd91cbbbfe564ccea45f5409.nq.gz
    ├── 12733be18e222d0ae917c0814d20fa0f5b73abfd.nq.gz
    ├── 1312cd7a4ecf5343320649d70ce4721721b1654d.nq.gz
    ├── 131657b22eaba97be7cbd4bcd64780f2bf8d7ce2.nq.gz
    ├── 13457ca3a0aa9851e02a18ff726d617408866262.nq.gz
    ├── 13c1c2d7538d7efc1f06fd87fcf7f56f5583b4b6.nq.gz
    ├── 14ebf421a0aa7492d1e18e6a737b8878ed9e306a.nq.gz
    ├── 14f7cd059a1e943c54a266dc8586318362429df0.nq.gz
    ├── 18003f60d66835c51542102a7222661b69489768.nq.gz
    ├── 1855dac2846c2064a516e74a1e89cc03b4fc8abb.nq.gz
    ├── 1877debb64b9d6614bd1f5bb1b25320329f2b2a9.nq.gz
    ├── 18fae82b927f1f9013d0127b94ca363f888ede61.nq.gz
    ├── 197384be6bc03dac9e1e56a583b000621c4657f7.nq.gz
    ├── 1a231fb55c76dd287fa08d0a57beef38d8e685d9.nq.gz
    ├── 1a2e7211b81adc7595c7b57dfa307e8aab82bd51.nq.gz
    ├── 1b01492aa951c07c662d6c968288222eb649aa4d.nq.gz
    ├── 1b08d9296869f68692839b642c311b6cba8baf54.nq.gz
    ├── 1b76de8c4335fd914ac7c6b80f35324c61942a9f.nq.gz
    ├── 1b7a2bb6c80fbf9c217f69a08944e0d22f0898c2.nq.gz
    ├── 1c826649a246011898ba43bd0deeab0eec907518.nq.gz
    ├── 1c9cc674f76b5b14113e77f43cb04fd0c9edf528.nq.gz
    ├── 1c9e9a405b9d472d4e4762630b4524e1389f33e0.nq.gz
    ├── 1eb2a297263a3b2f4a7aa7123631b239cf01ae81.nq.gz
    ├── 1f8a25163cf354361698cf54ae0c3ee50d3f329e.nq.gz
    ├── 21317e14d226ee98d447fb83e1b078467d36069b.nq.gz
    ├── 213421f495e1d10915a1582a6fed50aa5c860f41.nq.gz
    ├── 21c487ea62155a2f7e9cbe8fd89e27327a97630f.nq.gz
    ├── 22d3f399afdb5341925e96e774e569ebd91b7a19.nq.gz
    ├── 22ff7907c85a4ad74827002bd50bb8c7bf6133bd.nq.gz
    ├── 233de1e3a1651429144db7b725ebd43f174f61f8.nq.gz
    ├── 23a97382bce8acd010349d3d9f10ee8ce278491d.nq.gz
    ├── 24563d321019d101a0f3ce90548e591ef93b9a55.nq.gz
    ├── 24a3c7c25cc646aba8b22903ab19ab57304dbfcb.nq.gz
    ├── 256bbe469712d9936dc945edf6cb9713bd6b1e52.nq.gz
    ├── 269dd6810f2489b46618578f08dd35f76a425d23.nq.gz
    ├── 279b2bb2117d03d62a0c5d9ce281ef2baad691b4.nq.gz
    ├── 2959b9938531a6f6ee9b39a3a173037d0322fa36.nq.gz
    ├── 296a6c9f5ee9469ec6aa42cb776a62e264ecc590.nq.gz
    ├── 2990a2bb8907ee850999fded98fc6813353e6f25.nq.gz
    ├── 2b1e9021f0287f65dc8e8dc994a73039535643ee.nq.gz
    ├── 2b4592cda10437dc923a3621a4cdc228c3135163.nq.gz
    ├── 2b4e7e1867ef4daaf3f58592f041f5900834b919.nq.gz
    ├── 2c2b910c0bb2fa24029fd4a8da1968b21d611392.nq.gz
    ├── 2c616d10480eca84454b8b9c7f7df74268fae908.nq.gz
    ├── 2c6610196c33580b6541301661c66058586d7007.nq.gz
    ├── 2c7540374d555f7f38187094b7e629e8807d8f34.nq.gz
    ├── 2c8f39a93996a02733d33a6b5d62ca849e97bcfd.nq.gz
    ├── 2ca256053b4190e5c864caaee5db4c8f18f66a7a.nq.gz
    ├── 2d4110820f8671a1611db13565fb55e337c289d8.nq.gz
    ├── 2d41474ce3061a069565da510f7e6bf93083eb88.nq.gz
    ├── 2d5559294ab7379d21de86f7963dd37dd75287bd.nq.gz
    ├── 2e28ab549ea8034b5a13011ec20c142de0cd9de6.nq.gz
    ├── 2e74e9dee4fb6121ea53c0d33e8848ebc4a31309.nq.gz
    ├── 2ed8f25932407103c0e509b8c25dbe2bb268cfba.nq.gz
    ├── 2f0ea9ac89fd70d8e5463e4aadd20264f8057a62.nq.gz
    ├── 2f81b98cadeb6b3b1a77c338e23f18cd48f91c0e.nq.gz
    ├── 304a3380b3ee8dd46eed5d23223e5f38bde0ff9d.nq.gz
    ├── 3083e2b4a56003d67b59d65a3611053c3162df17.nq.gz
    ├── 30c2c393bbbc37f60ea059201f9d064c71fd7301.nq.gz
    ├── 317280df26b74ec26ee41f9b8f5a85d00f5c0949.nq.gz
    ├── 31ad8dd4c8f7e5c34af812e946d07273a26ce5a2.nq.gz
    ├── 32268aeda1fd2720074a97d159f6b48a2c25b63b.nq.gz
    ├── 328e089b1af4b3cd1eb2a439428a5f51cececb24.nq.gz
    ├── 32c4098ae6a47bd54ae0328646d3bc7f0cc3c7bd.nq.gz
    ├── 32e2c8c42661109604ee4ee87f1f1688e878cddc.nq.gz
    ├── 32e9a2c9057a13ecbd073fda0741809e6fe4213c.nq.gz
    ├── 35011b48f23c3bbe7655f6e0995a98f6d761cee6.nq.gz
    ├── 3562c4979f6070dafb13a818073be3a07d1fb946.nq.gz
    ├── 356d38e710881a27619be29f9d78d2c908d37c40.nq.gz
    ├── 365c189740c4b8d87b26759eb4fe136f5727e00d.nq.gz
    ├── 367b30b822c6ab72b674c5057b68176b47f15c3d.nq.gz
    ├── 36f7b334efdeb4c6d25d097004a9838b1c43c2df.nq.gz
    ├── 36faa58d6dd22d3ff445fd60ecc1fa21df0364da.nq.gz
    ├── 36fb5e0b91c781d093bfddc0ddde627939a99547.nq.gz
    ├── 370d523ebdfa24d187a8d2a0a5ced8a2d6729b37.nq.gz
    ├── 3833156cd13be2f96aa2e50271cd56ebb06e92fa.nq.gz
    ├── 386358d4d3653c4beb95e92eda97b38e99a5aaf0.nq.gz
    ├── 388ad4fd52428b560a50215e26a46f5db6f8cf43.nq.gz
    ├── 39372feec020715a19e52cb689b4a1ee7a37fe19.nq.gz
    ├── 396134e9b0c65cffba340b1654462ab47086e29f.nq.gz
    ├── 39f99cde5a5582d64576ebc23c8a435b96c83933.nq.gz
    ├── 3a2ead7a3c202a1efabb740a6148d55b8a436196.nq.gz
    ├── 3a476865ab55952a73c6add0a2dc7dda6ed2b0ee.nq.gz
    ├── 3a68950891995d554c593a23ec3563aecdb6584c.nq.gz
    ├── 3af51fd9fe0a630d77fd383d4e22393322432000.nq.gz
    ├── 3c43ec90316c5bf4ad44aba2641bb1095e20f01f.nq.gz
    ├── 3ccd071e98da0321b671965a7d7056bc82ef8fb3.nq.gz
    ├── 3cef8b7e6903b87834f469a7ed395072d2637509.nq.gz
    ├── 3d07edf774603bc9dba0962015e756f6fdbf06cb.nq.gz
    ├── 3dc813e7022a99bca593e71a6a965d41b17e689f.nq.gz
    ├── 403e548d33f81500bac31881c43d229cd92d9bc2.nq.gz
    ├── 41c8c5dd48a583efe74ce65f41bf63726b628fee.nq.gz
    ├── 41e4813b023cf7211f839aecf60c5222cc0986aa.nq.gz
    ├── 43b4d2cb9a84602b349fe1458c0c7e1df160afc6.nq.gz
    ├── 43ee8afc380e075f3cad7de00df354f1791ef5f7.nq.gz
    ├── 45541ca04cafe7e52d2724eac427d56ed7c03512.nq.gz
    ├── 457d1da71e252f6b1d28e7d4207722e0b939bc89.nq.gz
    ├── 4881eb65c6ab7077ad21490bf421d7f644484986.nq.gz
    ├── 489102588ebba56662d73549a90a21ebc8474956.nq.gz
    ├── 48c5c6ae50878f85306df732e16fb40f7573effe.nq.gz
    ├── 48ff9307fb088abec89d18d7fb771ce37a2634d9.nq.gz
    ├── 49541a8061eae66b279ac87e35b5b06730baf57b.nq.gz
    ├── 497d5c52ecbc9302b54cb6101085c590ed062a19.nq.gz
    ├── 497ebf4583c6e56f4fb94b3d9fa3fcea3f9f2262.nq.gz
    ├── 49c507c5528bc4535167f8623b9f9dcf3f9eea7b.nq.gz
    ├── 4a0f240322cc4ac47b84cafde15efb2924f9e260.nq.gz
    ├── 4a95f9214fa1dbf217c7d9eafbe91c1faded7ffb.nq.gz
    ├── 4bfbc835cf00d7fe439c94e49c55eec781b088ca.nq.gz
    ├── 4c7ddc6169b9ca46b97f7d606577a3a95f6813d6.nq.gz
    ├── 4d4c8bbb7c1aa340da3f657fb7bdf314dcb7d61e.nq.gz
    ├── 4f1a82a3483102738cf368fc7f08b15d7fd1dbe4.nq.gz
    ├── 4f7c53e86c81a0535309f58938e822148887be13.nq.gz
    ├── 4fad0e860e2c861dd720917ef0547b56feff5238.nq.gz
    ├── 4fe21cfe2f8e862fa33aeb680a44d26fcabc41ac.nq.gz
    ├── 508dc69ac94aec5376d2f6169604293df969dceb.nq.gz
    ├── 512e636746c384815b853823949d43328d0b4980.nq.gz
    ├── 51d186c57697558db876bc55763717e55f0451cc.nq.gz
    ├── 51f1fcd6e43ad2229a2ab4a7de103708e60c30eb.nq.gz
    ├── 52055801fce1b6bfb0a3f02fa54b5a6475bfabee.nq.gz
    ├── 52306a6b06dc8c84abfb2c8c7ec4c182b8e858ac.nq.gz
    ├── 52a2bd8de736b6d8b2763261ee647a0644bcf509.nq.gz
    ├── 54302b4acbd27544ff629cb5faf956c5c848182d.nq.gz
    ├── 5430d79c44b965b4708036da6f2019cb0bcf1b26.nq.gz
    ├── 54418ec3ef8fa0293616c6a66ba01aa08e34b448.nq.gz
    ├── 54705dce99f18218679386bd378b8319d43a814e.nq.gz
    ├── 54babfbb5c83c8b3eda1024d107ad61e5a4a342b.nq.gz
    ├── 54d4274e396da96799c37b923cc6fe7824947197.nq.gz
    ├── 55131c4ee48466ca23a0da1d234d1e0667ee5633.nq.gz
    ├── 558aba75645c15c3e6ade969b45ca4abb1f49b0d.nq.gz
    ├── 56646435ab2fbcb5654c42cfda98e757359d924b.nq.gz
    ├── 56b9717bb1e46eea46e48b5e227411a7a3a2b5aa.nq.gz
    ├── 56f0809c55baec08bd59992f953b5d7eb87fe1b1.nq.gz
    ├── 5709991c2c146d2d286078d0ad6e1c11b8835f58.nq.gz
    ├── 571d1d529f2499b4b1eca1838258c55464e244eb.nq.gz
    ├── 576d83e85523a28ebea0abb9789d5cdcb11e1154.nq.gz
    ├── 57f89eef98897bc6dc661678e137f70f391edd6e.nq.gz
    ├── 580206def396d9b57379d9ca6cd242b35b305b24.nq.gz
    ├── 588b789bf059968e6d8fb3fedced56214ab2443d.nq.gz
    ├── 58a94143a603e2341ca11c5acba80e586323d227.nq.gz
    ├── 59284a6240b71be31f77b3103f056d3fba0fad3c.nq.gz
    ├── 596dc09645a73641f6624d1e505c941bf8c167e3.nq.gz
    ├── 59e36776853fd3abe056692f990117ab9c982bfc.nq.gz
    ├── 5a4d624fca2ada9c7daa2b1231b0c8a5563dd2d0.nq.gz
    ├── 5add98ffffcb51a8b2a65986cb3c756ea38df450.nq.gz
    ├── 5cdc580d9dfcd6e55fd316dcfac1cc88eb7e0619.nq.gz
    ├── 5cf982099448e9afec4f4a7d99e922c2e614245f.nq.gz
    ├── 5d774d1f93df253d10445e3317723bf20f79754c.nq.gz
    ├── 5dcda2baef4c6ceadd884056468af0bd57427ec8.nq.gz
    ├── 5efe634e4acdca72f5db33a4d7f66821d7cf3c1b.nq.gz
    ├── 60b7a8480f2c2279f328b317f57e2a6a100d3967.nq.gz
    ├── 6166c32fc3e3f1bb67269c0d19f51139e264df32.nq.gz
    └── 6181cf77643564ea40bb252a55f577dda9acb045.nq.gz

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

[dynaconf/dynaconf](https://github.com/dynaconf/dynaconf)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
