# 移行性
本システムに要求されるシステム移行性について、以下に示す。

### | データ移行
* データ移行については、「移行に際して検討すべき事項」を参照

### | 業務移行
* 並行稼働するシステムとの連携を図りつつ移行を実施すること
* 移行計画書を作成すること

## 移行に際して検討すべき事項
|検討事項|
|:---|
|![image](./image/portability.png)|


|【 注釈 】|
|:---|
|本項では **「移行性」** について参考例を記載いたします。 **「移行」には** 、データ移行、システム移行及び業務運用移行の３つの要素があります。大規模な情報システムにおいては、既存の情報システムから新しい情報システムにデータ移行とシステム移行（新情報システム稼働）を行い、一定期間並行稼働させた後に、業務運用移行を行う場合もあります。他方で、中小規模の情報システムにおいては、３要素全ての移行を休日に実施する場合もあります。<br>いずれの場合においても、業務の安定的な継続が最重要課題であるため、移行の各ステップにおいて状況を評価し、最悪の場合でも既存の情報システムへ切り戻せるような計画と、プロセスの準備を要求しておくことが必要です。<br>移行元である既存の情報システム、業務、運用について、対象を漏れなく抽出します。抽出に当たり、既存の運用・保守事業者の協力が不可欠となるため、事前に移行調査に必要となる既存事業者の要員確保について調整しておくことが重要です。移行対象の抽出後、移行に際する制限事項を整理します。例えば、月次の締め処理がある業務の場合、「月末の締め処理が完了するまでは移行不可」といった事項を明確にします。<br>ここでは、移行先への移行手段を詳細に記載する必要はなく、後工程にて定義します。|
