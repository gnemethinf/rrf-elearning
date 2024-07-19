<!--
author:    Németh Gábor
languange: hu-hu
narrator:  Hungarian Female
version:   1.0
email:     gnemeth@inf.u-szeged.hu
import: https://raw.githubusercontent.com/liaTemplates/JSCPP/master/README.md
import: https://raw.githubusercontent.com/liaTemplates/vtk/master/README.md
-->

# Az állatorvosi ló

Ebben a részben sok olyan dolgot bemutatok, amely előjöhet egy tananyag kapcsán.

## Narráció


--{{1}}--
Narrációs megjegyzést fűzhetünk a tananyaghoz annak érdekében, ha szeretnénk valamivel kiegészíteni.

## Animáció

{{1-2}}
Ez a bekezdés animált.

{{2}}
Ez a bekezdés is animált, de az előző eltűnt, mert az csak a 2-es animációig látszik.

{{3}}
Ez a bekezdés is animált, de az előző ott maradt.

## Táblázat

| Tananyag rész | Fejezet | Becsült idő |
| -------- | :------: | -------: |
| eXeLearning     |   Egy lecke készítése   |    20:00 perc |


## Háromdimenziós modell

@VTK.loadIframe(https://kitware.github.io/vtk-js-datasets/data/vti/head-binary-zlib.vti)

## Programkód blokkok 

```cpp 
#include <iostream>
using namespace std;

int main() {
    for (int i = 0; i <5; i++) {
        cout << "LiaScript-et használok!" << endl;
    }
    return 0;
}
```
@JSCPP.eval

## HTML kód

<lia-keep>
<details>
<summary>Egy rövid összefoglaló</summary>
<p>
Ha egy dologról nem akarunk sokat megjeleníteni az oldalon, de valójában kifejtenénk, akkor használhatjuk a <tt>details</tt> címkét. 
</p>
</details>
</lia-keep>


