---
title: "Opțiuni de editoare (Linux)"
hide:
  - navigation
  - toc
---

Există două tipuri de editoare folosite pentru a scrie cod (nu doar în C++):

<div class="grid cards" markdown>

- :octicons-file-code-24:{ .lg .middle } **Editoare de text**

    ---

    Un editor de text este un program simplu folosit pentru scrierea și editarea
    codului sursă C++. Exemple de astfel de editoare includ Vim, Emacs, Geany,
    Kate, Sublime Text, și Visual Studio Code, printre altele. Acestea sunt
    ideale pentru editarea de fișiere de cod C++ simple, oferind
    funcționalități de bază precum evidențierea sintaxei și completarea
    automată.

    Editoarele de text consumă mai puțină memorie decât un IDE, însă trebuie să
    fie configurate pentru a putea suporta C++ la un nivel satisfăcător.

    [:octicons-arrow-right-24: Vezi opțiuni](#editoare-de-text)

- :octicons-device-desktop-24:{ .lg .middle } **IDE**

    ---

    Un mediu de dezvoltare integrat (IDE) pentru C++ este un software complex
    care oferă dezvoltatorilor un set complet de instrumente pentru scrierea,
    compilarea, testarea și depanarea codului C++. Exemple de IDE-uri pentru
    C++ includ CLion, Qt Creator și Code::Blocks. Acestea includ
    funcționalități avansate precum depanare interactivă, integrare cu sisteme
    de control al versiunilor, instrumente de profilare și optimizare a
    codului, și multe alte instrumente care facilitează dezvoltarea de
    aplicații complexe în C++. Fiind programe mai complexe, ele consumă mai
    multă memorie și mai mult spațiu, însă oferă toate uneltele necesare.

    [:octicons-arrow-right-24: Vezi opțiuni](#ide-uri)

</div>

## IDE-uri

La capitolul IDE-uri, nu avem așa de multe opțiuni, pentru că un IDE este
fundamental mai complex. Totuși, cele mai bune opțiuni sunt:

<div class="grid cards" markdown>

- **Code::Blocks**

    ---

    Code::Blocks este un IDE gratuit și open-source, dedicat dezvoltării de
    aplicații în limbajul C și C++. Este cunoscut pentru flexibilitatea sa,
    fiind extensibil prin plugin-uri și suportând diverse compilatoare.
    Interfața sa prietenoasă și ușurința de utilizare îl fac o alegere populară
    printre programatorii C/C++. În plus, acesta este editorul implicit pentru
    olimpiadă. Rulează pe Windows, macOS, Linux, FreeBSD și OpenBSD.

    [:octicons-arrow-right-24: Instalare și configurare](./codeblocks.md)

- **Qt Creator**

    ---

    Qt Creator este un IDE cross-platform dezvoltat de Qt Company, perfect
    pentru dezvoltarea în C++. Acesta oferă integrare completă cu Qt Framework,
    un designer vizual pentru interfețe grafice și suport pentru sistemele de
    build CMake și QMake. Qt Creator vine cu instrumente avansate de navigare și
    refactorizare a codului, un debugger integrat și instrumente de profilare
    pentru identificarea și rezolvarea problemelor de performanță. De asemenea,
    este foarte flexibil și poate fi extins prin plugin-uri, făcându-l potrivit
    pentru diverse nevoi ale dezvoltatorilor. Rulează pe Windows, macOS, Linux,
    FreeBSD, OpenBSD și NetBSD.

    [:octicons-arrow-right-24: Instalare și configurare](./qt-creator.md)

- **CLion**

    ---

    CLion este un IDE dezvoltat de JetBrains, specializat în dezvoltarea de
    aplicații în C și C++. Acesta oferă o gamă largă de funcționalități
    avansate, cum ar fi refactorizarea codului, navigarea inteligentă și
    suportul pentru CMake. CLion include un debugger integrat și instrumente de
    analiză a codului care ajută la menținerea unui cod curat și eficient. Este
    apreciat pentru productivitatea pe care o oferă dezvoltatorilor, datorită
    instrumentelor sale avansate și integrării cu diverse sisteme de control al
    versiunilor. Rulează pe Windows, macOS și Linux.

    [:octicons-arrow-right-24: Instalare și configurare](./clion.md)

</div>

!!! warning "Atenție"

    CLion, spre deosebire de celelalte opțiuni, nu este gratis. Totuși, dacă
    ești eligibil, poți avea un cont de student ceea ce îți oferă acces la
    CLion, precum și la alte produse marca JetBrains.

## Editoare de text

La capitolul editoare de text, există multe opțiuni. Totuși, dorim următoarele
calități de la un editor de text pentru C++:

- Syntax highlighting (evidențierea sintaxei), pentru a putea distinge ușor
  cuvintele cheie și a putea citi codul mai ușor;
- Completare automată (și sugestii) pentru a putea completa rapid și
  eficient codul;
- Indentare automată (și formatare), pentru a păstra un stil
  consistent;
- Funcții de căutare și înlocuire;
- Numărarea liniilor și coloanelor;
- Suport pentru extensii;
- Să fie ușor de folosit și să consume puține resurse.

Următoarele editoare îndeplinesc criteriile de mai sus:

<div class="grid cards" markdown>

- **Visual Studio Code**

    ---

    Visual Studio Code este un editor de cod gratuit și open-source, dezvoltat
    de Microsoft. Este extrem de popular datorită integrării sale cu multe
    instrumente de dezvoltare și suportului pentru extensii, oferind o
    experiență de codare puternică și flexibilă.

    [:octicons-arrow-right-24: Instalare și configurare](./visual-studio-code.md)

- **Sublime Text 4**

    ---

    Sublime Text 4 este un editor de text rapid și versatil, cunoscut pentru
    interfața sa curată și performanța excelentă. Este ideal pentru dezvoltatori
    datorită funcțiilor avansate precum evidențierea sintaxei și completarea
    automată, alături de un sistem robust de plugin-uri.

     [:octicons-arrow-right-24: Instalare și configurare](./sublime-text-4.md)

- **Kate**

    ---

    Kate este un editor de text puternic, parte a KDE. Este extensibil prin
    plugin-uri și suportă o gamă largă de limbaje de programare, incluzând C++.
    Este rapid și ușor de utilizat, fiind o alegere populară pentru
    utilizatorii de Linux care folosesc KDE și nu numai.

     [:octicons-arrow-right-24: Instalare și configurare](./kate.md)

- **Geany**

    ---

    Geany este un editor de text ușor și puternic, care oferă un echilibru
    excelent între funcționalitate și performanță. Este proiectat să fie rapid
    și să consume puține resurse, fiind ideal pentru dezvoltarea de aplicații
    C++. Geany oferă suport pentru evidențierea sintaxei, completarea automată
    și un terminal integrat. Este foarte potrivit pentru dezvoltatorii care
    doresc un editor simplu, dar capabil, care poate fi folosit fără a instala
    multe extensii.

     [:octicons-arrow-right-24: Instalare și configurare](./geany.md)

</div>

!!! note "Notă"

    În afară de aceste editoare, mai există și altele, precum eternele
    Vim/Neovim și Emacs. Deși autorul folosește ambele editoare
    (Emacs îndeosebi), procesul de a le configura este mai anevoios și sunt în
    afara scopului acestui articol introductiv.