
# Fork

## Co je Fork?
Fork je proces, při kterém se vytvoří kopie existujícího projektu, což umožňuje jeho další samostatný vývoj, aniž by se zasahovalo do původní verze. V prostředí verzovacích systémů, jako je Git, se používá pro práci na nových funkcích, opravách chyb nebo experimentování s kódem, aniž by se ovlivnila hlavní větev projektu. Fork poskytuje vývojářům svobodu testovat a vylepšovat projekt podle svých představ. V tomto návodu si ukážeme, jak si Fork nainstalovat a začít s ním pracovat.

## Instalace a nastavení Fork

Fork lze stáhnout z oficiální webové stránky [zde](https://git-fork.com/). Stačí vybrat verzi pro váš operační systém, buď pro **Windows**, nebo **macOS**.

### Po stažení:
1. Spusťte instalační soubor a postupujte podle pokynů.
2. Po dokončení instalace spusťte aplikaci a zadejte své přihlašovací údaje z GitHubu:
   - **Přezdívku** (Username)
   - **E-mailovou adresu**
   - **Cestu pro ukládání souborů** (kam chcete ukládat své projekty)

![přihlášení fork](https://github.com/user-attachments/assets/1b7b3fe8-94b4-42ab-bf38-6ccabfbcede8)

3. Klikněte na tlačítko `Finish` a počkejte, až se všechna nastavení načtou.

## Přidání GitHub účtu

Aby bylo možné využívat Fork naplno, je potřeba přidat svůj GitHub účet:

1. Otevřete nabídku `File` a vyberte možnost `Accounts...`.

!!!!!obrázek

2. V pravém horním rohu klikněte na znaménko `+`, čímž se otevře okno pro přidání nového účtu.
3. Vyberte možnost `GitHub`, zadejte své GitHub přihlašovací údaje a klikněte na `Sign in`.
   - **Poznámka**: Ujistěte se, že jste ve webovém prohlížeči přihlášeni ke svému GitHub účtu.

!!!!! obrázek

4. Otevře se nové okno, kde potvrdíte propojení svého GitHub účtu s Fork. Poté budete muset zadat své GitHub heslo.

!!!!! obrázek

5. Nakonec klikněte na `Sign in` a váš účet bude připojen.

## Klonování repozitáře a ukládání změn

Jakmile máte připojený GitHub účet, můžete začít klonovat repozitáře (projekty):

1. V hlavní nabídce klikněte na `File` a zvolte `Clone...`.

!!!!!obrázek

2. Otevře se nové okno, kde zadáte URL adresu repozitáře, který chcete klonovat, a název projektu. Poté klikněte na `Clone`.

!!!!! obrázek

3. **Kde najít URL adresu repozitáře?**  
   Otevřete si projekt na GitHubu, který chcete klonovat, a klikněte na tlačítko `<> Code`. Poté zkopírujte URL adresu.

!!!!!obrázek

4. Po klonování můžete repozitář otevřít ve svém oblíbeném editoru, například ve **Visual Studio Code**.

!!!!!obrázek

### Ukládání změn (Commit a Push)

Pokud provedete nějaké změny v projektu, Fork vám je zobrazí v sekci `Local Changes`.

!!!!!obrázek

Pro uložení změn na GitHub (commiting):

1. V sekci `Local Changes` vyberte soubory, které chcete commitnout, a klikněte na tlačítko `Stage`.
2. Do spodního řádku napište název commitu (např. "Oprava chyby" nebo "Přidání nové funkce") a přidejte volitelný popis změn.
3. Klikněte na `Commit`.

!!!!! obrázek

Nyní zbývá už jen nahrát změny na GitHub:

1. Klikněte na tlačítko `Push` v horní části aplikace.
2. Vaše změny jsou nyní na GitHubu!

!!!!! obrázek




