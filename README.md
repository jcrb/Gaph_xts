# Gaph_xts

Ce document étudie la façon de représenter graphiquement des séries temporelles. Il s'appuie sur le blog de [Stochastic Nonsense](http://earlh.com/blog/plotting-in-r/) qui propose une série de 12 leçons sur des astuces graphiques.

Utilise un fichier de données représentant l'évolution du [cours de l'action YAHOO](http://earlh.com/blog/images/2009/07/YHOO-stock-prices-19960412-20090702.csv) du 12 avril 1996 au 2 juillet 2009.

Pour pouvoirtravailler hors-ligne le fichier est savegardé sous __YHOO-stock-prices-19960412-20090702.csv__.

```
'data.frame':  3329 obs. of  7 variables:
 $ Date     : Factor w/ 3329 levels "1996-04-12","1996-04-15",..: 3329 3328 3327 3326 3325 3324 3323 3322 3321 3320 ...
 $ Open     : num  15.2 15.5 15.8 15.9 15.6 ...
 $ High     : num  15.3 15.7 15.9 16 15.8 ...
 $ Low      : num  14.9 15.3 15.3 15.6 15.5 ...
 $ Close    : num  15 15.4 15.7 15.9 15.7 ...
 $ Volume   : int  16919900 12716100 16033900 12312100 26449100 19827800 30979700 15866300 26488700 20323100 ...
 $ Adj.Close: num  15 15.4 15.7 15.9 15.7 ...
 ```