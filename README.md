# Git
Git használata

Git egy verziókezelő rendszer, amely lehetővé teszi a kódok, szövegek, fájlok és egyéb digitális tartalmak nyomon követését és karbantartását. A Git segítségével nyomon követheti a változtatásokat, visszaállíthatja az előző verziókat, és együttműködhet másokkal egy projekten.

Git telepítése

A Git telepítéséhez először meg kell győződnie arról, hogy a számítógépén telepítve van a Git. A Git letölthető és telepíthető a Git webhelyéről: https://git-scm.com/downloads.

Git kezdőknek

A Git használatának megkezdéséhez létre kell hoznia egy git repositoryt, amely egy könyvtár, amelyben a kódot vagy más digitális tartalmat tárolja.

Git repository létrehozása

Egy git repository létrehozásához használja a következő parancsot:

    git init

Ez a parancs létrehoz egy .git könyvtárat a meglévő könyvtárban. A .git könyvtár tartalmazza a Git repository összes metaadatát, beleértve a változtatások történetét is.

Fájlok hozzáadása a git repositoryhoz

A fájlok hozzáadásához a git repositoryhoz használja a következő parancsot:

    git add <fájl neve>

Például a következő parancs hozzáadja a my_file.txt fájlt a git repositoryhoz:

    git add my_file.txt

Fájlok commitálása a git repositoryhoz

A fájlok commitálásához a git repositoryhoz használja a következő parancsot:

    git commit -m <üzenet>

A -m kapcsoló lehetővé teszi a commit üzenet megadását. A commit üzenet leírja a commitban végrehajtott változtatásokat.

Például a következő parancs commitálja a my_file.txt fájlt a következő üzenettel:

    git commit -m "Hozzáadta a my_file.txt fájlt"

Git használata példákkal

Íme néhány példa a Git használatára:

Egy új funkció hozzáadása egy projekthez:

    git add my_new_feature.py
    git commit -m "Hozzáadta a my_new_feature.py funkciót"

 Egy hiba kijavítása egy projektben:

    git add my_file.py
    git commit -m "Javította a my_file.py fájlban lévő hibát"

Egy korábbi verzió visszaállítása:

    git checkout <commit hash>

Például a következő parancs visszaállítja a repositoryt a commit hash verziójára:

    git checkout 7f09d59

Egy projektben végzett változtatások összehasonlítása:

    git diff <commit hash>

Például a következő parancs összehasonlítja a repositoryt a commit hash verziójával:

    git diff 7f09d59


Git alapvető parancsok

A Git alapvető parancsai a következők:

    git init: létrehoz egy git repositoryt
    
    git add: hozzáadja a fájlokat a git repositoryhoz
    
    git commit: commitolja a változtatásokat a git repositoryba
    
    git checkout: visszaállítja a repositoryt egy korábbi verzióra
    
    git diff: összehasonlítja a repositoryt két verzió között
    
