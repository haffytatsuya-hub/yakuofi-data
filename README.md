# yakuofi-data

アプリ「薬オフィ」が起動時に取りに来る配信用データです。厚生労働省・PMDA の公開情報から自動で作っています。

- `manifest.json` … データの版（version）・形の番号（schema）・各ファイルのハッシュ
- `data/*.json` … 医薬品データ（薬価基準収載品目・供給状況・RMP・添付文書の場所・包装単位 など）

作り方はアプリ本体のリポジトリの `tools/update_data.py` を参照。
