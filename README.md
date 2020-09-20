# vertaling-covid-vragenlijst

De vertaling naar het Nederlands zit op de 'translation' branch. De vertaling is nu afgerond en gedeeld met de onderzoeksleider. 

# Er zijn enkele problemen naar voren gekomen (hieronder in het Engels): 

1. There’s an issue with date formatting in QID35_QuestionText. In the Netherlands and Belgium, the standard is dd/mm/yy. But if you simply ask people to fill out a numerical date, the data will be ambiguous. We have in the translation suggested that they write down the date as: 1 April ’20. (Instead of 4-1-20 or 1-4-20.) 

2. There’s an issue with the PCR test description (QIDs 24, 28, 32). To our knowledge, in Belgium and in the Netherlands, people are swabbed twice with the same swab, once in the throat with a orofaryngeal swab, and then the same swab is used to take a sample from the front of the nose. In the questionnaire this would strictly count as ‘other’, but we're not sure which option people who have been swabbed this way will pick. 

3. The US education categories are difficult to match with the Dutch system. We’ve tried to give a best approximation. 

4. There’s a slight difference in how date estimates are asked in QID35, compared to QID29, QID330, and QID331. We have not removed this difference in the translation. 

# Over de spreadsheet:

Let op! In sommige rijen zit ook HTML. Deze moet geheel intact en onveranderd blijven. Dit vereist soms een beetje puzzelen. Bijvoorbeeld, in QID217_QuestionText: 

```
"In welk land woont u op het moment?<span style=""caret-color: rgb(0, 0, 0);"">&nbsp;</span><span style=""caret-color: rgb(0, 0, 0); color: rgb(231, 76, 60); font-size: 16px;"">*</span>"
```

Er is een kolom toegevoegd (links) om met een 'V' te kunnen bijhouden welke rijen vertaald zijn, en welke rijen nog vertaald moeten worden. Deze kolom zal 
uiteindelijk weer verwijderd worden. 
