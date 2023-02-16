# RISC Zero Rust Starter Template

Welcome to the RISC Zero Rust Starter Template! This template is intended to give you a starting point for building a project using the RISC Zero zkVM. Throughout the code are comments labelled `TODO` in places where we expect projects will need to modify the code.

TODO: Replace this README with a README for your project
TODO: Verify whether the included `.gitignore`, `LICENSE`, and `rust-toolchain` files are appropriate to your project

***

RISC Zero Rust Starter 템플릿에 오신 것을 환영합니다! 이 템플릿은 RISC Zero zkVM을 사용하여 프로젝트를 빌드하기 위한 시작점을 제공하기 위한 것입니다. 코드 전체에 프로젝트가 코드를 수정해야 할 것으로 예상되는 곳에는 'TODO'라는 레이블이 붙은 코멘트가 있습니다.

TODO: 이 README를 프로젝트의 README로 바꿉니다
TODO: 포함된 ".gitignore", "License" 및 "rust-toolchain" 파일이 프로젝트에 적합한지 확인합니다.

## Quick Start

First, make sure [rustup](https://rustup.rs) is installed. This project uses a [nightly](https://doc.rust-lang.org/book/appendix-07-nightly-rust.html) version of [Rust](https://doc.rust-lang.org/book/ch01-01-installation.html). The [`rust-toolchain`](rust-toolchain) file will be used by `cargo` to automatically install the correct version.

To build all methods and execute the method within the zkVM, run the following command:

```
cargo run
```

This is an empty template, and so there is no expected output (until you modify the code).

***
먼저 [rustup](https://rustup.rs)이(가) 설치되어 있는지 확인합니다. 이 프로젝트는 [https://doc.rust-lang.org/book/appendix-07-nightly-rust.html) 버전의 [Rust](https://doc.rust-lang.org/book/ch01-01-installation.html))를 사용합니다. ['rust-toolchain'](rust-toolchain) 파일은 화물에서 자동으로 올바른 버전을 설치하는 데 사용됩니다.

zkVM 내에서 모든 메서드를 빌드하고 메서드를 실행하려면 다음 명령을 실행합니다:

```
cargo run
```
이것은 빈 템플릿이므로 코드를 수정할 때까지 예상되는 출력이 없습니다.


## How to create a project based on this template

Search this template for the string `TODO`, and make the necessary changes to implement the required feature described by the `TODO` comment. Some of these changes will be complex, and so we have a number of instructional resources to assist you in learning how to write your own code for the RISC Zero zkVM:
 * The [Getting Started section](https://www.risczero.com/docs) of the [RISC Zero website](https://www.risczero.com) is a great place to get started. There are additional explainers and overviews on our website as well.
 * Example projects are available in our [risc0/risc0-rust-examples repository](https://www.github.com/risc0/risc0-rust-examples).
 * Reference documentation for our Rust crates is available at [docs.rs], including the [RISC Zero zkVM crate](https://docs.rs/risc0-zkvm), the [RISC Zero zkVM guest crate](https://docs.rs/risc0-zkvm-guest), the [RISC Zero build crate](https://docs.rs/risc0-build), and others (the full list is available at [https://github.com/risc0/risc0/blob/main/README.md]).
 * Our [main repository](https://www.github.com/risc0/risc0).

***
이 템플릿에서 문자열 'TODO'를 검색하고 'TODO' 주석에 설명된 필수 기능을 구현하기 위해 필요한 변경을 수행하십시오. 이러한 변경 사항 중 일부는 복잡하므로 RISC Zero zkVM용 코드를 직접 작성하는 방법을 배울 수 있는 여러 가지 교육 리소스가 있습니다:
 * [RISC Zero 웹사이트](https://www.risczero.com)의 [Getting Started](시작하기) 섹션은 시작하기에 좋은 곳입니다. 저희 웹사이트에도 추가 설명자와 개요가 있습니다.
 * 예제 프로젝트는 [risc0/risc0-rust-rust-remission 저장소](https://www.github.com/risc0/risc0-rust-examples)에서 사용할 수 있습니다.
 * Rustcrate에 대한 참조 문서는 [RISC Zero zkVM crate](https://docs.rs/risc0-build), the RISC Zero zkVM guest crate](https://docs.rs/risc0-zkvm-guest), the RISC Zero 빌드 crate)(https://github.com/risc0/risc0/blob/main/ 및 기타)를 포함하여 [docs.rs]에서 확인할 수 있습니다(전체 목록은 [https://docs.rs/risc0-zkvm),]에서 확인할 수 있습니다README.md]).
 * [주 저장소](https://www.github.com/risc0/risc0).


## Stable Versions
By default, this template depends on the latest version of RISC Zero: the `main` branch of our [main repository](http://www.github.com/risc0). This gives you access to our latest features and improvements. If you would prefer to use our more stable published crates, we have tags matching those crates that you can use, e.g. `v0.11.1`.
***
기본적으로 이 템플릿은 최신 버전의 RISC Zero([주 리포지토리]의 '주' 분기)에 따라 달라집니다(http://www.github.com/risc0). 이를 통해 NAT의 최신 기능 및 향상된 기능에 액세스할 수 있습니다. 보다 안정적으로 발행된 상자를 사용하고 싶다면 'v0.11.1'과 같이 사용할 수 있는 상자와 일치하는 태그가 있습니다.

## Contributor's Guide
We welcome contributions to documentation and code via PRs and GitHub Issues on our [main repository](http://www.github.com/risc0), this repository, or any of our other repositories.
***
우리는 [기본 저장소](http://www.github.com/risc0), 이 저장소 또는 기타 저장소의 PR 및 GitHub 문제를 통해 문서 및 코드에 기여하는 것을 환영합니다.

## Video Tutorial
For a walk-through of how to build with this template, check out this [excerpt from our workshop at ZK HACK III](https://www.youtube.com/watch?v=Yg_BGqj_6lg&list=PLcPzhUaCxlCgig7ofeARMPwQ8vbuD6hC5&index=5).
***
이 템플릿을 사용하여 구축하는 방법에 대한 자세한 내용은 다음 [ZK HACK III 워크숍의 예시](https://www.youtube.com/watch?v를 참조하십시오=Yg_BGqj_6lg&list=PLCPzhUaCxlCgig7ofeARMPwQ8vbuD6hC5&index=5).

## Questions, Feedback, and Collaborations
We'd love to hear from you on [Discord](https://discord.gg/risczero) or [Twitter](https://twitter.com/risczero).
***
[Discord](https://discord.gg/risczero) 또는 [Twitter](https://twitter.com/risczero))에서 귀하의 의견을 듣고 싶습니다.
