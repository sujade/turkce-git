# Git auf Südrheinfränkisch (Nordbadisch)

S' alldäglich Gschwätz än deitschä Endwigglagrubbä, wu mid `git`
(iwwasezd: `Simbl` odda `Depp`) schaffä, isch ofd ä args Denglisch.
_"Konsch du mol bidde pullä"_ odda _"Hasch du scho puschd"_ sin blos zwai
vun dennä Konschdrugdzionä wu sich komisch ohorchä.

D' Lesung isch Gid uff Südrheinfränkisch (Nordbadisch)!

## Vorschläg

Do sin zwai Tabellä mid Vorschläg wie ma onnaschd schwätzä konn.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | uffmachä              |
| add         | adden              | däzudo                |
| blame       | blamen             | oschwärzä             |
| pull        | pullen             | ziegä                 |
| push        | pushen             | driggä                |
| clone       | clonen             | nochmachä             |
| fetch       | fetchen            | holä                  |
| branch      | branchen           | vaäschdlä             |
| commit      | commiten           | eireichä              |
| rebase      | rebasen            | (nei) sordierä        |
| diff        | diffen             | unnascheidä           |
| merge       | mergen             | zommädo               |
| fork        | forken             | weggawlä              |
| stash       | stashen            | zrignemmä             |
| tag         | taggen             | edikedierä            |
| cherry-pick | cherry-picken      | Rosinä pickä          |
| checkout    | checkouten         | rausholä              |
| squash      | squashen           | zommädriggä           |

Do sinn noch ä paar Vorschläg (Wu ned gonz so ernschd gmoind sinn)

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Simbl                      |
| github        | github             | Simblzendral               |
| gitlab        | gitlab             | Simbllabor                 |
| gitea         | gitea              | Simbltee                   |
| blame         | blame              | Oschwärzä                  |
| bitbucket     | bitbucket          | Gebissoima                 |
| repository    | repo               | Laga                       |
| branch        | branch             | Aschd                      |
| commit        | commit             | Eireichung                 |
| log           | log                | Brodokoll                  |
| pull request  | pull request       | Ofrog zum ziegä            |
| merge request | merge request      | Ofrog zum zommädo          |
| stash         | stash              | Bunga                      |
| status        | status             | Zuschdond                  |
| tag           | tag                | Edikedd                    |
| origin        | origin             | Urschbrung                 |
| master        | master             | Kabbo                      |
| main          | main               | Dallmäs                    |

## Beischbiel

    - Konnsch du denn Aschd, wu e grad umgschriewä häb, ziegä un änd Simblzendral driggä?

    - Dodäfor häwwe ä neis Laga uffgmachd, machs grad noch un nemm da än Endwigglungsaschd.

    - Noi, drigg des glei zum Kabbo äm Urschbrung!

    - Du konnsch än dä Simbloschwärzung sä, wu des gennad had.

    - I häb grad weggawl'd un die Ennarungä aus meim Bunga eigreichd.

    - Mach ä Ofrog zum ziegä, wenn mid äm zommädo ferdich bisch!

    - Äm beschdä mir pickä und die Rosinä aus'm Dallmäsaschd raus.

    - Gawl se än dä Simblzendral!

    - Wenn ferdich bisch, konnsch die Ofrog zum ziegä glei zommädriggä un zommädo.

    - Äm Simblbrodokoll konsch lesä, wär zledschd ä zommädriggde Eireichung zommädo had.

## Simbl uff Sidreinfrängisch benutzä

Wer's gar ned abwardä konn, do isch'd Olaidung, mid därrä du Simbl uff Sidreinfrängisch än deo Konsol neibringsch. Weil där Simbl koi Umlaud zulassd, missä ma en dennä Kommandos leider dodruff verzichdä. Nemm die Ennarungä än deina `~/.gitconfig` vor:

    git config --global alias.mach-uff init
    git config --global alias.mach-noch clone
    git config --global alias.zieg pull
    git config --global alias.do-daezu add
    git config --global alias.drigg push
    git config --global alias.schlombar 'push --force'
    git config --global alias.aschd branch
    git config --global alias.vaaeschdlae branch
    git config --global alias.reich-ei commit
    git config --global alias.sordier-nei rebase
    git config --global alias.unnascheid diff
    git config --global alias.do-zommae merge
    git config --global alias.bungar stash
    git config --global alias.edikedier tag
    git config --global alias.hol-raus checkout
    git config --global alias.brodokoll log
    git config --global alias.zuschdond status
    git config --global alias.schwaerz-o blame

Un du die Zeil än deinärä `~/.bashrc` eidragä (Oda was a imma uff deim Bedribssischdem hasch):

    alias simbl=git
