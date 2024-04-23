# Git auf Bayerisch (Boarisch)

De Redarei jeden Dog in Programiarateams, de `git` (übasetzd: `Daepp` oder `Doldi`) heanehma, is meist as feinste Denglish.
_"Konst du moi pullen, zefix"_ oder _"Host du scho gepusht"_ san nur zwoa der Konstruktionen de se komisch ohean.

Git auf Boarisch heift da!

## Vorschläge

Do sigst zwoa Tabein mit Vorschlägen de ma jeden Dog hernehma ko.

| Verb        | Derzeit werd gnoma | Vorschlog             |
|-------------|--------------------|-----------------------|
| init        | initten            | ofanga                |
| add         | adden              | dazuadoa              |
| pull        | pullen             | ziang                 |
| push        | pushen             | drucka                |
| clone       | clonen             | nochmacha             |
| fetch       | fetchen            | hoin                  |
| branch      | branchen           | obzwoang              |
| commit      | commiten           | übergem               |
| rebase      | rebasen            | neimacha              |
| diff        | diffen             | vergleicha            |
| merge       | mergen             | zamdoa                |
| fork        | forken             | goben                 |
| stash       | stashen            | bunkan                |
| tag         | taggen             | makian                |
| cherry-pick | cherry-picken      | Weibierl rausbicka    |
| checkout    | checkouten         | nehma                 |
| blame       | blamen             | hihenga               |

| Substantiv    | Derzeit werd gnoma | Vorschlog            |
|---------------|--------------------|----------------------|
| git           | git                | Doldi                |
| github        | github             | Doldidrahgreiz       |
| gitlab        | gitlab             | Doldilaboa           |
| gitea         | gitea              | DoldiTää             |
| bitbucket     | bitbucket          | Beissakiebe          |
| repository    | repo               | Schupfa              |
| branch        | branch             | Zwoagal              |
| commit        | commit             | Übergabe             |
| log           | log                | Tagebuach            |
| pull request  | pull request       | Ziangvorschlag       |
| merge request | merge request      | Zamdoavorschlag      |
| stash         | stash              | Vasteck              |
| status        | status             | Zuastand             |
| tag           | tag                | Makierung            |
| origin        | origin             | Uasprung             |
| master        | master             | Moasta               |

## Beispiele

    - Konst du des Zwoagal, des i grod umgschriem hob, ziang und zum Doldidrahgreiz drucka?

    - Dafür hob i an neia Schupfn aufgmacht, machs no und nimm as Programiarazwoagal.

    - Na, druck des gleiche zum Moasta im Uasprung!

    - I hob grod a Zwoagal gmacht und de neian Sachan ausm Schupfn dazua do.

    - Mach an neia Ziangvorschlag, wennst mit dem zamdoa fertig bist!

    - Am besten mia bickan uns de Weibierl ausm Moastazwoagal raus.

    - Goibe moi aufn Doldidrahgreiz!

## Doldi auf Boarisch hernehma

Wer den nextn Schrid macha mog, do is a Anleitung, de Doldi auf Boarisch in Dei Kastl bringt. Da Doldi koane Umlaute ko, miasma in de Befehle leider drauf vazichtn. Mach de Änderunga in deina  `~/.gitconfig`:

    git config --global alias.ofanga init
    git config --global alias.nochmacha clone
    git config --global alias.ziang pull
    git config --global alias.dazuadoa add
    git config --global alias.drucka push
    git config --global alias.pfusch 'push --force'
    git config --global alias.zwoagal branch
    git config --global alias.uebergem commit
    git config --global alias.neimacha rebase
    git config --global alias.vergleicha diff
    git config --global alias.zamdoa merge
    git config --global alias.bunkan stash
    git config --global alias.makian tag
    git config --global alias.nehma checkout
    git config --global alias.tagebuach log
    git config --global alias.zuastand status
    git config --global alias.hihenga blame

Dann duast de Zeilen do in dei `~/.bashrc` (oda wost hoid sunst hernimmst auf deina Kistn):

    alias doldi=git
