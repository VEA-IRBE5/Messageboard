# Messageboard
- Visiem te ir rediģēšanas piekļuve :)
- Lūdzu netaupiet aprakstošos komentārus, tas pēc tam atvieglos atskaites rakstīšanu
- Ja kaut kas nav skaidrs, droši prasiet Jēkabam


# ----------------------------------------------------------------
# Manuālis - TLDR versija
## Inicializācija
1. git config --global user.name "Vards Uzvards"
2. git config --global user.email "epasts@mail.com"
3. git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
4. git config --global init.defaultBranch main
5. git config --list
6. git init
7. git remote add IRBE5 https://github.com/VEA-IRBE5/[Repository name].git (Elektronika/Mehatronika/Programmejums)

## Lietošana lokāli
1. git pull IRBE5 [Branch name] (lejupielādē zaru no repozitorijas)
2. git branch [branch name] (izveido jaunu zaru)
3. git switch [branch name] (pārslēdzas uz zaru)
4. git add .
5. git commit -m "text" (izņem -m "text" ja gribi izmantot teksta editoru)
6. git push IRBE5 [Branch name] (augšupielādē zara saturu uz repozitoriju no tava datora)
7. Uz main zaru izmaiņas nestumj pa taisno, veido atsevišķu zaru, tad caur pull request apvieno ar main
8. Iepriekšējais neattiecas uz README koriģēšanu githubā

## Github pull rquest
1. Spiež Pull requests, tad zaļā poga
2. compare branch izvēlas kā pievienojamo zaru
3. create pull rquest
4. Labajā pusē pievieno rewievers (galvenais inženieris + visi nodaļas inženieri)
5. Kad visi apstiprina, sāna zars tiek apvienots ar main zaru
6. Sāna zaru tad var droši dzēst ārā



# ----------------------------------------------------------------
# Zaru lietošana
- Katrā repozitorijā tikai galvenajam nodaļas inženierim ir atļauja rediģēt main zaru
- Bez šīs atļaujas mēģinājums veikt push uz main zaru tiks noraidīts
- Kad uzsāk izmaiņas kādai projekta daļai (piem. viena no iespiedplatēm, vai perifērijas izveide), tās veido savā zarā
- Ar pull request veic zaru apvienošanu, katru pull request ir jāapstiprina visiem nodaļas dalībniekiem + galvenais inženieris

## Zaru lietošanas procedūra
#### 1. Atver git bash konsoli
#### 2. Konsolē: git branch [branch name]
- Ievadē nav vajadzīgas [] kvadrātiekavas
- Ja ievada bez jaunā zara vārda, konsolē uzrāda visus esošos zarus, un kurā tu atrodies
#### 3. Konsolē: git switch [branch name]
- Pārslēdzas uz norādīto zaru
#### 4. Var veikt add un commit kā parasti
#### 5. Kad veic push, norāda pareizo zara nosaukumu
#### 6. Lai dzēstu zaru, Konsolē: git branch -d [branch name]
- Zaru nevar izdzēst, ja tu tajā atrodies
- main zaru iesaku nedzēst
