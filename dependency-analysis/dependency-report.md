## Dependency Tree

```
mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m├──[0m async-trait v0.1.88 (proc-macro)
[2m│[0m   [2m├──[0m proc-macro2 v1.0.95
[2m│[0m   [2m│[0m   [2m└──[0m unicode-ident v1.0.18
[2m│[0m   [2m├──[0m quote v1.0.40
[2m│[0m   [2m│[0m   [2m└──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m syn v2.0.103
[2m│[0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m└──[0m unicode-ident v1.0.18
[2m├──[0m axum v0.7.9
[2m│[0m   [2m├──[0m async-trait v0.1.88 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m axum-core v0.4.5
[2m│[0m   [2m│[0m   [2m├──[0m async-trait v0.1.88 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m├──[0m futures-util v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-channel v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m futures-sink v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-io v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-macro v0.3.31 (proc-macro)
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-sink v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-task v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m memchr v2.7.5
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m pin-utils v0.1.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m slab v0.4.10
[2m│[0m   [2m│[0m   [2m├──[0m http v1.3.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m fnv v1.0.7
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m├──[0m http-body v1.0.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m http v1.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m http-body-util v0.1.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m http v1.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m http-body v1.0.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m mime v0.3.17
[2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m rustversion v1.0.21 (proc-macro)
[2m│[0m   [2m│[0m   [2m├──[0m sync_wrapper v1.0.2
[2m│[0m   [2m│[0m   [2m├──[0m tower-layer v0.3.3
[2m│[0m   [2m│[0m   [2m├──[0m tower-service v0.3.3
[2m│[0m   [2m│[0m   [2m└──[0m tracing v0.1.41
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m tracing-attributes v0.1.29 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m tracing-core v0.1.34
[2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m once_cell v1.21.3
[2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m http v1.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m http-body v1.0.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m http-body-util v0.1.3 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m hyper v1.6.0
[2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m├──[0m futures-channel v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m http v1.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m http-body v1.0.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m httparse v1.10.1
[2m│[0m   [2m│[0m   [2m├──[0m httpdate v1.0.3
[2m│[0m   [2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m smallvec v1.15.1
[2m│[0m   [2m│[0m   [2m└──[0m tokio v1.45.1
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m mio v1.0.4
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m parking_lot v0.12.4
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m lock_api v0.4.13
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m└──[0m scopeguard v1.2.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [1m[34m└──[0m autocfg v1.4.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m parking_lot_core v0.9.11
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m├──[0m cfg-if v1.0.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m└──[0m smallvec v1.15.1
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m signal-hook-registry v1.4.5
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m socket2 v0.5.10
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m tokio-macros v2.5.0 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m hyper-util v0.1.14
[2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m├──[0m http v1.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m http-body v1.0.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m hyper v1.6.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m└──[0m tower-service v0.3.3
[2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m├──[0m matchit v0.7.3
[2m│[0m   [2m├──[0m memchr v2.7.5
[2m│[0m   [2m├──[0m mime v0.3.17
[2m│[0m   [2m├──[0m percent-encoding v2.3.1
[2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m├──[0m rustversion v1.0.21 (proc-macro)
[2m│[0m   [2m├──[0m serde v1.0.219
[2m│[0m   [2m│[0m   [2m└──[0m serde_derive v1.0.219 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m serde_json v1.0.140
[2m│[0m   [2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m├──[0m memchr v2.7.5
[2m│[0m   [2m│[0m   [2m├──[0m ryu v1.0.20
[2m│[0m   [2m│[0m   [2m└──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m serde_path_to_error v0.1.17
[2m│[0m   [2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m└──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m serde_urlencoded v0.7.1
[2m│[0m   [2m│[0m   [2m├──[0m form_urlencoded v1.2.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m percent-encoding v2.3.1
[2m│[0m   [2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m├──[0m ryu v1.0.20
[2m│[0m   [2m│[0m   [2m└──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m sync_wrapper v1.0.2
[2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m tower v0.5.2
[2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m sync_wrapper v1.0.2
[2m│[0m   [2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m tower-layer v0.3.3
[2m│[0m   [2m│[0m   [2m├──[0m tower-service v0.3.3
[2m│[0m   [2m│[0m   [2m└──[0m tracing v0.1.41 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m tower-layer v0.3.3
[2m│[0m   [2m├──[0m tower-service v0.3.3
[2m│[0m   [2m└──[0m tracing v0.1.41 [33m[2m(*)[39m[22m
[2m├──[0m chrono v0.4.41
[2m│[0m   [2m├──[0m iana-time-zone v0.1.63
[2m│[0m   [2m├──[0m num-traits v0.2.19
[2m│[0m   [2m│[0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [1m[34m└──[0m autocfg v1.4.0
[2m│[0m   [2m└──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m├──[0m fastrand v2.3.0
[2m├──[0m futures v0.3.31
[2m│[0m   [2m├──[0m futures-channel v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m├──[0m futures-executor v0.3.31
[2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m├──[0m futures-task v0.3.31
[2m│[0m   [2m│[0m   [2m└──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m futures-io v0.3.31
[2m│[0m   [2m├──[0m futures-sink v0.3.31
[2m│[0m   [2m├──[0m futures-task v0.3.31
[2m│[0m   [2m└──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m├──[0m jsonschema v0.17.1
[2m│[0m   [2m├──[0m ahash v0.8.12
[2m│[0m   [2m│[0m   [2m├──[0m cfg-if v1.0.1
[2m│[0m   [2m│[0m   [2m├──[0m getrandom v0.3.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m cfg-if v1.0.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m├──[0m once_cell v1.21.3
[2m│[0m   [2m│[0m   [2m├──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m└──[0m zerocopy v0.8.25
[2m│[0m   [2m│[0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [1m[34m└──[0m version_check v0.9.5
[2m│[0m   [2m├──[0m anyhow v1.0.98
[2m│[0m   [2m├──[0m base64 v0.21.7
[2m│[0m   [2m├──[0m bytecount v0.6.9
[2m│[0m   [2m├──[0m clap v4.5.40
[2m│[0m   [2m│[0m   [2m├──[0m clap_builder v4.5.40
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m anstream v0.6.19
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m anstyle v1.0.11
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m anstyle-parse v0.2.7
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m utf8parse v0.2.2
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m anstyle-query v1.1.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m colorchoice v1.0.4
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m is_terminal_polyfill v1.70.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m utf8parse v0.2.2
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m anstyle v1.0.11
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m clap_lex v0.7.5
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m strsim v0.11.1
[2m│[0m   [2m│[0m   [2m└──[0m clap_derive v4.5.40 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m heck v0.5.0
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m fancy-regex v0.11.0
[2m│[0m   [2m│[0m   [2m├──[0m bit-set v0.5.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m bit-vec v0.6.3
[2m│[0m   [2m│[0m   [2m└──[0m regex v1.11.1
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m aho-corasick v1.1.3
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m memchr v2.7.5
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m memchr v2.7.5
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m regex-automata v0.4.9
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m aho-corasick v1.1.3 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m memchr v2.7.5
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m regex-syntax v0.8.5
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m regex-syntax v0.8.5
[2m│[0m   [2m├──[0m fraction v0.13.1
[2m│[0m   [2m│[0m   [2m├──[0m lazy_static v1.5.0
[2m│[0m   [2m│[0m   [2m└──[0m num v0.4.3
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m num-bigint v0.4.6
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m num-integer v0.1.46
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m└──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m num-complex v0.4.6
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m num-integer v0.1.46 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m num-iter v0.1.45
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m num-integer v0.1.46 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [1m[34m└──[0m autocfg v1.4.0
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m num-rational v0.4.2
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m num-bigint v0.4.6 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m num-integer v0.1.46 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m iso8601 v0.6.3
[2m│[0m   [2m│[0m   [2m└──[0m nom v8.0.0
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m memchr v2.7.5
[2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m├──[0m memchr v2.7.5
[2m│[0m   [2m├──[0m num-cmp v0.1.0
[2m│[0m   [2m├──[0m once_cell v1.21.3
[2m│[0m   [2m├──[0m parking_lot v0.12.4 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m percent-encoding v2.3.1
[2m│[0m   [2m├──[0m regex v1.11.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m reqwest v0.11.27
[2m│[0m   [2m│[0m   [2m├──[0m base64 v0.21.7
[2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m├──[0m encoding_rs v0.8.35
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m cfg-if v1.0.1
[2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m h2 v0.3.26
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m fnv v1.0.7
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-sink v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m http v0.2.12
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m fnv v1.0.7
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m indexmap v2.9.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m equivalent v1.0.2
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m hashbrown v0.15.4
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m slab v0.4.10
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tokio-util v0.7.15
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-sink v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m tracing v0.1.41 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m http v0.2.12 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m http-body v0.4.6
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m http v0.2.12 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m hyper v0.14.32
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-channel v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m h2 v0.3.26 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m http v0.2.12 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m http-body v0.4.6 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m httparse v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m httpdate v1.0.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m itoa v1.0.15
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m socket2 v0.5.10 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tower-service v0.3.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tracing v0.1.41 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m want v0.3.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m try-lock v0.2.5
[2m│[0m   [2m│[0m   [2m├──[0m hyper-tls v0.5.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m hyper v0.14.32 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m native-tls v0.2.14
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m openssl v0.10.73
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m bitflags v2.9.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m cfg-if v1.0.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m foreign-types v0.3.2
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m foreign-types-shared v0.1.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m once_cell v1.21.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m openssl-macros v0.1.1 (proc-macro)
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m openssl-sys v0.9.109
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m├──[0m cc v1.2.27
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m│[0m   [2m└──[0m shlex v1.3.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m├──[0m pkg-config v0.3.32
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m└──[0m vcpkg v0.2.15
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m openssl-probe v0.1.6
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m openssl-sys v0.9.109 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m tokio-native-tls v0.3.1
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m native-tls v0.2.14 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m ipnet v2.11.0
[2m│[0m   [2m│[0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m│[0m   [2m├──[0m mime v0.3.17
[2m│[0m   [2m│[0m   [2m├──[0m native-tls v0.2.14 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m once_cell v1.21.3
[2m│[0m   [2m│[0m   [2m├──[0m percent-encoding v2.3.1
[2m│[0m   [2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m│[0m   [2m├──[0m rustls-pemfile v1.0.4
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m base64 v0.21.7
[2m│[0m   [2m│[0m   [2m├──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m serde_json v1.0.140 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m serde_urlencoded v0.7.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m sync_wrapper v0.1.2
[2m│[0m   [2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m tokio-native-tls v0.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m tokio-util v0.7.15 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m tower-service v0.3.3
[2m│[0m   [2m│[0m   [2m└──[0m url v2.5.4
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m form_urlencoded v1.2.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m idna v1.0.3
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m idna_adapter v1.2.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m├──[0m icu_normalizer v2.0.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m displaydoc v0.2.5 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m icu_collections v2.0.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m displaydoc v0.2.5 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m potential_utf v0.1.2
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerovec v0.11.2
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m yoke v0.8.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m stable_deref_trait v1.2.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m yoke-derive v0.8.0 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m├──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m└──[0m synstructure v0.13.2
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m zerofrom v0.1.6
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m└──[0m zerofrom-derive v0.1.6 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m synstructure v0.13.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m zerofrom v0.1.6 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m zerovec-derive v0.11.1 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m yoke v0.8.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m zerofrom v0.1.6 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerovec v0.11.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m icu_normalizer_data v2.0.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m icu_provider v2.0.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m displaydoc v0.2.5 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m icu_locale_core v2.0.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m displaydoc v0.2.5 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m litemap v0.8.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tinystr v0.8.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m displaydoc v0.2.5 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerovec v0.11.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m writeable v0.6.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerovec v0.11.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m stable_deref_trait v1.2.0
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m tinystr v0.8.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m writeable v0.6.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m yoke v0.8.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m zerofrom v0.1.6 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m zerotrie v0.2.2
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m displaydoc v0.2.5 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m yoke v0.8.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerofrom v0.1.6 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerovec v0.11.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m smallvec v1.15.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerovec v0.11.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m└──[0m icu_properties v2.0.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m displaydoc v0.2.5 (proc-macro) [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m icu_collections v2.0.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m icu_locale_core v2.0.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m icu_properties_data v2.0.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m icu_provider v2.0.0 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m potential_utf v0.1.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m zerotrie v0.2.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m zerovec v0.11.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m smallvec v1.15.1
[2m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m utf8_iter v1.0.4
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m percent-encoding v2.3.1
[2m│[0m   [2m├──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m serde_json v1.0.140 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m time v0.3.41
[2m│[0m   [2m│[0m   [2m├──[0m deranged v0.4.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m powerfmt v0.2.0
[2m│[0m   [2m│[0m   [2m├──[0m num-conv v0.1.0
[2m│[0m   [2m│[0m   [2m├──[0m powerfmt v0.2.0
[2m│[0m   [2m│[0m   [2m├──[0m time-core v0.1.4
[2m│[0m   [2m│[0m   [2m└──[0m time-macros v0.2.22 (proc-macro)
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m num-conv v0.1.0
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m time-core v0.1.4
[2m│[0m   [2m├──[0m url v2.5.4 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m uuid v1.17.0
[2m│[0m   [2m [0m   [2m├──[0m getrandom v0.3.3 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m└──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m├──[0m reqwest v0.11.27 [33m[2m(*)[39m[22m
[2m├──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[2m├──[0m serde_json v1.0.140 [33m[2m(*)[39m[22m
[2m├──[0m thiserror v2.0.12
[2m│[0m   [2m└──[0m thiserror-impl v2.0.12 (proc-macro)
[2m│[0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m├──[0m tokio-process v0.2.5
[2m│[0m   [2m├──[0m crossbeam-queue v0.1.2
[2m│[0m   [2m│[0m   [2m└──[0m crossbeam-utils v0.6.6
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m cfg-if v0.1.10
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m lazy_static v1.5.0
[2m│[0m   [2m├──[0m futures v0.1.31
[2m│[0m   [2m├──[0m lazy_static v1.5.0
[2m│[0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m├──[0m mio v0.6.23
[2m│[0m   [2m│[0m   [2m├──[0m cfg-if v0.1.10
[2m│[0m   [2m│[0m   [2m├──[0m iovec v0.1.4
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m│[0m   [2m├──[0m net2 v0.2.39
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m cfg-if v0.1.10
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m└──[0m slab v0.4.10
[2m│[0m   [2m├──[0m tokio-io v0.1.13
[2m│[0m   [2m│[0m   [2m├──[0m bytes v0.4.12
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m byteorder v1.5.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m iovec v0.1.4 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m futures v0.1.31
[2m│[0m   [2m│[0m   [2m└──[0m log v0.4.27
[2m│[0m   [2m├──[0m tokio-reactor v0.1.12
[2m│[0m   [2m│[0m   [2m├──[0m crossbeam-utils v0.7.2
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m cfg-if v0.1.10
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m lazy_static v1.5.0
[2m│[0m   [2m│[0m   [2m│[0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [1m[34m└──[0m autocfg v1.4.0
[2m│[0m   [2m│[0m   [2m├──[0m futures v0.1.31
[2m│[0m   [2m│[0m   [2m├──[0m lazy_static v1.5.0
[2m│[0m   [2m│[0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m│[0m   [2m├──[0m mio v0.6.23 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m num_cpus v1.17.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m├──[0m parking_lot v0.9.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m lock_api v0.3.4
[2m│[0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m scopeguard v1.2.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m parking_lot_core v0.6.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m cfg-if v0.1.10
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m smallvec v0.6.14
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m maybe-uninit v2.0.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m└──[0m rustc_version v0.2.3
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m [0m   [2m└──[0m semver v0.9.0
[2m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [1m[34m [0m   [2m [0m   [2m└──[0m semver-parser v0.7.0
[2m│[0m   [2m│[0m   [2m│[0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [1m[34m└──[0m rustc_version v0.2.3 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m├──[0m slab v0.4.10
[2m│[0m   [2m│[0m   [2m├──[0m tokio-executor v0.1.10
[2m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m crossbeam-utils v0.7.2 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m futures v0.1.31
[2m│[0m   [2m│[0m   [2m├──[0m tokio-io v0.1.13 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m└──[0m tokio-sync v0.1.8
[2m│[0m   [2m│[0m   [2m [0m   [2m├──[0m fnv v1.0.7
[2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m futures v0.1.31
[2m│[0m   [2m└──[0m tokio-signal v0.2.9
[2m│[0m   [2m [0m   [2m├──[0m futures v0.1.31
[2m│[0m   [2m [0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m [0m   [2m├──[0m mio v0.6.23 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m mio-uds v0.6.8
[2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m iovec v0.1.4 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m mio v0.6.23 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m signal-hook-registry v1.4.5 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m tokio-executor v0.1.10 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m tokio-io v0.1.13 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m└──[0m tokio-reactor v0.1.12 [33m[2m(*)[39m[22m
[2m├──[0m tokio-stream v0.1.17
[2m│[0m   [2m├──[0m futures-core v0.3.31
[2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m tokio-util v0.7.15 [33m[2m(*)[39m[22m
[2m├──[0m tokio-tungstenite v0.20.1
[2m│[0m   [2m├──[0m futures-util v0.3.31 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m tungstenite v0.20.1
[2m│[0m   [2m [0m   [2m├──[0m byteorder v1.5.0
[2m│[0m   [2m [0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m [0m   [2m├──[0m data-encoding v2.9.0
[2m│[0m   [2m [0m   [2m├──[0m http v0.2.12 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m httparse v1.10.1
[2m│[0m   [2m [0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m [0m   [2m├──[0m rand v0.8.5
[2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m libc v0.2.173
[2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m rand_chacha v0.3.1
[2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m├──[0m ppv-lite86 v0.2.21
[2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m zerocopy v0.8.25
[2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m└──[0m rand_core v0.6.4
[2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m getrandom v0.2.16
[2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m cfg-if v1.0.1
[2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m libc v0.2.173
[2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m rand_core v0.6.4 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m sha1 v0.10.6
[2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m cfg-if v1.0.1
[2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m cpufeatures v0.2.17
[2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m digest v0.10.7
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m├──[0m block-buffer v0.10.4
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m generic-array v0.14.7
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m└──[0m typenum v1.18.0
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [34m[1m[build-dependencies][39m[22m
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [1m[34m└──[0m version_check v0.9.5
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m└──[0m crypto-common v0.1.6
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m [0m   [2m├──[0m generic-array v0.14.7 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m [0m   [2m└──[0m typenum v1.18.0
[2m│[0m   [2m [0m   [2m├──[0m thiserror v1.0.69
[2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m thiserror-impl v1.0.69 (proc-macro)
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m│[0m   [2m [0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m├──[0m url v2.5.4 [33m[2m(*)[39m[22m
[2m│[0m   [2m [0m   [2m└──[0m utf-8 v0.7.6
[2m├──[0m tower v0.5.2 [33m[2m(*)[39m[22m
[2m├──[0m tower-http v0.5.2
[2m│[0m   [2m├──[0m bitflags v2.9.1
[2m│[0m   [2m├──[0m bytes v1.10.1
[2m│[0m   [2m├──[0m http v1.3.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m http-body v1.0.1 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m http-body-util v0.1.3 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m pin-project-lite v0.2.16
[2m│[0m   [2m├──[0m tower-layer v0.3.3
[2m│[0m   [2m└──[0m tower-service v0.3.3
[2m├──[0m tracing v0.1.41 [33m[2m(*)[39m[22m
[2m├──[0m tracing-subscriber v0.3.19
[2m│[0m   [2m├──[0m nu-ansi-term v0.46.0
[2m│[0m   [2m│[0m   [2m└──[0m overload v0.1.1
[2m│[0m   [2m├──[0m sharded-slab v0.1.7
[2m│[0m   [2m│[0m   [2m└──[0m lazy_static v1.5.0
[2m│[0m   [2m├──[0m smallvec v1.15.1
[2m│[0m   [2m├──[0m thread_local v1.1.9
[2m│[0m   [2m│[0m   [2m└──[0m cfg-if v1.0.1
[2m│[0m   [2m├──[0m tracing-core v0.1.34 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m tracing-log v0.2.0
[2m│[0m   [2m [0m   [2m├──[0m log v0.4.27
[2m│[0m   [2m [0m   [2m├──[0m once_cell v1.21.3
[2m│[0m   [2m [0m   [2m└──[0m tracing-core v0.1.34 [33m[2m(*)[39m[22m
[2m├──[0m url v2.5.4 [33m[2m(*)[39m[22m
[2m└──[0m uuid v1.17.0 [33m[2m(*)[39m[22m
[36m[1m[dev-dependencies][39m[22m
[1m[36m├──[0m chrono v0.4.41 [33m[2m(*)[39m[22m
[1m[36m├──[0m criterion v0.6.0
[1m[36m│[0m   [2m├──[0m anes v0.1.6
[1m[36m│[0m   [2m├──[0m cast v0.3.0
[1m[36m│[0m   [2m├──[0m ciborium v0.2.2
[1m[36m│[0m   [2m│[0m   [2m├──[0m ciborium-io v0.2.2
[1m[36m│[0m   [2m│[0m   [2m├──[0m ciborium-ll v0.2.2
[1m[36m│[0m   [2m│[0m   [2m│[0m   [2m├──[0m ciborium-io v0.2.2
[1m[36m│[0m   [2m│[0m   [2m│[0m   [2m└──[0m half v2.6.0
[1m[36m│[0m   [2m│[0m   [2m│[0m   [2m [0m   [2m└──[0m cfg-if v1.0.1
[1m[36m│[0m   [2m│[0m   [2m└──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m clap v4.5.40 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m criterion-plot v0.5.0
[1m[36m│[0m   [2m│[0m   [2m├──[0m cast v0.3.0
[1m[36m│[0m   [2m│[0m   [2m└──[0m itertools v0.10.5
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m└──[0m either v1.15.0
[1m[36m│[0m   [2m├──[0m itertools v0.13.0
[1m[36m│[0m   [2m│[0m   [2m└──[0m either v1.15.0
[1m[36m│[0m   [2m├──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m oorandom v11.1.5
[1m[36m│[0m   [2m├──[0m plotters v0.3.7
[1m[36m│[0m   [2m│[0m   [2m├──[0m num-traits v0.2.19 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m│[0m   [2m├──[0m plotters-backend v0.3.7
[1m[36m│[0m   [2m│[0m   [2m└──[0m plotters-svg v0.3.7
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m└──[0m plotters-backend v0.3.7
[1m[36m│[0m   [2m├──[0m rayon v1.10.0
[1m[36m│[0m   [2m│[0m   [2m├──[0m either v1.15.0
[1m[36m│[0m   [2m│[0m   [2m└──[0m rayon-core v1.12.1
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m├──[0m crossbeam-deque v0.8.6
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m├──[0m crossbeam-epoch v0.9.18
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m│[0m   [2m└──[0m crossbeam-utils v0.8.21
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m│[0m   [2m└──[0m crossbeam-utils v0.8.21
[1m[36m│[0m   [2m│[0m   [2m [0m   [2m└──[0m crossbeam-utils v0.8.21
[1m[36m│[0m   [2m├──[0m regex v1.11.1 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m serde_json v1.0.140 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m tinytemplate v1.2.1
[1m[36m│[0m   [2m│[0m   [2m├──[0m serde v1.0.219 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m│[0m   [2m└──[0m serde_json v1.0.140 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m└──[0m walkdir v2.5.0
[1m[36m│[0m   [2m [0m   [2m└──[0m same-file v1.0.6
[1m[36m├──[0m pretty_assertions v1.4.1
[1m[36m│[0m   [2m├──[0m diff v0.1.13
[1m[36m│[0m   [2m└──[0m yansi v1.0.1
[1m[36m├──[0m tempfile v3.20.0
[1m[36m│[0m   [2m├──[0m fastrand v2.3.0
[1m[36m│[0m   [2m├──[0m getrandom v0.3.3 [33m[2m(*)[39m[22m
[1m[36m│[0m   [2m├──[0m once_cell v1.21.3
[1m[36m│[0m   [2m└──[0m rustix v1.0.7
[1m[36m│[0m   [2m [0m   [2m├──[0m bitflags v2.9.1
[1m[36m│[0m   [2m [0m   [2m└──[0m linux-raw-sys v0.9.4
[1m[36m└──[0m tokio-test v0.4.4
[1m[36m [0m   [2m├──[0m async-stream v0.3.6
[1m[36m [0m   [2m│[0m   [2m├──[0m async-stream-impl v0.3.6 (proc-macro)
[1m[36m [0m   [2m│[0m   [2m│[0m   [2m├──[0m proc-macro2 v1.0.95 [33m[2m(*)[39m[22m
[1m[36m [0m   [2m│[0m   [2m│[0m   [2m├──[0m quote v1.0.40 [33m[2m(*)[39m[22m
[1m[36m [0m   [2m│[0m   [2m│[0m   [2m└──[0m syn v2.0.103 [33m[2m(*)[39m[22m
[1m[36m [0m   [2m│[0m   [2m├──[0m futures-core v0.3.31
[1m[36m [0m   [2m│[0m   [2m└──[0m pin-project-lite v0.2.16
[1m[36m [0m   [2m├──[0m bytes v1.10.1
[1m[36m [0m   [2m├──[0m futures-core v0.3.31
[1m[36m [0m   [2m├──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[1m[36m [0m   [2m└──[0m tokio-stream v0.1.17 [33m[2m(*)[39m[22m
```

## Duplicate Dependencies
```
bytes v0.4.12
[2m└──[0m tokio-io v0.1.13
[2m [0m   [2m├──[0m tokio-process v0.2.5
[2m [0m   [2m│[0m   [2m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m [0m   [2m├──[0m tokio-reactor v0.1.12
[2m [0m   [2m│[0m   [2m├──[0m tokio-process v0.2.5 [33m[2m(*)[39m[22m
[2m [0m   [2m│[0m   [2m└──[0m tokio-signal v0.2.9
[2m [0m   [2m│[0m   [2m [0m   [2m└──[0m tokio-process v0.2.5 [33m[2m(*)[39m[22m
[2m [0m   [2m└──[0m tokio-signal v0.2.9 [33m[2m(*)[39m[22m

bytes v1.10.1
[2m├──[0m tokio v1.45.1
[2m│[0m   [2m├──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m│[0m   [2m├──[0m tokio-stream v0.1.17
[2m│[0m   [2m│[0m   [2m└──[0m tokio-test v0.4.4
[2m│[0m   [2m│[0m   [2m [0m   [36m[1m[dev-dependencies][39m[22m
[2m│[0m   [2m│[0m   [2m [0m   [1m[36m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m│[0m   [2m└──[0m tokio-test v0.4.4 [33m[2m(*)[39m[22m
[2m└──[0m tokio-test v0.4.4 [33m[2m(*)[39m[22m

cfg-if v0.1.10
[2m├──[0m crossbeam-utils v0.6.6
[2m│[0m   [2m└──[0m crossbeam-queue v0.1.2
[2m│[0m   [2m [0m   [2m└──[0m tokio-process v0.2.5 [33m[2m(*)[39m[22m
[2m├──[0m crossbeam-utils v0.7.2
[2m│[0m   [2m├──[0m tokio-executor v0.1.10
[2m│[0m   [2m│[0m   [2m├──[0m tokio-reactor v0.1.12 [33m[2m(*)[39m[22m
[2m│[0m   [2m│[0m   [2m└──[0m tokio-signal v0.2.9 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m tokio-reactor v0.1.12 [33m[2m(*)[39m[22m
[2m├──[0m mio v0.6.23
[2m│[0m   [2m├──[0m mio-uds v0.6.8
[2m│[0m   [2m│[0m   [2m└──[0m tokio-signal v0.2.9 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m tokio-process v0.2.5 [33m[2m(*)[39m[22m
[2m│[0m   [2m├──[0m tokio-reactor v0.1.12 [33m[2m(*)[39m[22m
[2m│[0m   [2m└──[0m tokio-signal v0.2.9 [33m[2m(*)[39m[22m
[2m├──[0m net2 v0.2.39
[2m│[0m   [2m└──[0m mio v0.6.23 [33m[2m(*)[39m[22m
[2m└──[0m parking_lot_core v0.6.3
[2m [0m   [2m└──[0m parking_lot v0.9.0
[2m [0m   [2m [0m   [2m└──[0m tokio-reactor v0.1.12 [33m[2m(*)[39m[22m

cfg-if v1.0.1
[2m├──[0m getrandom v0.3.3
[2m│[0m   [2m├──[0m tempfile v3.20.0
[2m│[0m   [2m│[0m   [36m[1m[dev-dependencies][39m[22m
[2m│[0m   [2m│[0m   [1m[36m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m│[0m   [2m└──[0m uuid v1.17.0
[2m│[0m   [2m [0m   [2m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m├──[0m half v2.6.0
[2m│[0m   [2m└──[0m ciborium-ll v0.2.2
[2m│[0m   [2m [0m   [2m└──[0m ciborium v0.2.2
[2m│[0m   [2m [0m   [2m [0m   [2m└──[0m criterion v0.6.0
[2m│[0m   [2m [0m   [2m [0m   [2m [0m   [36m[1m[dev-dependencies][39m[22m
[2m│[0m   [2m [0m   [2m [0m   [2m [0m   [1m[36m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m├──[0m parking_lot_core v0.9.11
[2m│[0m   [2m└──[0m parking_lot v0.12.4
[2m│[0m   [2m [0m   [2m└──[0m tokio v1.45.1 [33m[2m(*)[39m[22m
[2m└──[0m thread_local v1.1.9
[2m [0m   [2m└──[0m tracing-subscriber v0.3.19
[2m [0m   [2m [0m   [2m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)

crossbeam-utils v0.6.6 [33m[2m(*)[39m[22m

crossbeam-utils v0.7.2 [33m[2m(*)[39m[22m

crossbeam-utils v0.8.21
[2m├──[0m crossbeam-deque v0.8.6
[2m│[0m   [2m└──[0m rayon-core v1.12.1
[2m│[0m   [2m [0m   [2m└──[0m rayon v1.10.0
[2m│[0m   [2m [0m   [2m [0m   [2m└──[0m criterion v0.6.0 [33m[2m(*)[39m[22m
[2m├──[0m crossbeam-epoch v0.9.18
[2m│[0m   [2m└──[0m crossbeam-deque v0.8.6 [33m[2m(*)[39m[22m
[2m└──[0m rayon-core v1.12.1 [33m[2m(*)[39m[22m

itertools v0.10.5
[2m└──[0m criterion-plot v0.5.0
[2m [0m   [2m└──[0m criterion v0.6.0 [33m[2m(*)[39m[22m

itertools v0.13.0
[2m└──[0m criterion v0.6.0 [33m[2m(*)[39m[22m

lock_api v0.3.4
[2m└──[0m parking_lot v0.9.0 [33m[2m(*)[39m[22m

lock_api v0.4.13
[2m└──[0m parking_lot v0.12.4 [33m[2m(*)[39m[22m

mio v0.6.23 [33m[2m(*)[39m[22m

mio v1.0.4
[2m└──[0m tokio v1.45.1 [33m[2m(*)[39m[22m

parking_lot v0.9.0 [33m[2m(*)[39m[22m

parking_lot v0.12.4 [33m[2m(*)[39m[22m

parking_lot_core v0.6.3 [33m[2m(*)[39m[22m

parking_lot_core v0.9.11 [33m[2m(*)[39m[22m

smallvec v0.6.14
[2m└──[0m parking_lot_core v0.6.3 [33m[2m(*)[39m[22m

smallvec v1.15.1
[2m├──[0m icu_normalizer v2.0.0
[2m│[0m   [2m└──[0m idna_adapter v1.2.1
[2m│[0m   [2m [0m   [2m└──[0m idna v1.0.3
[2m│[0m   [2m [0m   [2m [0m   [2m└──[0m url v2.5.4
[2m│[0m   [2m [0m   [2m [0m   [2m [0m   [2m└──[0m mcp-protocol-sdk v0.2.3 (/home/runner/work/mcp-protocol-sdk/mcp-protocol-sdk)
[2m├──[0m idna v1.0.3 [33m[2m(*)[39m[22m
[2m├──[0m parking_lot_core v0.9.11 [33m[2m(*)[39m[22m
[2m└──[0m tracing-subscriber v0.3.19 [33m[2m(*)[39m[22m
```
