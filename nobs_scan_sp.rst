Single Point
============

.. image:: image/nobs_scan_sp.png

Single Pointは、ON点とOFF点を交互に観測する方法です。

*Integration Time* : ON点の積分時間です。OFF点も同じ時間になります。

*Beam Rotation Angle* : 今回は使用しませんので、そのままで大丈夫です。

*Sequence Pattern* : スキャン順序のパターンを決めます。数字はReferenceタブにおけるID番号、\*はON点を示します。通常はOFF, ON, OFF,...と繰り返すので、1\*としておきます。最初はOFF、最後はONという制約もあります。

*Number of Sequence* : 上で記述したパターンを繰り返す数です。Single Pointの場合は、観測状況により各自で観測を止めることが通常ですので、長めに設定しておけば良いです。ただし、ON, OFF, RSKYをそれぞれ1カウントとして、1000未満でなければなりません。

*Calibration Mode* : キャリブレーションモードの選択です。今回はR-SKYを使用します。

*Integration Time* : キャリブレーション時の積分時間です。Single Pointの場合は、通常、ON点やOFF点と同じ時間にします。

*Calibration Interval* : キャリブレーションを行う頻度を指定します。通常10分から15分間隔で行います。単位はsequenceです。Single PointではON、OFFの1サイクルにかかる時間は、移動を考慮するとON点積分時間の3倍と考えることが多いです。

