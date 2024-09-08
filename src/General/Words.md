# 用語集

## <div id="soldiers_num">兵数</div>
[ユニット数](#unit_num)と同義。

## <div id="unit_num">ユニット数</div>
[兵数](#soldiers_num)とも呼ばれる。<br>
兵士ユニット1体につき設定されている数値。
コストのようなもの。<br>
兵士の種類によって設定されている数値が異なる。<br>
例えば、狙撃兵は1体につきユニット数が1だが、決闘車は1体につきユニット数が10となっている。<br>
各兵士ユニットごとのユニット数の詳細は[兵士解説](/src/Battle/Soldiers.md)を参照。

## <div id="max_injured_unit_num">負傷兵ユニット最大値</div>
[最大負傷兵数](#max_injured_num)と同義。
ステータスの項目にはこの名称で記載されている。

## <div id="max_injured_num">最大負傷兵数</div>
ステータスの項目では『[負傷兵ユニット最大値](#max_injured_unit_num)』と記載されている。<br>
病院に収まりきる[負傷兵](#injured_unit)ユニット数の最大値のこと。<br>
この数値を超える[負傷兵](#injured_unit)が発生した場合、本来[損失](#lost_unit)ではなかった兵士が治療を受けられない状態のため、[損失](#lost_unit)してしまうようになる数値。

## <div id="injured_unit">負傷兵</div>
戦闘を経て負傷し、病院での治療を行わないと戦線復帰できない兵士。

## <div id="lost_unit">損失(兵)</div>
戦闘を経て死亡し、消滅してしまった兵士。<br>
[負傷兵転化率](#revive_prob)の確立で[蘇生](#revive)を行うことが可能。
