# GIT verziókezelés

- Helyi REPO inicializálása:
    > git init
- A helyi REPO ellenőrzése:
    > git status
- Előkésztjük a commitolásra, feltesszük a színpadra (Stage), indexelés:
    > git add . (a 'pont' minden állományra vonatkozik)

    > git status
- Commit, az új verzió létrehozása:
    > git commit -m "firstCommit" (Helyi REPO inicializálása.)

    > git status
- Távoli REPO létrehozása (a GitHub oldalon)
- Összekapcsoljuk a távoli REPO-t a helyivel (legelső alkalommal):
    > git remote add origin https://token@github.com/dalecooper74/TestRepo03.git
- Kiválasztjuk az ágat (branch), az ágat a távoli REPO-ban:
    > git push -u origin master (legelső alkalommal)

    > git push (a további alkalmakkor)
- Token használata (ezzel azonosítjuk magunkat a GitHub-on)

## Publikálás
- A publikálandó file neve index.html
- Settings > Pages > Branch non-ból kiválasztottuk a master-t > save
- Action-ban látható a publikálási folyamat
- Minden commit után automatikusan újra megtörténik a "deploy" az oldallal.