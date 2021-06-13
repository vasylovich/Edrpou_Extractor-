# Edrpou_Extractor-
Extraction of Ukrainian EDRPOU registry xml

This script will help you to extract active organizations from "ЄДИНИЙ ДЕРЖАВНИЙ РЕЄСТР ЮРИДИЧНИХ ОСІБ, ФІЗИЧНИХ ОСІБ – ПІДПРИЄМЦІВ ТА ГРОМАДСЬКИХ ФОРМУВАНЬ". 
https://nais.gov.ua/m/ediniy-derjavniy-reestr-yuridichnih-osib-fizichnih-osib-pidpriemtsiv-ta-gromadskih-formuvan


rename - active_organizations.xml to current version of file from the website (downloaded xml file eg. 17-UFOP_02.03.2021.xml).

This example generate a xlsx file with acrive beverigies compainies in Ukraine. But you can change to the desired grop. 
The info in XML file is encoded for cyrilic cp1251 format, so probably its better to use        

value = u'\u0437'u'\u0430'u'\u0440'u'\u0435'u'\u0454'u'\u0441'u'\u0442'u'\u0440'u'\u043e'u'\u0432'u'\u0430'u'\u043d'u'\u043e' instead of value = "зареєстровано" etc. - it can help you to save day or two of research)). 

Have a fun!)
