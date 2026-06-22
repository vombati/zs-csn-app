# zs-csn-app

PWA kalkulačka pro výpočet impedance ochranné smyčky Zs.

**Normy:** IEC 60364-4-41 · IEC 60364-6 · ČSN 33 2000-4-41 · ČSN 33 2000-6

## Funkce
- Výpočet Zs = √(Rs² + Xs²) s reaktancí vedení
- Teplotní korekce dle typu izolace (PVC/XLPE/EPR/MIN)
- Podmínka výpočtu: Zs ≤ 2/3 · U₀/Ia (IEC 60364-6)
- Podmínka měření: Zs ≤ U₀/Ia (IEC 60364-6)
- Automatický násobek Ia pro MCB B/C/D + čas 0.4s/5s
- Protokol ke zkopírování nebo tisku PDF

## Nasazení (GitHub Pages)
1. Vytvoř repo `zs-csn-app`
2. Nahraj všechny soubory (index.html, manifest.json, sw.js, icon-*.png)
3. Settings → Pages → Deploy from branch: main / root
4. Na iPhone: Safari → Sdílet → Přidat na plochu
