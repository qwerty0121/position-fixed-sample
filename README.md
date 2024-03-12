# position-fixed-sample

## 概要

`position: fixed` を設定した要素に `transform` / `perspective` / `filter` に `none` 以外が設定された祖先要素がある場合の挙動を確認するサンプルコード。

## 背景

`position: fixed` を設定した要素に対し、 `transform` / `perspective` / `filter` に `none` 以外が設定された祖先要素がある場合、 `position: fixed` を設定した要素はビューポートではなくその祖先要素に対して相対的に配置されるようになる。

そのため、その挙動を確認するためにこのサンプルコードを作成した。

## 注意事項

IE では上記の挙動とはならず、 `position: fixed` を設定した要素はビューポートに対して相対的に配置される。
