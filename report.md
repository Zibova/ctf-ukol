V systému bylo nesprávně nastavené sudo oprávnění, které umožňovalo uživateli student spustit program zip jako uživatel spravce bez zadání hesla. 
Program zip obsahuje parametr -TT, který umožňuje spustit externí příkaz při testování archivu. 
Tím bylo možné spustit příkaz cat s oprávněními uživatele spravce a přečíst chráněný soubor; řešením je odebrat toto sudo oprávnění nebo omezit jeho použití.
