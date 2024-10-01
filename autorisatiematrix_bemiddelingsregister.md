# Autorisatiematrix Bemiddelingsregister 1
Bemiddelingsregister 1: versie 1.1 - 30-09-2024 (under construction)

[Informatiemodel Bemiddelingsregister 1](https://informatiemodel.istandaarden.nl/iWlz-Bemiddeling-1/)

<<- scroll ->>
|             ENTITEIT   / ATTRIBUUT | BRA0001 | BRA0002 | BRA0004 | BRA0005 | BRA0006 | BRA0007 | BRA0008 | BRA0009 | BRA0010 | BRA0011 | BRA0012 |
|-----------------------------------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
|                        **Client**  |         |         |         |         |         |         |         |         |         |         |         |
|                           clientID |    R    |         |         |         |    R    |         |         |         |    R    |         |         |
|                                bsn |    R    |         |         |         |    R    |         |         |         |    R    |         |         |
|                        leefeenheid |    R    |         |         |         |    R    |         |         |         |    R    |         |         |
|                           huisarts |    R    |         |         |         |    R    |         |         |         |    R    |         |         |
|                   communicatievorm |    R    |         |         |         |    R    |         |         |         |    R    |         |         |
|                              taal  |    R    |         |         |         |    R    |         |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                    **Bemiddeling** |         |         |         |         |         |         |         |         |         |         |         |
|                      bemiddelingID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                           clientID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                     wlzIndicatieID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |    R    |         |
|        verantwoordelijkZorgkantoor |    R    |    R    |         |         |    R    |    R    |         |         |    R    |    R    |         |
|   verantwoordelijkheidIngangsdatum |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|      verantwoordelijkheidEinddatum |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|        **Bemiddelingspecificatie** |         |         |         |         |         |         |         |         |         |         |         |
|           bemiddelingspcificatieID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                   bemiddeldeIingID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                     leveringsvorm  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                           zzpCode  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|            toewijzingIngangsdatum  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                         instelling |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|              uitvoerendZorgkantoor |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                 vaststellingMoment |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|               toewijzingEinddatum  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                        percentage  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                      pgbPercentage |         |         |         |         |    R    |    R    |         |         |         |         |         |
|                             opname |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                    redenIntrekking |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                            etmalen |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|               instellingBestemming |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                    soortToewijzing |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                     **Overdracht** |         |         |         |         |         |         |         |         |         |         |         |
|                       overdrachtID |         |         |         |         |         |         |         |         |    R    |         |         |
|                     bemiddelingdID |         |         |         |         |         |         |         |         |    R    |         |         |
|       verantwoordelijkZorgkantoor  |         |         |         |         |         |         |         |         |    R    |         |         |
|                 vaststellingMoment |         |         |         |         |         |         |         |         |    R    |         |         |
|                    overdrachtdatum |         |         |         |         |         |         |         |         |    R    |         |         |
|                       verhuisdatum |         |         |         |         |         |         |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|         **Overdrachtspecificatie** |         |         |         |         |         |         |         |         |         |         |         |
|           overdrachtspecificatieID |         |         |         |         |         |         |         |         |    R    |         |         |
|            bemiddelingspecificatie |         |         |         |         |         |         |         |         |    R    |         |         |
|                       overdrachtID |         |         |         |         |         |         |         |         |    R    |         |         |
|                    leveringsstatus |         |         |         |         |         |         |         |         |    R    |         |         |
|       leveringsstatusClassificatie |         |         |         |         |         |         |         |         |    R    |         |         |
| oorspronkelijkeToewijzingEinddatum |         |         |         |         |         |         |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                    **Regiehouder** |         |         |         |         |         |         |         |         |         |         |         |
|                      regiehouderID |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                      bemiddelingID |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                         instelling |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                       ingangsdatum |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                          einddatum |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                           regierol |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                **Contactgegevens** |         |         |         |         |         |         |         |         |         |         |         |
|                  contactgegevensID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                           clientID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                   contactpersoonID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         straatnaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         huisnummer |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         huisletter |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|               huisnummertoevoeging |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                aanduidingWoonadres |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                           postcode |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         plaatsnaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                               land |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         adressoort |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                   telefoonnummer01 |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                       landnummer01 |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                   telefoonnummer02 |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                       landnummer02 |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         emailadres |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                       ingangsdatum |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                         einddatum  |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                 **Contactpersoon** |         |         |         |         |         |         |         |         |         |         |         |
|                   contactpersoonID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                           clientID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                      relatienummer |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                           volgorde |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                       soortRelatie |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                                rol |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                            relatie |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                      geslachtsnaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|           voorvoegselGeslachtsnaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                        partnernaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|             voorvoegselPartnernaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                          voornamen |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                        voorletters |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                           roepnaam |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                        naamgebruik |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                           geslacht |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                      geboortedatum |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|               geboortedatumgebruik |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                       ingangsdatum |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                          einddatum |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
 
