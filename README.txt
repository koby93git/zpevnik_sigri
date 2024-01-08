Jak přeložit pdf ve Windows

1. Nainstalovat https://miktex.org/download

2. Přidat adresář s instalovaným MiKTex do systémové proměnné PATH, např. C:\Program Files\MiKTeX 2.9\miktex\bin\x64\.

   POZOR! Raději si zálohuj proměnnou PATH (vykopíruj výpis příkazu: echo %PATH%)

   V cmd spuštěném jako správce zadat tento příkaz: setx \M PATH="%PATH%;C:\Program Files\MiKTeX 2.9\miktex\bin\x64\"

3. Spustit soubor get_pdf.bat v této složce