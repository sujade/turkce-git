# Türkçe Git

Günlük iletişimde Türkçe konuşan geliştiriciler genelde `git`i
(`Mankafa` ya da `Salak`) genelde plaza Türkçesi şeklinde kullanıyor.
_"Pullayabilir misin acaba?"_ ya da  _"Pushladın mı? Bir saattir bekliyorum"_ 
bunun bazı örnekleri.

Bu yüzden sizler için Türkçe Git'i hazırladım!
Daha doğrusu git-auf-deutsch'tan _"çatalladım"_.
(Lütfen _fazla_ ciddiye almayın. <3")

## Öneriler

Aşağıdaki tabloda hem günlük kullanımlar hem de öneriler yer alıyor.

| Fiil        | Günlük Kullanım    | Öneri                 |
|-------------|--------------------|-----------------------|
| init        | initlemek          | açmak                 |
| add         | addlemek           | eklemek               |
| blame       | blamelemek         | suçlamak              |
| pull        | pullamak           | çekmek                |
| push        | pushlamak          | itmek                 |
| clone       | clonelamak         | nüsha almak           |
| fetch       | fetchlemek         | getirmek              |
| branch      | branchlemek        | dallandırmak          |
| commit      | commitlemek        | işlemek               |
| rebase      | rebaselemek        | (yeniden) temel atmak |
| diff        | difflemek          | ayırt etmek           |
| merge       | mergelemek         | birleştirmek          |
| fork        | forklamak          | çatallamak            |
| stash       | stashlemek         | zulalamak             |
| tag         | taglemek           | işaretlemek           |
| cherry-pick | cherry-picklemek   | kiraz seçmek          |
| checkout    | checkoulamak       | teslim almak          |
| squash      | squashlamak        | ezmek                 |


| İsim          | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Salak                      |
| github        | github             | Salak Merkezi              |
| gitlab        | gitlab             | Salak Laboratuvarı         |
| gitea         | gitea              | Salak Çayı                 |
| blame         | blame              | Suçlamak                   |
| bitbucket     | bitbucket          | Kırıntı Kovası             |
| repository    | repo               | Depo                       |
| branch        | branch             | Dal                        |
| log           | log                | Kütük                      |
| pull request  | pull request       | Çekme İsteği               |
| merge request | merge request      | Birleçtirme İsteği         |
| stash         | stash              | Zula                       |
| status        | status             | Durum                      |
| tag           | tag                | Etiket                     |
| origin        | origin             | Kaynak                     |
| master        | master             | Efendi                     |
| main          | main               | Ana                        |

## Örnekler

    - Şu üzerinde çalıştığım dalı çekip Salak Merkezine gönderir misin?
    
    - Ya ben onun için yeni depo açmıştım, nüshasını alıp geliştirme dalına göndersene.

    - Olmaz hocam, anadaki efendiye gönder.
    
    - Ne değiştiğini görmek için salak suçlamasına bakabilirsin.

    - Daha şimdi dallandırdım ve değişiklikleri benim zulaya yazdım.

    - Birleştirme işin bittiyse bir çekme isteği aç.
    
    - En iyisi ana daldan kiraz toplayalım.

    - Salak Merkezinden çatalla.
    
    - İşin bitince çekme isteğini hemen ezip birleştirebilirsin.
    
    - Salak kütüğüne bakıp en son kimin ezilmiş bir işlemeyi birleştirdiğini görebilirsin.

## Salağı Türkçe kullanmak

Bu işi bir üst seviyeye taşımak istiyorsan ve Salağı Türkçe kullanmak istiyorsan aşağıdaki değişikleri `~/.gitconfig` dosyana ekleyebilirsin:

    git config --global alias.ac init
    git config --global alias.nusha clone
    git config --global alias.cek pull
    git config --global alias.ekle add
    git config --global alias.it push
    git config --global alias.zorla-it 'push --force'
    git config --global alias.dal branch
    git config --global alias.dallandir branch
    git config --global alias.isle commit
    git config --global alias.temel-at rebase
    git config --global alias.ayirt-et diff
    git config --global alias.birlestir merge
    git config --global alias.zulala stash
    git config --global alias.etiketle tag
    git config --global alias.teslim-al checkout
    git config --global alias.kutuk log
    git config --global alias.durum status
    git config --global alias.sucla blame
    git config --global alias.uzaktan remote


Aşağıdaki kısmı da `~/.bashrc` (ya da işletim sistemine göre ne kullanıyorsan) ekle:

    alias salak=git

kaynak: https://github.com/danielauener/git-auf-deutsch.git

Önerileriniz için issue açabilirsiniz.
