

Zaměstnanci - aplikace s WinForms a databází

Umožňuje přidávat osoby do DB, odstraňovat je z ní a obnovit původní seznam osob ze záložní DB,
kterou nelze uživatelsky upravovat.
Program správně funguje, pokud je nainstalována LocalDB SQL Server Express 2019, která je jako jediná
LocalDB součástí Visual Studia Community 2022. Více informací je v obrázcích Navod-1, Navod-2 a Screen.

při přidávání osoby
- kontroluje vyplnění polí, upozorní na nedostatek
- odstraňuje zadané mezery, oddělení nelze ručně zapsat ani editovat
- dynamicky mění červený chybový text ihned po každé změně v zadávacích polích
