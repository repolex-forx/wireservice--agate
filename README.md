# Repolex Knowledge Graph of wireservice/agate

RDF knowledge graph data for [wireservice/agate](https://github.com/wireservice/agate), parsed by [repolex](https://repolex.ai).

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
rlex download wireservice/agate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 202796ada63357c275a2a5f8685a983e37bad9bf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 202796ada63357c275a2a5f8685a983e37bad9bf
│           └── chunk-001.nq.gz
└── blob
    ├── 01db158b43cfc36012548e1008ec0d81d06dfa58.nq.gz
    ├── 039f480a90c8e7c3ea102a3bc3f1871de827bedb.nq.gz
    ├── 05d8056499c6036dd87da31874dd8ab319d5f77c.nq.gz
    ├── 083d078db093f253edd4792b5abbe81723c8bcc4.nq.gz
    ├── 0915e47351988295ac4d84251f178928d1bc88a1.nq.gz
    ├── 0ad8b1314176537960320e7baaa040f07901d2c4.nq.gz
    ├── 0bb3d1d85e1543629e7dfdf6f45e515626129eec.nq.gz
    ├── 0c0caa3155ce9759778db56416286a17d0b4a99c.nq.gz
    ├── 0c0fc73da558a3bea6612e166c8fddaf93cec024.nq.gz
    ├── 0ceb92954a9558e0d305a294e9381cbc0389ba14.nq.gz
    ├── 0e50dd3917fe5231359ac391a2d02f63a7000212.nq.gz
    ├── 0f01ea2b0478a4018aaf63a8e0d79df5c15f6c4b.nq.gz
    ├── 0f0cd589e207bab0ee70af8f43bbc011c752b9b7.nq.gz
    ├── 103c40277695f23a7a67e748224a205aad624b86.nq.gz
    ├── 10833d08a09cb287102fc25178c01fea58c91172.nq.gz
    ├── 11b94c884d9db63d3b7122b6d806233a448768cd.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 12aa8c5692697dec1ef44dd13456eecbfdde9d6d.nq.gz
    ├── 141c3aea199afa6991fd5145d6cccc83b1fb267a.nq.gz
    ├── 16f71b2c9dddcae5c34f516957fc8b464e26d1eb.nq.gz
    ├── 18d6e1e03a17a8f809029739ab3a1a970b0b8733.nq.gz
    ├── 196ae00e11e7222eb8ab86a5cb08df6bc36f570a.nq.gz
    ├── 19d5bcd8e2e55ceca4710e59923857b0540e50bb.nq.gz
    ├── 1c94d1a1c589f1863af108cdf401505e2ed3f738.nq.gz
    ├── 1dd5d9d23581b5a2e05876bb851a215c70d59688.nq.gz
    ├── 1fcbe1e0c053ffc48d6106cb0eb40a668e7981dd.nq.gz
    ├── 201c2a1153febbd98188fdedbe0d74e65e67de3c.nq.gz
    ├── 209b39b6034ab26e090b18986b3dd5d4e649ba80.nq.gz
    ├── 2130739a0f79842b3ca9efce6cddbce7c71f80c2.nq.gz
    ├── 22a95da5d0027aa562b385447f225c1276fd3eae.nq.gz
    ├── 24b3cac485b63f0323e84284fb74d401365b8d83.nq.gz
    ├── 25830e3147aa43a07808f71ccbc4e4da8cbdaf29.nq.gz
    ├── 2593a1c41a320bd5fd96b6a71941aab1b45acb24.nq.gz
    ├── 25c2cc8ab405dde7ae862d2807a4f3aebc612658.nq.gz
    ├── 263d2157fab9edeb2b28c643183d189b1715d65c.nq.gz
    ├── 2650028e653310923ee8486dfd3fba0d2cca2fbf.nq.gz
    ├── 2c7ec6368ee9ee5e425c6457f5a1434d68e83d3b.nq.gz
    ├── 2c83c7add676d6b0783b64b45896b431788baab9.nq.gz
    ├── 2d280ce9d6526789a1b31410f3b80cc949753e81.nq.gz
    ├── 307920f367832e8f83c7633d865d63f696f4c995.nq.gz
    ├── 32c99f716ae791bb0d9d9d30a5c9bd462c8fc2f6.nq.gz
    ├── 3355aa28c32188f7c46184de482212971561f875.nq.gz
    ├── 33595a80551fbcc90fba9d1afd56145662df0ef8.nq.gz
    ├── 3514877f6039950998db0c175ce12eef5caf7842.nq.gz
    ├── 374be51e6b6860dd187643b38fe970d9348f9c26.nq.gz
    ├── 398d3272c4ca487a6c7f8cc5c8a05d64faa94a7e.nq.gz
    ├── 3c40d3da820b2cbc105958e48da6003f4a821ea0.nq.gz
    ├── 3f2f68ebc18fd0307bc974081a068b4db240cf96.nq.gz
    ├── 3f5d66de6f9f7567a185ca7516b4d17f33af3829.nq.gz
    ├── 3fb440e00514a510a59c773ef92a5d9337a818ce.nq.gz
    ├── 3ff3f4b0891856b0fa779a55dd63ec4a327cb84f.nq.gz
    ├── 426806bfcd26bc38cbfc7a5e6be588d2bd3a58c8.nq.gz
    ├── 42fd89e710cc5772b228865fe3b70d42553e8375.nq.gz
    ├── 43941de4376b013e022377a3160e0a494e9806e1.nq.gz
    ├── 43af7476fa62260b2a859577e4c0789fe438ae60.nq.gz
    ├── 4614ad4783c40017951c586a60d7c3a14084a74f.nq.gz
    ├── 46c3fbe89577fdd7f69d0d462c0364af99b57efb.nq.gz
    ├── 4876d00bcf47278896f22651048d2defed96d36f.nq.gz
    ├── 495083fbd664ce9967eeec245f84e553ddb5f0da.nq.gz
    ├── 4966ddcbe98b02d23eb59b109fc3f694598b7bb5.nq.gz
    ├── 49f905ee227235ca1c680c66d41302c1f01de4e8.nq.gz
    ├── 4be7a96c6df351629f3121834d54e15631e7e537.nq.gz
    ├── 4c32ed85eac8095a08ff445c3f094337672bbdcf.nq.gz
    ├── 4f74c86ae3678e6b460802a1b27f77825c8b3506.nq.gz
    ├── 4fe1c82e023d10d7496ccbf9d79327007e3989fa.nq.gz
    ├── 50ab0dfad69dbf9d527ce24faab39a77c0192fcc.nq.gz
    ├── 51a569d7e7f5a88057a3f6ed7b2b2cce0c288bda.nq.gz
    ├── 51d925f82230f9644d71e74a2da391cc3aa1b6db.nq.gz
    ├── 52958639b92f880a82e6e479adf11ae050cdfabc.nq.gz
    ├── 529ab16580631b03bd92ca0ea00daf2b450feba2.nq.gz
    ├── 52e32bfd16ff20fbc7e65a4328a34d0c8f90142d.nq.gz
    ├── 534e6ce4d46bf48a598f6207dd6f538af0b915b5.nq.gz
    ├── 53f1abf25e85e28809e926216bf6c37d3e65a871.nq.gz
    ├── 540cef20c96b0746a3d545238f5f185573d5d91d.nq.gz
    ├── 542e861466ee29ac7d61f1b61cd040a8c2f0e3a5.nq.gz
    ├── 5435946e434dcd3205a75088377ff647265f944c.nq.gz
    ├── 5729c199fc119d0ec189adf43bff7d5a4858aaeb.nq.gz
    ├── 59b27dca77d1ba725061a4a174e579188a034930.nq.gz
    ├── 59c797711de275a651d90b5fb34af2fea23ccffe.nq.gz
    ├── 5b0bf0cc9ef11cc52f1cd441cc59c5a27bd97903.nq.gz
    ├── 5bac6737a4db281b8a262b5c0b728352f80e787e.nq.gz
    ├── 5dc0030ce2aa237d2e0552cd9fdbc054e9c81e18.nq.gz
    ├── 6066c0fc204685f77a0f296b9b8df28adab3ff2f.nq.gz
    ├── 63137a3ed5ce5f52b52ad0f93280cf0147e25b6f.nq.gz
    ├── 63ba060246b67bdda52517d9615a2ee6a196ce09.nq.gz
    ├── 67b5e647001c32d8dc6efe533458cb2e6f88e163.nq.gz
    ├── 68342f8a244af21dfaf926a448697ad1cfdb3868.nq.gz
    ├── 69e656c11760c3e64a0b372fd26cca6a51473908.nq.gz
    ├── 6bf4294f55812a9499a8cadf5c1e2b86981007b1.nq.gz
    ├── 6c13fb5f116d6ce35eaa4f84e7176ff7f0cbaff7.nq.gz
    ├── 6cf886cedce074e260b6924446aaf62eba611fb1.nq.gz
    ├── 6d13fb5faaa10d3c6eaaa10e67a44be792fb2912.nq.gz
    ├── 6d2cc2f8c494f62def033b7092bf735ebcec6e88.nq.gz
    ├── 6fb48d0d9236cac71b5bff594fe6ca32d2980af5.nq.gz
    ├── 701e669350f9ae48f81ac9d1d1bfc895db39848e.nq.gz
    ├── 71fad4fd804a6b7646ec01f7e1eab0be59ca4f88.nq.gz
    ├── 71ffa83db9d1c65d6fd17aec7ca65aeec255dba6.nq.gz
    ├── 7208cc1dcc28e3f581e9d049e30221a8b6de1059.nq.gz
    ├── 7218317e7ea61afc25d3de646c2a1b024a844ccd.nq.gz
    ├── 72aa228add983c2c6385e2c89efb538fb45d8c06.nq.gz
    ├── 72f9db5429c3fa30ed62f147d1a495ba256f3d2b.nq.gz
    ├── 7549289de47c1b66d2c55b0250ef98aff311466b.nq.gz
    ├── 7612eb54e54a2f29d83ba2a8b885db26f83ba26c.nq.gz
    ├── 77a01443b9b5c67beb6893525161b64d432ceaf4.nq.gz
    ├── 77a4062da2513524003b76d11f7c2044a1754b6e.nq.gz
    ├── 78a77da77655da2309baf9667269f026a861cfa3.nq.gz
    ├── 79ede0e7d7778460bf92fb9f3fc8063259112557.nq.gz
    ├── 7aa8e3654aafe30e670dc71cc6126c88eccc7eb4.nq.gz
    ├── 7af9a5a758da415edda63d7dc82ddcb9f56db334.nq.gz
    ├── 7b4660922608544f9688f8db208d90a35c04ac2e.nq.gz
    ├── 7b6f833659e629a3dd3b72459feb1765eb75768a.nq.gz
    ├── 7bfdf0bd0491e442474a3030fcb181b7e4ac5417.nq.gz
    ├── 7d63233c7326639c2296cf29890aca886ab51cc2.nq.gz
    ├── 7e4ae11f7f4ab71cfa561efd8715ca27b9a044c9.nq.gz
    ├── 7eb459f3de51e6590e1515e7b30a21953334aa94.nq.gz
    ├── 7f0d929f0775851aea541b0b5cf5444fff5857aa.nq.gz
    ├── 8175187b97215d39f92bc21b50b3ea005a45419b.nq.gz
    ├── 83043fdbff6fdb4282bb55a9ae01f96f20ead37b.nq.gz
    ├── 836cbb7ede77fe53c6579ff570ae4e30a7a1c563.nq.gz
    ├── 83ae66c4cbe263b7b78d1990de637792b137d415.nq.gz
    ├── 8815bf6002401bad5bcef6a58250c6a6fdd7c5d7.nq.gz
    ├── 8a7a5fad47083b01b714df98fb26f928da3a1696.nq.gz
    ├── 8b9f2452110e2318945a2a3f05f75b392fe308ec.nq.gz
    ├── 8c999366887da260f81e7ccb268f29782aa36b2a.nq.gz
    ├── 8ded98ee6219cca8be90bad9cbca20ba00c5513e.nq.gz
    ├── 8efb0d127e0ff324ab8d45bfca8d3647565bc25c.nq.gz
    ├── 8f557394919bbef5583a720b199d0fbd329a9efb.nq.gz
    ├── 90259771933f7f927f9c70096f5ae8ef8a3c2d59.nq.gz
    ├── 91dc4dfe0814265b8f33e0f8b8c362dbd6ba9f9d.nq.gz
    ├── 92e880e62dfef7721ac0498f661739fd9283b13d.nq.gz
    ├── 951ab072d6111ff5981586a4007bbd44051bec7b.nq.gz
    ├── 95a0aa76092c72123c6513bc8a4f72f90be0a952.nq.gz
    ├── 95f6395ec0f5828667cd0b13eb52d30917f25ad9.nq.gz
    ├── 9656f80cd985cc54d14f6780c21ccbda0e90d9e7.nq.gz
    ├── 976ee2ddc09bbf89b3468ed037002b07891aa4b7.nq.gz
    ├── 99f494fe8fd9c134244f392497c55f759216bcc7.nq.gz
    ├── 9a7ba05da82a5a9db07df14ea30bd8aba55a83b5.nq.gz
    ├── 9c0f4c20a76ac3b15353792bd8fa99c7eb53ae31.nq.gz
    ├── 9d105ccbdcfd39138cf938a008af8478597b6b1a.nq.gz
    ├── 9edba98d02b9afd97514d6a22dd2cb101136645b.nq.gz
    ├── 9fe27dc9a7266dc5cc4b4bf7dd6e807407b24ec6.nq.gz
    ├── a112b934bec0eb76d4f0174596adbbd234cba29d.nq.gz
    ├── a127aea39a6bf4d48bd2da5cc646926334293cc8.nq.gz
    ├── a2dc9095c9d349783709df6967abe0b73fe1f230.nq.gz
    ├── a408924cab51f93ba2df926c5cd610295cdbf7fd.nq.gz
    ├── a669e4fa308643e106c6b3df7d0387783eeaa4f2.nq.gz
    ├── a7bab9c249b3ec545387fc050aff5b5fb6731aef.nq.gz
    ├── a8f7a180834c49fcd97487f2885739599a4c8dec.nq.gz
    ├── aa68d28d1c040d562e21f4cac13491c04f5d610b.nq.gz
    ├── ab2c0f78ee13b984828aa37eef36f2584cdd7e6e.nq.gz
    ├── ab88701efe892fa9aa2a9f45c679896eabee0e61.nq.gz
    ├── ac715ed058fefa93f9d5fe94ccf2859b33442ac1.nq.gz
    ├── adcc34722c1463ee3cc54badc0c616bb38d70c78.nq.gz
    ├── b245d503f2fb896cfacf4e9017988ac5aef3fda0.nq.gz
    ├── b3536fc3fa1fb0e6da4eae9749764e87610e181b.nq.gz
    ├── b463c5e59c3fa496445e35fda691829e8872d817.nq.gz
    ├── b4a7a4d7f850028ced979a587b919df761e2ecc5.nq.gz
    ├── b5eacc74fecac2515708d18a9961c92945092013.nq.gz
    ├── b634cbe6aaa1d0b5050a8e49d34b1f8f6cb9fb82.nq.gz
    ├── b66369d80123cf2b8bca521dbd29e1eb2786030c.nq.gz
    ├── b678a0a2cbf79e6d35effe0a2063896e67761886.nq.gz
    ├── b6af1a0824ba0c91d92157171dfceae0ef29b3c3.nq.gz
    ├── b7bc405f750ef4208b28ed9d13e436c79ad99ce6.nq.gz
    ├── b91e8343526d94d3db256cf931931591d455a8c3.nq.gz
    ├── bb0f46acad482a25481b6d615e830e3e051a2113.nq.gz
    ├── bb1d16c5460f22cfb39be8daa9cc3e62dff3c294.nq.gz
    ├── bc8cbff4d7bd8ef7fca70d49d150165ee5721170.nq.gz
    ├── bdd410c9d9296b135df8723591599125d4efa87a.nq.gz
    ├── bea504d7b8f27066bf68696004be6350c8e30112.nq.gz
    ├── bff7a6a960d13705d592d85e8989e2250c7981d1.nq.gz
    ├── c19aa0b4e7dc0018e88efcab2542e9d99c067886.nq.gz
    ├── c2467ee8808cc520a328136f4a5b7494c86f4dd1.nq.gz
    ├── c36c622d28ba2f56038123a689767eeba9cf2352.nq.gz
    ├── c401fa9391a2d07da7b0e4ae867da4d8782384ca.nq.gz
    ├── c483c309077258fe98e166eaf9749524211225e8.nq.gz
    ├── c84404b00db1dcdc72d8ea895ba27f4ade38a59c.nq.gz
    ├── c8f81fe20949b44b9f7b4d4456b28f14f80ae7b3.nq.gz
    ├── c9e1432bb4d5855c189a43183116ed86bfe1cb0e.nq.gz
    ├── cb51ffd439af7a2d312b143ac17b62e6026fd0f7.nq.gz
    ├── cd1b4cf63289ffc41f12716e61e89c4ffceee882.nq.gz
    ├── cfd48ca5670ca0ec5591fc9b80616355c5c124ce.nq.gz
    ├── d13d7cdd41ff95d28c18f4eba19dbb805c8094de.nq.gz
    ├── d28ed2483899b1b3d87f4d977d2b0267e8d8c2a7.nq.gz
    ├── d6014b4dd65cc7ed7b69affd27bcbb89d09f3959.nq.gz
    ├── d76ca56636de6f8014761ddadeae883784846e76.nq.gz
    ├── d79192ca99889c1611e633676b8b9b80bc6aac7a.nq.gz
    ├── d82f243396f37cc89cbd7410e16521ef285d8c61.nq.gz
    ├── d8b3339f385fc3600d254790d7218fab3d6843f0.nq.gz
    ├── d9e0a2aa722b17be40f72a9c26804525043f4929.nq.gz
    ├── dace13d5bcade1ea0fd89a9d59d1238f78a21252.nq.gz
    ├── db38592700cade6186b745e926aab2a552302b50.nq.gz
    ├── db5d1889d9bc524e5a51286dfb22ba96d09f1211.nq.gz
    ├── dbb28b497f0cfd02569d7b2398f3e21686ec5db0.nq.gz
    ├── de145d9b52978ed971f2ced9eb6a1c4fc8d96864.nq.gz
    ├── de25db97dc7c96c471a1a53a8529118eaf1997a2.nq.gz
    ├── df774b1eee2d26457ad1e2ba85192e2b80ad499f.nq.gz
    ├── e0b5c21de059282c3b3879ae7db81a284c494a06.nq.gz
    └── e1ab4a431d8fe9ae6116a21456e6e55510a9fe96.nq.gz

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

[wireservice/agate](https://github.com/wireservice/agate)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
