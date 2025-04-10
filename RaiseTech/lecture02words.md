Web
→ 正式名称は「World Wide Web（ワールドワイドウェブ）」。
インターネット上で情報を閲覧・公開するためのハイパーテキストシステムのこと。W3とも呼ぶ。
(ハイパーテキストシステムとは？)

Webアプリケーション
→ インターネット経由でWebブラウザ上で利用できるアプリケーションのこと。
「システム対人間」の関係で、人間が利用することを前提としたもの。

Webサービス
→ インターネット上で利用できるサービスの総称で、Webブラウザから利用できる。
「システム対システム」で連携している関係及びサービスのこと。
Webサイトの閲覧やメールの送受信、買い物、決済、予約などがWebサービスに含まれる。

WebアプリケーションとWebサービスの違い
→ Webサービスはコンピュータ同士の連携なのに対して、Webアプリはコンピュータと人間がつながることを指す。

クライアント
→ IT用語におけるクライアント（client）とは、ネットワーク上のサービスを利用するコンピュータやソフトウェアを指す。
ユーザーが直接操作するデバイス（パソコンやスマートフォンなど）もクライアントに含まれる。

サーバ
→ ネットワークに接続されたコンピューターで、他のコンピューターからの要求に応答してデータや情報を提供するもの。
Webサーバー、メールサーバー、ファイルサーバー、FTPサーバー、プロキシサーバー、データーベースサーバー、アプリケーションサーバ、DNSサーバ、 DHCPサーバなどがある。
(FTP？プロキシ？DNS？DHCP？)

キャッシュ
→ 一時的に保存したデータや処理結果のこと。Webサイトやアプリの表示を高速化するために利用される。

キャッシュサーバ
→ ネットワーク上で頻繁にアクセスされるデータのコピーを保存し、オリジンサーバーに代わってデータの配信を行うサーバーのこと。
Webサイトやアプリケーションのパフォーマンスを向上させるために用いられる。
(オリジンサーバー？)

ブラウザ
→ インターネット上のホームページ（Webサイト）を閲覧するためのソフトウェア。Webブラウザとも呼ばれ、パソコンやスマートフォンで利用できる。
(第2回講義を見直して補足入れたい。﻿)

TCP/IP
→ Transmission Control Protocol/Internet Protocolの略称。
インターネットや企業ネットワークで利用されている通信プロトコル（通信方式）のこと。
TCP（Transmission Control Protocol）とIP（Internet Protocol）という2つのプロトコルで構成されています。﻿
(TCPとIPについて調べる？)

スタンドアロン
→ 他のリソースに依存せず、単独で機能することを意味する。直訳すると「孤立」という意味らしい。

HTTP
→ Hypertext Transfer Protocolの略称。
WebブラウザとWebサーバー間でデータの送受信を行うプロトコル（通信規約）のこと。
インターネット上でWebサイトにアクセスする際に使用され、Webページのコンテンツが配信される。

HTTPS
→ Hypertext Transfer Protocol Secureの略称。
HTTP通信をより安全に行うためのURIスキームである。「HTTPS」はプロトコルではなく、SSL/TLSプロトコルなどによって提供されるセキュアな接続の上でのHTTP通信をさす。
(URI？スキーム？URIスキーム？SSL/TLSプロトコル？SSL？TLS？セキュア？)

WebAPI
→ Web Application Programming Interfaceの略称。
Web技術を用いて異なるアプリケーション間でデータや機能を連携させる仕組みのこと。
HTTPやHTTPSなどの通信プロトコルを利用して、Webサイトやアプリケーションに別のサービスの機能を組み込むことができる。

API
→ アプリケーション・プログラミング・インタフェースの略称。
ソフトウェアやアプリケーション同士をつなぐ技術です。アプリケーションの開発を効率化したり、機能拡張を容易にしたりする効果があります。﻿

インターフェース
→ 情報技術において、インタフェースは、情報の授受を行うシステム間のプロトコル、または、その接続を行う部分をいう。
コンピュータシステムの各部、あるいはシステム間の接続や、人間と機械の間の入出力部などがある。インターフェイスあるいはインターフェースなどと表記することもある。

JSON
→ JavaScript Object Notationの略称。
JavaScriptのオブジェクトの表記法を基にしたデータ形式のこと。テキストベースで、人間が読みやすく機械が解析しやすいという特徴がある。
(テキストベース？オブジェクト？)

XML
→ Extensible Markup Languageの略称。
文章の見た目や構造を記述するためのマークアップ言語の一種。
主にデータのやりとりや管理を簡単にする目的で使われ、記述形式がわかりやすいという特徴がある。
Web技術で頻繁に登場する、HTMLをはじめ、SVG、XHTML、XSLT、RFTなども、 XML と同じマークアップ言語のひとつ。

JSONとXML何が違う？
→JSON は、文字列、数値、オブジェクトなどの限られた範囲のデータ型のみをサポートする。
JSON はブールアレイもサポートできますが、XML ではタグを追加しないとサポートできません。
ただし、XML のほうが柔軟性が高く、バイナリデータやタイムスタンプなどの複雑なデータ型をサポートしています。
JSONオブジェクトは順序付けられたデータ構造ではないため、内容の順序を保証できない。
XMLのは「編集がしづらい」「コンピュータ処理の負荷が大きい」「XMLを扱うことのできる技術者が少ない」などが挙げられる。
(ブールアレイ？バイナリデータ？タイムスタンプ？)

データベース
→ コンピューター上で整理・管理されたデータの集まりのことで、データを1つの場所に集約して管理するシステムのこと。

URL
→ Uniform Resource Locatorの略称。
インターネット上の情報資源（文書や画像など）の場所を示す技術方式です。Webサイトの住所とも呼ばれる。

通信
→ 送り手が情報を送り、また受け手が情報を受けることである。 特に電気的な手段を用いて行われる場合（電気通信）を指す場合が多い。

動的
→ 何らかの対象やその構成要素の設定や内容、属性、動作などが実際の稼働時に決定されたり、操作や状況に応じて変化していくこと

静的
→ あらかじめ設定された内容や属性などが、実際の稼働時に変化しないこと

フォーマット
→ 「形式」や「初期化」を意味する言葉。ラテン語のforma（姿・形）に由来する。
「ハードディスクをフォーマットする」は、ハードディスクを使用可能な形式（初期状態）に整えることを指す。

メソッド
→ 目的を達成するための手順や手法、方式、やり方などを意味する言葉。

HTTPメソッド
→ Webブラウザとサーバー間でやり取りする際に、クライアントからサーバーに実行させるアクションを指示するもの。

GETメソッド
→ WebブラウザなどのクライアントからWebサーバーに情報を取得するために使用されるHTTPプロトコルのリクエストメソッドのこと。

POSTメソッド
→ WebブラウザなどのクライアントからWebサーバに情報を送信するHTTPリクエストの一種。
主に、HTMLのフォームに入力された情報をサーバーに受け取るために使用されます。﻿
(メソッドは、第2回講義を見直して補足したい。)
