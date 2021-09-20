# Messageboard
Visiem te ir rediģēšanas piekļuve :)


# Zaru lietošana
- Katrā repozitorijā tikai galvenajam nodaļas inženierim ir atļauja rediģēt main zaru
- Kad uzsāk izmaiņas kādai projekta daļai (piem. viena no iespiedplatēm, vai perifērijas izveide), tās veido savā zarā
  - Procedūra, lai uzsāktu: pull no main, pirmās izmaiņas, tad commit un push uz jaunu zaru ar citu nosaukumu (piem. plate1)
  - Procedūra, kad izstrādā: pull no šī zara, push uz šo zaru
  - Procedūra, kad pabeigts: push uz zaru, tad veic pull request: main <- zars 
- Ar pull request veic zaru apvienošanu, katru pull request ir jāapstiprina visiem nodaļas dalībniekiem + galvenais inženieris
