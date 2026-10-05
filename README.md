# -surveying_projects

surveying_projects_apps

## Tools

- [Field Clock](./field-clock/) — 測量現場向けのiPhoneシステム時刻表示時計
- [Elevation Survey](./elevation_survey.html)
- [SIMA Converter](./sima_converter.html)
- [Taiyou Kansoku](./taiyou_kansoku.html)

## Sample data / provenance

SIMA Converterの入力例と「合成デモを入れる」で読み込む座標は、公開デモ用に作成した合成値です。X=100、Y=200を基点に10ずつ増減させた四角形であり、実在地点、測量成果、実案件、座標系との対応はありません。点名は変換ルールを示すための例で、保存名は `demo_synthetic.SIM` です。

Taiyou Kansokuの緯度・経度欄には具体的な地点の例示値を置いていません。利用者が自分で入力する欄です。

既存のself-testは計算・入力形式・出力形式の回帰確認用です。実案件の正確性、現場での適合性、測量成果としての利用を保証する公開Evidenceではありません。過去のcommit messageにあるExcel/PDFとの照合記述について、元資料の由来・公開許諾はこのrepositoryから確認できません。その記述を、現在の合成デモの由来や実案件の検証済み宣言として扱わないでください。

入力データや観測結果をissue / PR / commitへ添付する場合は、公開してよいデータかを確認してください。
