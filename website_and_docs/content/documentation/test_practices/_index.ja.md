---
title: "ガイドラインとレコメンデーション"
linkTitle: "ガイドライン"
chapter: true
weight: 12
description: >
  Some guidelines and recommendations on testing from the Selenium project.
---

{{% pageinfo color="warning" %}}
<p class="lead">
   <i class="fas fa-language display-4"></i> 
   Page being translated from 
   English to Japanese. Do you speak Japanese? Help us to translate
   it by sending us pull requests!
</p>
{{% /pageinfo %}}

「ベストプラクティス」に関するメモ：このドキュメントでは、"ベストプラクティス"というフレーズを意図的に避けています。
すべての状況に有効なアプローチはありません。
"ガイドラインとレコメンデーション"というアイデアを好みます。
これらを一通り読み、特定の環境でどのアプローチが効果的かを慎重に決定することをお勧めします。

機能テストは、多くの理由で適切に行うのが困難です。
まるでアプリケーションの状態、複雑さ、および依存関係が、テストを十分に難しくしないと思えるほど、ブラウザ（特にクロスブラウザの非互換性）を扱うのは、良いテストの作成を難しくします。

Seleniumは、機能的なユーザーインタラクションを簡単にするツールを提供しますが、適切に設計されたテストスイートの作成には役立ちません。
この章では、機能的なWebページの自動化に取り組む方法に関するアドバイス、ガイドライン、および推奨事項を提供します。

この章では、長年にわたって成功を収めてきたSeleniumの多くのユーザーの間で人気のあるソフトウェア設計パターンを記録します。
