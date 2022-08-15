# Git


GIT: nyílt forráskódú, verziókezelő.

CÉL: a fejlesztés alatt álló dokumentumok, tervek, forráskódú és egyéb olyan adatok verzióinak kezelésére amelyeken több ember dolgolgozik egyidejűleg.

Fogalmak:

Repository: egy tároló, mely a verzió követett fáljok számos verzióját tárolni tudja.

Fajtái:

Remote (központi szerver): a távoli szerveren lévő központi repositoryt jelenti, mely segítségével tartják a kapcsolatot egymással a fejlesztők. (ORIGIN névvel hivatkozznak).

Local: a helyi számítógépen lévő klónozott repository, a tényleges fejlesztés ezen megy végbe.

Private: a repository csak regisztrált és engedélyezett felhasználók férhetnek hozzá.

Public: a repositoryhoz bárki hozzáférhet és használhatja.


Working directory (wd): munkakönyvtár ahol dolgozzunk.

Commit: wd egy bármikor visszaállítható verziója. Eltéréseket tárolja el elsősorban.

Fork: a szerveren megosztott repository helyi másolata.

Revision number: a repositoryban tárolt változatokra ennek segítségével tudunk hivatkozni.

Konfliktus: akkor keletkezik amikor a verziókezelő rendszer nem tud dönteni a változtatások sorsáról.


Staged: módosított fáljok (állapotok, verziók, tartalom).

Snapshot: egy adott pillanatban, időpontban a könyvtárak, fájlok aktuális állapotát tartalmát, verzióját jelenti.

Stash: biztosítja a wd változásainak ideiglenes elmentését egy biztonságos helyre.


Origin: az a remote, ahonnan eredetileg klónoztuk.

Branch (ág): a fejlesztés egymástól függetlenül, több ágon is folyhat.

Merge: két ág összeolvasztásának folyamata.

Head: hivatkozás a commitra.


Push: egy remote-ra feltölti a nálunk létező, de onnan még hiányzó commitokat.

Pull: a központi szerverre felküldött változások, commitok letöltése merge-ölése az aktuális branch-ba.

Patch: a létrehozott változásokat egy fájlban írunk ki, amely beolvasztható automatikusan a repoba de ha a repo rev nb nem haladt tovább a patch-ben tárolt értékhez képest.

Fetch: egy remote-ról letölti az ott jelen lévő, de a lokális repositoryból még hiányzó commitokat.



