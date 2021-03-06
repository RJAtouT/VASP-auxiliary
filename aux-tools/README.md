# VASP-auxiliary

## aux-band

	=== Usage: aux-band [-s] [-f filename] FLAG ===
	[1]: band(Atom Type),           [2]: band(Atom)
	[3]: band(Atom Type & Orbital), [4]: band(Atom & Orbital)
	Get E_fermi from 'OUTCAR' & Selected flag = FLAG[default 1]
	band restore ...

`preview[aux-band]`

	  Coord.         KPOINT           Energy     Occ      Mo       W       S
	 0.00000    (0.00|0.50|0.00)    -35.8702   1.000  0.9852  0.0001  0.0020
	 0.00636    (0.00|0.49|0.00)    -35.8702   1.000  0.9852  0.0001  0.0020
	 0.01272    (0.00|0.48|0.00)    -35.8702   1.000  0.9850  0.0001  0.0020
	 0.01907    (0.00|0.47|0.00)    -35.8702   1.000  0.9852  0.0001  0.0020
	 0.02543    (0.00|0.47|0.00)    -35.8702   1.000  0.9851  0.0001  0.0020
	 0.03179    (0.00|0.46|0.00)    -35.8702   1.000  0.9852  0.0001  0.0020
	 0.03815    (0.00|0.45|0.00)    -35.8702   1.000  0.9852  0.0001  0.0020
	 0.04450    (0.00|0.44|0.00)    -35.8703   1.000  0.9852  0.0001  0.0020
	 0.05086    (0.00|0.43|0.00)    -35.8703   1.000  0.9851  0.0001  0.0020
	 0.05722    (0.00|0.42|0.00)    -35.8703   1.000  0.9852  0.0001  0.0020
	 0.06357    (0.00|0.42|0.00)    -35.8703   1.000  0.9850  0.0001  0.0020
	 0.06993    (0.00|0.41|0.00)    -35.8703   1.000  0.9850  0.0001  0.0020
	 0.07629    (0.00|0.40|0.00)    -35.8704   1.000  0.9851  0.0001  0.0020
	 0.08265    (0.00|0.39|0.00)    -35.8704   1.000  0.9851  0.0001  0.0020
	 0.08901    (0.00|0.38|0.00)    -35.8704   1.000  0.9852  0.0001  0.0020
	 0.09536    (0.00|0.38|0.00)    -35.8705   1.000  0.9851  0.0001  0.0020

## aux-dos

	[1]: pdos(Atom Type),           [2]: pdos(Atom)
	[3]: pdos(Atom Type & Orbital), [4]: pdos(Atom & Orbital)
	Selected flag = FLAG[default 1]
	dos restore ...

`preview[aux-dos]`

	   Energy       DOS        iDOS          Mo           W           S
	  -5.8518   42.4696    140.6082      4.2381      9.7197     14.0045
	  -5.8317   45.9318    141.5287      4.7025     10.2552     15.2109
	  -5.8117   49.2997    142.5167      5.1731     10.7678     16.3765
	  -5.7916   50.2701    143.5241      5.2461     10.8711     16.7722
	  -5.7716   49.0932    144.5079      4.8885     10.6816     16.4885
	  -5.7516   47.6753    145.4634      4.3965     10.5814     16.1259
	  -5.7315   46.2648    146.3905      3.9941     10.4584     15.7315
	  -5.7115   43.5289    147.2628      3.6989      9.7954     14.8766
	  -5.6914   39.6178    148.0568      3.5182      8.5314     13.6694
	  -5.6714   36.3919    148.7861      3.4798      7.2118     12.7654
	  -5.6514   34.3152    149.4737      3.4487      6.2265     12.2731
	  -5.6313   31.5967    150.1069      3.1558      5.4315     11.4919
	  -5.6113   27.1320    150.6507      2.5247      4.6295      9.9993
	  -5.5912   22.5166    151.1019      1.8244      3.9846      8.3786
	  -5.5712   20.2140    151.5070      1.3945      3.8029      7.5538
	  -5.5512   20.6858    151.9215      1.3220      4.0858      7.7145
	  -5.5311   22.1632    152.3657      1.4528      4.4714      8.2295
	  -5.5111   22.7587    152.8218      1.6131      4.5789      8.4198
	  -5.4910   21.9658    153.2620      1.7223      4.3223      8.1078
	  -5.4710   20.3167    153.6691      1.7551      3.8739      7.4906
	  -5.4510   18.5052    154.0400      1.6881      3.4492      6.8244

