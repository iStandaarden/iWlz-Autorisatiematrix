# Autorisatiematrix Bemiddelingsregister 1
Bemiddelingsregister 1: versie 1.1 - 30-09-2024 

[Informatiemodel Bemiddelingsregister 1](https://informatiemodel.istandaarden.nl/informatiemodel/iwlz/netwerk/bemiddelingsregister-1/)



<<- scroll ->>
|             ENTITEIT   / ATTRIBUUT | <h4 id="bra0001">BRA0001</h4> | <h4 id="bra0002">BRA0002</h4> | <h4 id="bra0004">BRA0004</h4> | <h4 id="bra0005">BRA0005</h4> | <h4 id="bra0006">BRA0006</h4> | <h4 id="bra0007">BRA0007</h4> | <h4 id="bra0008">BRA0008</h4> | <h4 id="bra0009">BRA0009</h4> | <h4 id="bra0010">BRA0010</h4> | <h4 id="bra0011">BRA0011</h4> | <h4 id="bra0012">BRA0012</h4> |
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
|                     wlzIndicatieID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |    R    |         |
|        verantwoordelijkZorgkantoor |    R    |    R    |         |         |    R    |    R    |         |         |    R    |    R    |         |
|   verantwoordelijkheidIngangsdatum |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|      verantwoordelijkheidEinddatum |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|        **Bemiddelingspecificatie** |         |         |         |         |         |         |         |         |         |         |         |
|           bemiddelingspcificatieID |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                     leveringsvorm  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                            zzpCode |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|            toewijzingIngangsdatum  |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                         instelling |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|              uitvoerendZorgkantoor |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                 vaststellingMoment |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
|                toewijzingEinddatum |    R    |    R    |         |         |    R    |    R    |         |         |    R    |         |         |
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
|        verantwoordelijkZorgkantoor |         |         |         |         |         |         |         |         |    R    |         |         |
|                 vaststellingMoment |         |         |         |         |         |         |         |         |    R    |         |         |
|                    overdrachtdatum |         |         |         |         |         |         |         |         |    R    |         |         |
|                       verhuisdatum |         |         |         |         |         |         |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|         **Overdrachtspecificatie** |         |         |         |         |         |         |         |         |         |         |         |
|           overdrachtspecificatieID |         |         |         |         |         |         |         |         |    R    |         |         |
|                    leveringsstatus |         |         |         |         |         |         |         |         |    R    |         |         |
|       leveringsstatusClassificatie |         |         |         |         |         |         |         |         |    R    |         |         |
| oorspronkelijkeToewijzingEinddatum |         |         |         |         |         |         |         |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                    **Regiehouder** |         |         |         |         |         |         |         |         |         |         |         |
|                      regiehouderID |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                         instelling |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                       ingangsdatum |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                          einddatum |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                           regierol |         |         |         |    R    |         |         |         |    R    |         |         |    R    |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                **Contactgegevens** |         |         |         |         |         |         |         |         |         |         |         |
|                  contactgegevensID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
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
|                          einddatum |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
|                                    |         |         |         |         |         |         |         |         |         |         |         |
|                 **Contactpersoon** |         |         |         |         |         |         |         |         |         |         |         |
|                   contactpersoonID |         |         |    R    |         |         |         |    R    |         |    R    |         |         |
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
 
