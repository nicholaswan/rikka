# Qiniu Plugin

[中文版][version-zh]

Inner name `qiniu`.

## Description

This plugin use Qiniu Cloud CND to store your image.

## Options

You should provide Qiniu ACCESSKEY, SECRETKEY, Bucket name and Bucket host.

ACCESSKEY and SECRETKEY should be add into your env variable, use key `RIKKA_QINIU_ACCESS` and `RIKKA_QINIU_SECRET`.

Bucket name and bucket host should be provide use command line option:

`-bname` for the bucket name.

`-bhost` for bucket host.

## Guide

See [Rikka Deploy Guide with Qiniu Plugin on DaoCloud][qiniu-plugin-guide].

[version-zh]: https://github.com/7sDream/rikka/blob/master/plugins/qiniu/README.zh.md
[qiniu-plugin-guide]: https://github.com/7sDream/rikka/wiki/%E4%BD%BF%E7%94%A8%E4%B8%83%E7%89%9B%E4%BA%91%E6%8F%92%E4%BB%B6
