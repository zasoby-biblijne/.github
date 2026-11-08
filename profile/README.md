# Zasoby biblijne

**Polski projekt cyfrowy wspierający dostęp do materiałów i narzędzi do studiowania Biblii.**

Organizacja GitHub `zasoby-biblijne` skupia repozytoria składające się na projekt
**Zasoby biblijne**. Aplikacja gromadzi różne materiały biblijne i udostępnia je
w jednym serwisie, wyposażonym w wyszukiwarkę oraz narzędzia ułatwiające
korzystanie z treści.

W serwisie znajdują się między innymi książki, czasopisma i artykuły, informacje
o rodowodach biblijnych, śpiewniki oraz rozważania na każdy dzień. Treści i
funkcje aplikacji są rozwijane w kilku repozytoriach, a ich głównymi elementami
są backend i frontend.

## Jak działa projekt

Frontend udostępnia aplikację webową, a backend dostarcza jej dane, treści i
funkcje wyszukiwania. Aplikacja mobilna na Androida i iOS wyświetla ten sam
serwis w komponencie WebView, zamiast niezależnie implementować jego funkcje.
Do działania wymaga połączenia z internetem.

## Repozytoria organizacji

| Repozytorium                                                                  | Rola w projekcie                                                                                                         |
| ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| `backend` · prywatne                                                          | API, korpus treści, wyszukiwanie oraz zaplecze wspierające działanie serwisu.                                            |
| `frontend` · prywatne                                                         | Aplikacja webowa z interfejsem do przeglądania i wyszukiwania materiałów na telefonach, tabletach i komputerach.         |
| `mobile` · prywatne                                                           | Aplikacja mobilna oparta na Expo, która udostępnia serwis webowy w WebView i zawiera konfigurację dla Androida oraz iOS. |
| [`landing-page`](https://github.com/zasoby-biblijne/landing-page) · publiczne | Niezależna od aplikacji strona informacyjna i awaryjna.                                                                  |
| [`.github`](https://github.com/zasoby-biblijne/.github) · publiczne           | Profil organizacji i informacje o projekcie publikowane na GitHub.                                                       |

Repozytoria backendu, frontendu i aplikacji mobilnej zawierają szczegółowe
informacje o architekturze, konfiguracji i sposobie uruchomienia poszczególnych
części systemu.
