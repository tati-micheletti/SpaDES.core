# Setup

## Platform

|setting  |value                        |
|:--------|:----------------------------|
|version  |R version 3.4.4 (2018-03-15) |
|system   |x86_64, linux-gnu            |
|ui       |X11                          |
|language |en_CA:en                     |
|collate  |en_CA.UTF-8                  |
|tz       |America/Edmonton             |
|date     |2018-07-09                   |

## Packages

|package      |*  |version    |date       |source                                          |
|:------------|:--|:----------|:----------|:-----------------------------------------------|
|quickPlot    |*  |0.1.4      |2018-07-09 |Github (PredictiveEcology/quickPlot@cba38b4)    |
|reproducible |*  |0.2.1.9000 |2018-07-09 |Github (PredictiveEcology/reproducible@575b903) |
|SpaDES.core  |*  |0.2.0      |2018-07-09 |local (PredictiveEcology/SpaDES.core@52b7f26)   |
|SpaDES.tools |   |0.2.0.9000 |2018-07-09 |Github (PredictiveEcology/SpaDES.tools@c02ae99) |

# Check results

3 packages

|package       |version | errors| warnings| notes|
|:-------------|:-------|------:|--------:|-----:|
|NetLogoR      |0.3.3   |      0|        0|     0|
|SpaDES.addins |0.1.1   |      0|        1|     0|
|SpaDES        |2.0.2   |      0|        1|     0|

## NetLogoR (0.3.3)
Maintainer: Sarah Bauduin <sarahbauduin@hotmail.fr>  
Bug reports: https://github.com/PredictiveEcology/NetLogoR/issues

0 errors | 0 warnings | 0 notes

## SpaDES.addins (0.1.1)
Maintainer: Alex M Chubaty <alex.chubaty@gmail.com>  
Bug reports: https://github.com/PredictiveEcology/SpaDES.addins/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘SpaDES.addins’ can be installed ... WARNING
Found the following significant warnings:
  Warning: no DISPLAY variable so Tk is not available
See ‘/home/achubaty/Documents/GitHub/SpaDES/SpaDES.core/revdep/checks/SpaDES.addins.Rcheck/00install.out’ for details.
```

## SpaDES (2.0.2)
Maintainer: Alex M Chubaty <alex.chubaty@gmail.com>  
Bug reports: https://github.com/PredictiveEcology/SpaDES/issues

0 errors | 1 warning  | 0 notes

```
checking whether package ‘SpaDES’ can be installed ... WARNING
Found the following significant warnings:
  Warning: no DISPLAY variable so Tk is not available
  Warning: replacing previous import ‘SpaDES.tools::checkGDALVersion’ by ‘reproducible::checkGDALVersion’ when loading ‘SpaDES’
  Warning: replacing previous import ‘SpaDES.tools::getGDALVersion’ by ‘reproducible::getGDALVersion’ when loading ‘SpaDES’
  Warning: replacing previous import ‘SpaDES.tools::fastMask’ by ‘reproducible::fastMask’ when loading ‘SpaDES’
See ‘/home/achubaty/Documents/GitHub/SpaDES/SpaDES.core/revdep/checks/SpaDES.Rcheck/00install.out’ for details.
```

