---
title: オブザーバビリティ(可観測性)
status: Completed
category: コンセプト
tags: ["プロパティ", "", ""]
---

オブザーバビリティとは、システムが実用的な洞察をどの程度出力できるかを決める性質のことを指します。
オブザーバビリティにより、ユーザーはシステム外部への出力を元にそのシステムの状態を理解し、(是正)措置を取ることが可能になります。

コンピューターシステムは、CPU時間・メモリ・ディスク容量といった低水準のシグナルや、APIの応答時間・エラー数・秒間トランザクション数などを含む高水準でビジネスに直結するシグナルを観測することで評価されます。
可観測なシステムは、いわゆるオブザーバビリティツールと言われる専門のツールで**観測**(もしくは監視)されます。
オブザーバビリティツールの一覧は[クラウドネイティブ ランドスケープのオブザーバビリティセクション](https://landscape.cncf.io/?group=projects-and-products&view-mode=card#observability-and-analysis--observability)で見られます。

可観測なシステムは、有意義かつ実用的なデータを運用者に提供し、運用者が(インシデントへのより素早い対応や開発者の生産性向上といった)好ましい結果を出すことを可能にします。
システムのダウンタイムとともに、手間のかかる手作業での仕事も少なくなります。

結果として、システムの運用コストと開発コストは、そのシステムがどれだけ可観測なのかに大きく影響を受けるでしょう。