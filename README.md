# aozora_classification_2023
https://github.com/shibuiwilliam/aozora_classification を参考に構築しました, keras, tensorflowのverに伴い記述を変更している箇所があります.

青空文庫から, 作者1人につき20作品を学習データとし, 1作品をテストデータとして\
20人の作者の作品(テストデータ)を作者推定し, 精度を示します。\
character-level CNN を tensorflow + keras で実装し, 作者推定を実現

対象の20人の作者は "sakusya_list.txt" に記載

精度は 16/20 (エポック数 50)
