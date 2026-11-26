# Hemgård

Ett lugnt spel om att bygga och inreda ett svenskt hem. Här finns spelet att ladda ner.
Du behöver inget konto någonstans.

**Ladda ner:** öppna [den senaste versionen](https://github.com/SamHatami/hemgard-releases/releases/latest)
och välj filen för din dator under *Assets*.

## Windows

1. Ladda ner `Hemgard-Setup-<version>.exe` och öppna den.
2. Windows kan säga **"Windows skyddade din dator"**, eftersom spelet inte är köpt från en butik.
   Klicka på **Mer info** och sedan **Kör ändå**. Det behövs bara första gången.
3. Installationen frågar inte efter administratörslösenord. Hemgård hamnar i Start-menyn.

## Mac (M1 eller nyare)

1. Ladda ner `Hemgard-<version>-mac.zip`. Den packas upp av sig själv till **Hemgard**.
2. Dra **Hemgard** till mappen **Program**.
3. Öppna den. Första gången säger macOS att den inte kan kontrollera appen. Klicka **Klar**,
   öppna **Systeminställningar → Integritet och säkerhet**, skrolla ner och klicka
   **Öppna ändå** vid Hemgard. Det behövs bara första gången.

## Linux (64-bitars, Ubuntu 22.04 eller nyare)

1. Ladda ner `Hemgard-<version>-linux.tar.gz` och packa upp den, till exempel med
   `tar xzf Hemgard-<version>-linux.tar.gz`.
2. Kör `Hemgard/install.sh`. Hemgård hamnar i programmenyn och kan också startas med `hemgard`.
   Inget administratörslösenord behövs. (Du kan också starta `Hemgard/hemgard` direkt utan att
   installera.)
3. Ta bort spelet med `~/.local/share/hemgard-game/install.sh --uninstall`. Dina sparade hem
   finns kvar.

## Uppdateringar

När en ny version finns säger spelet till i startmenyn och frågar om det ska uppdatera.
Dina sparade hem följer med, och en kopia av dem sparas innan något ändras.

## Något gick fel?

Välj **Skicka felrapport** i pausmenyn och skriv vad som hände. Sam får den direkt.

---

*English:* Hemgård is a calm game about building and furnishing a Swedish home. Download the
file for your computer from the latest release above. On first start, Windows may ask you to
confirm (More info, Run anyway) and macOS may ask you to allow it in System Settings, Privacy
& Security (Open Anyway). On Linux, unpack the tar.gz and run `Hemgard/install.sh` (no
administrator password; `--uninstall` removes it again, keeping your saves). The game updates
itself after that.
