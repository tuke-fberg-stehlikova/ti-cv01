# cv01: Príkazový riadok a HTML

Stránka týždňa s teóriou a ukážkami: https://beata.stehlikova.website.tuke.sk/ti/02.html

## Odovzdávaš

V repository *cv01* na GitHub a vo svojom webovom priestore na sigma (`ti/cv01`):

- `index.html`, `style.css`, `photo.jpg`,
- `history.txt` (výpis `history` z terminálu) a `about-me.txt` (napísaný vo vi).

## Hodnotenie

1 bod. Na sigma je stránka v `public_html/ti/cv01` a zobrazuje sa aj s obrázkom (image). Commit a push najneskôr do nasledujúceho cvičenia. Po každom push sa spustia automatické testy; výsledok nájdeš podľa návodu [04 Odovzdávanie](https://beata.stehlikova.website.tuke.sk/navody/04-odovzdavanie.html), časť 6.

## Prompty pre AI

Na miestach `// DOPLŇ` a `[DOPLŇ …]` dopĺňaš sám.

### Ukážka 4: prompt pre AI na prvú stránku

```text
Vytvor mi jednoduchú webovú stránku v HTML5 v slovenčine (lang="sk", kódovanie UTF-8)
a k nej samostatný súbor style.css. Bez JavaScriptu a bez frameworkov (žiadny Bootstrap).

Stránka je jedna (index.html) a má obsahovať:
- header s heading h1 a menu, ktoré odkazuje na section na tej istej stránke
  pomocou kotiev (href="#..."),
- section s headings h2, aspoň dva paragraphs textu, zvýraznené slovo (strong, em),
- nečíslovaný a číslovaný zoznam,
- table s header (thead) a aspoň 3 riadkami, s viditeľným ohraničením buniek,
- image zo súboru photo.jpg v tom istom priečinku, s attribute alt,
- link na externú stránku, ktorý sa otvorí v novej karte prehliadača,
- footer s mojím menom a rokom.

CSS nech je jednoduché a čitateľné: písmo, obmedzená šírka obsahu a centrovanie,
farba headings, menu vedľa seba, ohraničenie table, image nesmie pretiecť mimo stránku.

Do HTML aj CSS daj krátke komentáre po slovensky, ktoré vysvetlia, na čo slúži
každý element, aby som kódu rozumel.

Téma stránky: [DOPLŇ]
```

## Úlohy

**Úloha 2.1: Príprava Kubeflow a zadanie.** Priprav si Kubeflow podľa návodu [04 Odovzdávanie](https://beata.stehlikova.website.tuke.sk/navody/04-odovzdavanie.html), časť 1: v Explorer je hore WEB, dole na stavovej lište je **Go Live**. Ak tam nie je, rozšírenia vráti tento príkaz v termináli:

```bash
code-server --install-extension Natizyskunk.sftp --install-extension yandeu.five-server --install-extension bmewburn.vscode-intelephense-client --install-extension mblode.twig-language-2
```

Potom `F1`, **Developer: Reload Window**. Nastavenie pripojenia na sigma zostáva, netreba ho robiť znova. Prijmi zadanie *cv01* v Classroom 50 (link je vyššie) a repository naklonuj do `~/web/ti/cv01` podľa návodu 04, časti 2 a 3.

**Úloha 2.2: Pieskovisko.** V termináli v Kubeflow si vytvor `~/pieskovisko` a v ňom len príkazmi, bez myši, štruktúru `projekt/css`, `projekt/img` a prázdne súbory `projekt/index.html` a `notes.txt`. Jeden súbor skopíruj, jeden premenuj a jeden zmaž. Po každom kroku to over cez `ls -la`.

**Úloha 2.3: Vi.** V pieskovisku vytvor vo vi súbor `about-me.txt` s tromi riadkami: meno, téma tvojho semestrálneho projektu, jedna vec, ktorú si sa dnes naučil. Ulož a odíď. Otvor ho znova, zmaž riadok cez `dd`, vráť ho cez `u` a odíď bez uloženia cez `:q!`. Cez `cat` over, že súbor má stále tri riadky.

**Úloha 2.4: História.** Na konci práce v termináli ulož históriu do súboru: `history > ~/pieskovisko/history.txt`.

**Úloha 2.5: Stránka cez AI.** Prompt z Ukážky 4 vlož do AI, na koniec doplň tému svojho projektu. Výsledok ulož do `~/web/ti/cv01` ako `index.html` a `style.css`. Image pretiahni myšou z počítača do priečinka `cv01` v Explorer a premenuj ho na `photo.jpg`. Stránku si pozri cez Five Server a čo nesedí, nechaj AI opraviť. Prečítaj komentáre v kóde: každý element musíš vedieť vysvetliť.

**Úloha 2.6: Odovzdanie.** Skopíruj do zadania súbory z pieskoviska: `cp ~/pieskovisko/history.txt ~/pieskovisko/about-me.txt ~/web/ti/cv01/`. Potom commit a push podľa návodu [04 Odovzdávanie](https://beata.stehlikova.website.tuke.sk/navody/04-odovzdavanie.html).

**Úloha 2.7: Upload Folder a kontrola na sigma.** Podľa návodu 04, časť 7: klikni pravým na priečinok `cv01` a v menu úplne dole zvoľ **Upload Folder**. Na sigma tým doplníš aj pretiahnutý image a súbory z terminálu. Potom sa cez `ssh` pripoj na sigma a skontroluj, že v `public_html/ti/cv01` sú tvoje súbory (Ukážka 3). Nakoniec otvor v prehliadači `https://sigma.tuke.sk/student/meno.priezvisko/ti/cv01/`.

**Hodnotenie:** 1 bod. V repository *cv01* na GitHub aj na sigma je funkčná stránka, `history.txt` a `about-me.txt`. Commit a push najneskôr do nasledujúceho cvičenia.

---

# cv01: The command line and HTML

The week page with theory and examples: https://beata.stehlikova.website.tuke.sk/ti/02.html

## What you submit

In the repository *cv01* on GitHub and in your web space on sigma (`ti/cv01`):

- `index.html`, `style.css`, `photo.jpg`,
- `history.txt` (the `history` output from the terminal) and `about-me.txt` (written in vi).

## Grading

1 point. On sigma the page is in `public_html/ti/cv01` and shows with the image. Commit and push by the next lab at the latest. Automatic tests run after every push; find the result following guide [04 Submitting](https://beata.stehlikova.website.tuke.sk/navody/04-odovzdavanie.html), part 6.

## AI prompts

You fill in the `// DOPLŇ` and `[FILL IN …]` places yourself.

### Example 4: an AI prompt for your first page

```text
Create a simple web page in HTML5 (set the lang attribute to the page language,
UTF-8 encoding) and a separate style.css file. No JavaScript and no frameworks
(no Bootstrap).

It is a single page (index.html) and it contains:
- a header with an h1 heading and a menu linking to sections on the same page
  using anchors (href="#..."),
- sections with h2 headings, at least two paragraphs of text, an emphasised word
  (strong, em),
- an unordered and an ordered list,
- a table with a header (thead) and at least 3 rows, with visible cell borders,
- an image from the file photo.jpg in the same folder, with an alt attribute,
- a link to an external website that opens in a new tab,
- a footer with my name and the year.

Keep the CSS simple and readable: font, limited content width and centring,
heading colour, menu items side by side, table borders, the image must not
overflow the page.

Add short comments in English to both the HTML and the CSS explaining what every
element is for, so that I understand the code.

Page topic: [FILL IN]
```

## Tasks

**Task 2.1: Getting Kubeflow ready and the assignment.** Get Kubeflow ready following guide [04 Submitting](https://beata.stehlikova.website.tuke.sk/navody/04-odovzdavanie.html), part 1: Explorer shows WEB at the top, the status bar at the bottom shows **Go Live**. If it does not, this terminal command brings the extensions back:

```bash
code-server --install-extension Natizyskunk.sftp --install-extension yandeu.five-server --install-extension bmewburn.vscode-intelephense-client --install-extension mblode.twig-language-2
```

Then `F1`, **Developer: Reload Window**. The connection settings for sigma stay, you do not have to set them up again. Accept the assignment *cv01* in Classroom 50 (the link is above) and clone the repository into `~/web/ti/cv01` following guide 04, parts 2 and 3.

**Task 2.2: Sandbox.** In the Kubeflow terminal create `~/pieskovisko` and inside it, using commands only and no mouse, the structure `projekt/css`, `projekt/img` and empty files `projekt/index.html` and `notes.txt`. Copy one file, rename one and delete one. Check each step with `ls -la`.

**Task 2.3: Vi.** In the sandbox create a file `about-me.txt` in vi with three lines: your name, the topic of your semester project, one thing you learned today. Save and quit. Open it again, delete a line with `dd`, bring it back with `u` and quit without saving with `:q!`. Check with `cat` that the file still has three lines.

**Task 2.4: History.** At the end of your terminal work save the history into a file: `history > ~/pieskovisko/history.txt`.

**Task 2.5: A page made with AI.** Paste the prompt from Example 4 into an AI and fill in the topic of your project at the end. Save the result into `~/web/ti/cv01` as `index.html` and `style.css`. Drag an image from your computer into the `cv01` folder in Explorer and rename it to `photo.jpg`. View the page with Five Server and let the AI fix whatever is not right. Read the comments in the code: you must be able to explain every element.

**Task 2.6: Submitting.** Copy the sandbox files into the assignment: `cp ~/pieskovisko/history.txt ~/pieskovisko/about-me.txt ~/web/ti/cv01/`. Then commit and push following guide [04 Submitting](https://beata.stehlikova.website.tuke.sk/navody/04-odovzdavanie.html).

**Task 2.7: Upload Folder and the check on sigma.** Following guide 04, part 7: right-click the `cv01` folder and choose **Upload Folder** at the very bottom of the menu. This also gets the dragged image and the files from the terminal to sigma. Then connect to sigma with `ssh` and check that your files are in `public_html/ti/cv01` (Example 3). Finally open `https://sigma.tuke.sk/student/name.surname/ti/cv01/` in the browser.

**Grading:** 1 point. A working page, `history.txt` and `about-me.txt` are in the *cv01* repository on GitHub and on sigma. Commit and push by the next lab at the latest.
