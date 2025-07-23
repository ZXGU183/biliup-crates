# biliup(-rs) crates

[![Chat on Matrix](https://img.shields.io/badge/Matrix-%23biliup--fork%3Amozilla.org-06D7A0?logo=matrix)](https://matrix.to/#/#biliup-fork:mozilla.org)

把 [biliup 系](https://github.com/biliup) 项目中的 `/crates` 目录链接到一个仓库内

## 作为子模块集成

```shell
git submodule add https://github.com/ZXGU183/biliup-crates.git crates
```

# stream-gears
通过 PyO3 导出**上传** B 站与**下载** FLV、HLS 流的函数供Python调用,
支持时间或文件大小分段，同时解决拉取FLV流花屏的问题。

## Dev
1. Install the latest [Rust compiler](https://www.rust-lang.org/tools/install)
2. Install [maturin](https://maturin.rs/): `$ pip3 install maturin`
```shell
$ python -m venv .env
$ source .env/bin/activate
$ maturin develop
```

## Credits
感谢 [Genteure](https://github.com/Genteure) 提供帮助