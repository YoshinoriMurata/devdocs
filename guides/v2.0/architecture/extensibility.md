---
layout: default
group: arch-guide
subgroup: Architectural Basics
title: Extensibility and modularity
menu_title: 
menu_node: 
menu_order: 
github_link: architecture/extensibility.md
---

<h2 id="m2arch-whatis-overview">拡張性とモジュール化</h2>


製品<i>拡張性</i>は製品の機能セットを拡張することがいかに簡単かを解説します。拡張可能な製品は初期の計画段階からカスタマイズと改良のために設計されています。インストールしたものの機能セットの増大、現在の機能の強化、サードパーティソフトウェアとの融合を簡単に行えるように設計されています

最大限の拡張性は全てのMagento開発の要素において我々のゴールでした。主なタスクである送付は個別のモジュールにパッケージ化されており、あなたがサードパーティから購入したあるいは自身で作成したモジュールをインストールすることによって店舗の機能を拡張できます。各運送業者へのロジックの詳細は個別のモジュールにパッケージ化されていますが、運送業者の追加と削除はモジュールを追加または削除するだけで簡単に行えます。製品フレームワークはルーティングと他のコアアプリケーション機能への共通のロジックを提供します。

Magentoのカスタマイズ能力をこれらのトピックを通して御覧ください:

* 拡張機能開発をサポートするグローバル製品機能
* フロントエンドカスタムの容易さ


<h3>製品を拡張可能にするものとは？</h3>

<i>Magento拡張性</i> は開発者と小売業者に事業が拡大するにつれ定期的に店舗の機能を拡張するために製品のビルトイン機能を記述します。 

製品を拡張するための試みは以下のものに影響されています: 

* <b>製品の仕組みを導く構造原則</b> Magentoモデルのソフトウェア開発の中心はコアコードの編集よりも取り換えか拡張の実践です。 
この手法はあなたの店舗を大々的にカスタマイズしつつ我々が提供するテストされたコードの保全性を保つことを可能にします。


* <b>オープンソースソフトウェアにてエクステンションの作成と管理</b>Magentoは開発のコミュニティによりコミュニティのためにオープンソース技術によって作られております。オープンソースツールのComposerを依存性の管理に使用しています。全リストは<a href="{{ site.gdeurl }}architecture/tech-stack.html">技術スタック</a>を御覧ください

* <b>コーディング規格</b> 
PHPとJavaScriptのスタンダードベストプラクティスを保持することによってコードベースの健全さを確保します。MagentoはPHP用のZendフレームワークコーディング規格の殆どに適応しております。更なる情報は<a href="{{ site.gdeurl }}coding-standards/bk-coding-standards.html">コーディング規格</a>を御覧ください。

* <b>アップグレードとバージョニングストラテジー</b> 
Magentoにはソフトウェアコンポーネントの依存性の問題を回避するのを補助するためのよく定義されたアップグレードとバージョニングのストラテジーがあります。Magentoフレームワークのバージョンとモジュールのバージョンが互換性があるかを確認後にモジュールを追加してください。更なる情報は<a href="{{ site.gdeurl }}install-gde/bk-install-guide.html">インストールガイド</a>を御覧ください。


<h3 id="m2arch-related">関連するトピック</h3>
<a href="{{ site.gdeurl }}architecture/archi_perspectives/ABasics_intro.html">Architectural basics</a>






