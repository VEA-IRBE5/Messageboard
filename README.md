# Messageboard
Visiem te ir rediģēšanas piekļuve :)


# Zaru lietošana
- Katrā repozitorijā tikai galvenajam nodaļas inženierim ir atļauja rediģēt main zaru
- Bez šīs atļaujas mēģinājums veikt push uz main zaru tiks noraidīts
- Kad uzsāk izmaiņas kādai projekta daļai (piem. viena no iespiedplatēm, vai perifērijas izveide), tās veido savā zarā
- Ar pull request veic zaru apvienošanu, katru pull request ir jāapstiprina visiem nodaļas dalībniekiem + galvenais inženieris

## Zaru lietošanas procedūra
1. Atver git bash konsoli
2. Konsolē: git branch [branch name]
- Ja ievada bez jaunā zara vārda, konsolē uzrāda visus esošos zarus, un kurā tu atrodies
3. Konsolē: git switch [branch name]
- Pārslēdzas uz norādīto zaru
4. Var veikt add un commit kā parasti
5. Kad veic push, norāda pareizo zara nosaukumu
6. Lai dzēstu zaru, Konsolē: git branch -d [branch name]
- Zaru nevar izdzēst, ja tu tajā atrodies
- main zaru iesaku nedzēst
