# Autorisatiematrix Bemiddelingsregister 1
versie 1.0 - 21-12-2023

|                Entiteit |          |                          Attribuut |    BRA0001    |    BRA0002    |    BRA0003    |    BRA0004    | BRA0005 | BRA0006 | BRA0007 | BRA0008 | BRA0009 | BRA0010 |
|------------------------:|---------:|-----------------------------------:|:-------------:|:-------------:|:-------------:|:-------------:|---------|---------|---------|---------|---------|---------|
|                         |          |                                    | ZORGAANBIEDER | ZORGAANBIEDER | ZORGAANBIEDER | ZORGAANBIEDER |         |         |         |         |         |         |
|                 Client  | sleutel  |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |                           clientID |       R       |               |               |               |         |         |         |         |         |         |
|                         |       UK |                                bsn |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |                        leefeenheid |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |                           huisarts |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |                   communicatievorm |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |                              taal  |       R       |               |               |               |         |         |         |         |         |         |
|          Bemiddeldeling |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |                      bemiddelingID |       R       |               |               |               |         |         |         |         |         |         |
|                         |   FK, AK |                           clientID |       R       |               |               |               |         |         |         |         |         |         |
|                         |       AK |                     wlzIndicatieID |       R       |               |               |               |         |         |         |         |         |         |
|                         |       AK |        verantwoordelijkZorgkantoor |       R       |               |               |               |         |         |         |         |         |         |
|                         |       AK |   verantwoordelijkheidIngangsdatum |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |      verantwoordelijkheidEinddatum |       R       |               |               |               |         |         |         |         |         |         |
| Bemiddelingspecificatie |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |           bemiddelingspcificatieID |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |   FK, AK |                   bemiddeldeIingID |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |       AK |                     leveringsvorm  |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |       AK |                           zzpCode  |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |       AK |            toewijzingIngangsdatum  |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |       AK |                         instelling |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |       AK |              uitvoerendZorgkantoor |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |                 vaststellingMoment |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |               toewijzingEinddatum  |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |                        percentage  |       R       |       R       |               |               |         |         |         |         |         |         |
|                         |          |                             opname |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |                    redenIntrekking |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |                            etmalen |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |               instellingBestemming |       R       |       R       |       R       |               |         |         |         |         |         |         |
|                         |          |                    soortToewijzing |       R       |       R       |       R       |               |         |         |         |         |         |         |
|              Overdracht |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |                       overdrachtID |               |               |               |               |         |         |         |         |         |         |
|                         |    FK,AK |                     bemiddelingdID |               |               |               |               |         |         |         |         |         |         |
|                         |       AK |       verantwoordelijkZorgkantoor  |               |               |               |               |         |         |         |         |         |         |
|                         |          |                 vaststellingMoment |               |               |               |               |         |         |         |         |         |         |
|                         |          |                    overdrachtdatum |               |               |               |               |         |         |         |         |         |         |
|                         |          |                       verhuisdatum |               |               |               |               |         |         |         |         |         |         |
|  Overdrachtspecificatie |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |           overdrachtspecificatieID |               |               |               |               |         |         |         |         |         |         |
|                         |  FK1, AK |            bemiddelingspecificatie |               |               |               |               |         |         |         |         |         |         |
|                         |  FK2, AK |                       overdrachtID |               |               |               |               |         |         |         |         |         |         |
|                         |          |                    leveringsstatus |               |               |               |               |         |         |         |         |         |         |
|                         |          |       leveringsstatusClassificatie |               |               |               |               |         |         |         |         |         |         |
|                         |          | oorspronkelijkeToewijzingEinddatum |               |               |               |               |         |         |         |         |         |         |
|           Dossierhouder |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |                    dossierhouderID |       R       |               |               |               |         |         |         |         |         |         |
|                         |   FK, AK |                           clientID |       R       |               |               |               |         |         |         |         |         |         |
|                         |       Ak |                         instelling |       R       |               |               |               |         |         |         |         |         |         |
|                         |       AK |                       ingangsdatum |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |                         einddatum  |       R       |               |               |               |         |         |         |         |         |         |
|    CoordinatorZorgThuis |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |             coordinatorZorgThuisID |       R       |               |               |               |         |         |         |         |         |         |
|                         |   FK, AK |                           clientID |       R       |               |               |               |         |         |         |         |         |         |
|                         |       AK |                         instelling |       R       |               |               |               |         |         |         |         |         |         |
|                         |       AK |                       ingangsdatum |       R       |               |               |               |         |         |         |         |         |         |
|                         |          |                         einddatum  |       R       |               |               |               |         |         |         |         |         |         |
|         Contactgegevens |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |                  contactgegevensID |               |               |               |       R       |         |         |         |         |         |         |
|                         | FK1, AK1 |                           clientID |               |               |               |       R       |         |         |         |         |         |         |
|                         | FK2, AK2 |                   contactpersoonID |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         straatnaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         huisnummer |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         huisletter |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |               huisnummertoevoeging |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                aanduidingWoonadres |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                           postcode |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         plaatsnaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                               land |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         adressoort |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                   telefoonnummer01 |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                       landnummer01 |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                   telefoonnummer02 |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                       landnummer02 |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         emailadres |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                       ingangsdatum |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                         einddatum  |               |               |               |       R       |         |         |         |         |         |         |
|          Contactpersoon |          |                                    |               |               |               |               |         |         |         |         |         |         |
|                         |       PK |                   contactpersoonID |               |               |               |       R       |         |         |         |         |         |         |
|                         | FK1, AK1 |                           clientID |               |               |               |       R       |         |         |         |         |         |         |
|                         |      AK1 |                      relatienummer |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                           volgorde |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                       soortRelatie |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                                rol |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                            relatie |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                      geslachtsnaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |           voorvoegselGeslachtsnaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                        partnernaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |             voorvoegselPartnernaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                          voornamen |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                        voorletters |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                           roepnaam |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                        naamgebruik |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                           geslacht |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                      geboortedatum |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |               geboortedatumgebruik |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                       ingangsdatum |               |               |               |       R       |         |         |         |         |         |         |
|                         |          |                          einddatum |               |               |               |       R       |         |         |         |         |         |         |
 
