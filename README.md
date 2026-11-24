# Public-iLogic — iLogic-regels voor Autodesk Inventor

## CC_Vervang_Tool.iLogicVb.txt
Content Center vervang-tool (Inventor 2026):
- Doorzoekt de actieve assembly en alle subassembly's
- Toont alle unieke Content Center-onderdelen (part number, bestandsnaam, omschrijving, familie, aantal plaatsen)
- Per onderdeel een vervangend onderdeel kiezen:
  - via de CC-librarybrowser (libraries → categorieën → families → maten, genereert het .ipt via CreateMember), of
  - vanaf schijf uit de Content Center-map
- Knop **Uitvoeren** vervangt alle voorkomens in alle subassembly's (ComponentOccurrence.Replace)

### Gebruik
1. In Inventor: iLogic-browser → tab **Externe regels** → regel toevoegen → dit bestand selecteren
2. Open de assembly en draai de regel (rechtermuisknop → Run Rule, of koppel aan een iLogic-formulier/knop)
3. Kies per regel een vervanging en klik op Uitvoeren
