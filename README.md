# [hyper](https://hyper.rs) for WebAssembly: hyper_wasi

A **fast** and **correct** HTTP implementation for Rust. 
This is a fork from the original [hyper](https://github.com/hyperium/hyper) with support for WebAssembly compilation target.
That allows hyper client and server apps to run inside the [WasmEdge Runtime](https://github.com/WasmEdge/WasmEdge#readme) as a lightweight and secure alternative to natively compiled apps in Linux container.

For more details and usage examples, please see the upstream [hyper](https://github.com/hyperium/hyper) source and [these examples](https://github.com/WasmEdge/wasmedge_hyper_demo).

Note: We do not yet support SSL / TLS connections in hyper_wasi yet.


- HTTP/1 and HTTP/2
- Asynchronous design
- Leading in performance
- Tested and **correct**
- Extensive production use
- Client and Server APIs

**Get started** by looking over the [guides](https://hyper.rs/guides).

## Contributing

To get involved, take a look at [CONTRIBUTING](CONTRIBUTING.md).

## License

hyper is provided under the MIT license. See [LICENSE](LICENSE).

