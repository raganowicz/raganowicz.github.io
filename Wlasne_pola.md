# Własne pola

| Spis treści                                                            |
| ---------------------------------------------------------------------- |
| [**Hero**](#hero)<br/>                                                 |
| [**Hero - Strona główna**](#hero---strona-główna)<br/>                 |
| [**Lead**](#lead)<br/>                                                 |
| [**Sekcje**](#sekcje)<br/>                                             |
| [**Sekcje - Strona główna**](#sekcje---strona-główna)<br/>             |
| [**Powiązane wpisy**](#powiązane-wpisy)<br/>                           |
| [**Projekt**](#projekt)<br/>                                           |
| [**Kontakt**](#kontakt)<br/>                                           |
| [**Osoba - szczegóły sortowania**](#osoba---szczegóły-sortowania)<br/> |
| [**Wideo**](#wideo)<br/>                                               |

## Hero

<br/>

- #### **Obrazek w hero** _(Prawda / Fałsz)_ - zaznaczenie pola sprawia, że 'Obrazek wyróżniający' będzie wyświetlany w hero strony. Należy pamiętać o dodaniu obrazka wyróżniającego, w przeciwnym razie hero będzie wyświetlane w domyślnej formie bez obrazka. Domyślnia wartość: **Tak**.

---

<br/>

## Hero - Strona główna

<br/>

- #### **Nagłówek** _(Obszar tekstowy)_ - sekcja dodaje treść nagłówka strony głównej.

---

<br/>

## Lead

<br/>

- #### _(Obszar tekstowy)_ - Lead wpisu powinien być krótkim, zwięzłym i interesującym fragmentem, wskazującym na temat wpisu.

---

<br/>

## Sekcje

<br/>

- #### **Nagłówek** - sekcja pozwala na wstawienie nagłówka `<h2>` z opcjonalnym linkiem.

    <br/>

  | Nazwa pola | Typ     | Rola                                            |
  | ---------- | ------- | ----------------------------------------------- |
  | Nagłówek   | _Tekst_ | Treść nagłówka, wyświetlana w tagu `<h2>`       |
  | Link       | _Link_  | Link do którego kieruje nagłówek _(opcjonalne)_ |

    <br/>

- #### **Tekst** - sekcja dodaje treść z nagłówkiem.

    <br/>

  | Nazwa pola | Typ                | Rola                                                                                                       |
  | ---------- | ------------------ | ---------------------------------------------------------------------------------------------------------- |
  | Szerokość  | _Grupa przycisków_ | Wybór szerokości bloku tekstowego - tekst może stanowić kolumnę, lub zajmować pełną szerokość kontenera.   |
  | Nagłówek   | _Tekst_            | Treść nagłówka, wyświetlana w tagu `<h2>`.                                                                 |
  | Treść      | _Edytor WYSIWYG_   | Treść bloku tekstowego. Edytor WYSIWYG umożliwia dodawanie tekstu, jego edycje, a także wstawianie mediów. |

    <br/>

- #### **Galeria + Tekst** - sekcja dodaje treść z galerią obrazów.

    <br/>

  | Nazwa pola         | Typ              | Rola                                                                                                                                                                               |
  | ------------------ | ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | Wspólny figcaption | _Grupa_          | Pole umożliwia ustawienie wszystkim obrazom w galerii wspólnego `figcaption`. Aby to zrobić, należy zaznaczyć przycisk _Tak_, co odblokuje input, w który należy wprowadzić treść. |
  | Galeria            | _Galeria_        | Aby dodać obraz do galerii należy kliknąć przycisk _Dodaj do galerii_, a następie wybrać obraz z biblioteki mediów, lub przesłać nowy plik.                                        |
  | Treść              | _Edytor WYSIWYG_ | Treść bloku tekstowego. Edytor WYSIWYG umożliwia dodawanie tekstu, jego edycje, a także wstawianie mediów.                                                                         |

    <br/>

- #### **Obrazek wyróżniający + Tekst** - sekcja dodaje treść z obrazkiem wyróżniającym. Obraz jest pobierany automatycznie. Używając tej sekcji należy pamiętać o uzupełnieniu pola _Obrazek wyróżniający_.

    <br/>

  | Nazwa pola | Typ              | Rola                                                                                                       |
  | ---------- | ---------------- | ---------------------------------------------------------------------------------------------------------- |
  | Treść      | _Edytor WYSIWYG_ | Treść bloku tekstowego. Edytor WYSIWYG umożliwia dodawanie tekstu, jego edycje, a także wstawianie mediów. |

    <br/>

- #### **Zdjęcie** - sekcja dodaje obraz, zajmujący pełną szerokość kontenera.

    <br/>

  | Nazwa pola | Typ     | Rola |
  | ---------- | ------- | ---- |
  | Obraz      | _Obraz_ | -    |

    <br/>

- #### **Wideo / Iframe** - sekcja dodaje wideo lub iframe Vimeo/Youtube.

    <br/>

  | Nazwa pola      | Typ                | Rola                                                                                                                                                                                                                                                   |
  | --------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
  | Typ             | _Grupa przycisków_ | Wybór typu zamieszczanego filmu. `Video` pozwala na wstawienie wideo z biblioteki mediów wraz z niestandardowym odtwarzaczem. `Vimeo/YouTube` umożliwia dodanie linku do `iframe` i osadzenie na stronie wideo bezpośrednio z serwisów Vimeo i Youtube |
  | Poster          | _Obraz_            | Obraz, który jest wyświetlany podczas gdy film jest pobierany lub dopóki użytkownik nie kliknie przycisku odtwarzania. Jeśli pole zostanie puste, jako `poster` zostanie wykorzystana pierwsza klatka filmu.                                           |
  | Video           | _Plik_             | Pole aktywuje się w przypadku wybrania typu `Video`. Należy wybrać plik wideo.                                                                                                                                                                         |
  | Vimeo / YouTube | _oEmbed_           | Pole aktywuje się w przypadku wybrania typu `Vimeo/YouTube`. Należy wstawić link do wideo w wybranym serwisie.                                                                                                                                         |

    <br/>

- #### **Cytat** - sekcja dodaje wyróżniony cytat.

    <br/>

  | Nazwa pola | Typ               | Rola                    |
  | ---------- | ----------------- | ----------------------- |
  | Cytat      | _Obszar tekstowy_ | Treść bloku tekstowego. |

    <br/>

- #### **Rozwijany tekst** - sekcja dodaje _accordiony_ - zwinięte nagłówki, które po kliknięciu rozwijają treść.

    <br/>

  | Nazwa pola       | Typ                | Rola                                                                                 |
  | ---------------- | ------------------ | ------------------------------------------------------------------------------------ |
  | Accordions       | _Pole powtarzalne_ | Lista elementów z rozwijanym tekstem.                                                |
  | Nagłówek         | _Pole powtarzalne_ | Treść nagłówka bloku rozwijanego tekstu.                                             |
  | Szerokość treści | _Grupa przycisków_ | Wybór układu treści (podział na kolumny lub pełna szerokość)                         |
  | Treść            | _Edytor WYSIWYG_   | Treść bloku tekstowego. Edytor WYSIWYG umożliwia dodawanie tekstu, oraz jego edycje. |

<br/>

- #### **Pliki do pobrania** - sekcja dodaje listę plików do pobrania.

    <br/>

  | Nazwa pola         | Typ                | Rola                                                                                                                                                                                                                                 |
  | ------------------ | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
  | Download           | _Pole powtarzalne_ | Lista elementów do pobrania.                                                                                                                                                                                                         |
  | Nagłówek           | _Tekst_            | Treść nagłówka elementu do pobrania.                                                                                                                                                                                                 |
  | Typ                | _Grupa przycisków_ | Wybór typu                                                                                                                                                                                                                           |
  | Treść              | _Edytor WYSIWYG_   | Treść bloku tekstowego. Edytor WYSIWYG umożliwia dodawanie tekstu, oraz jego edycje.                                                                                                                                                 |
  | Plik               | _Plik_             | Pole aktywuje się w przypadku wybrania typu `Plik` lub `Galeria`. Należy dodać plik w dowolnym, dopuszczalnym formacie.                                                                                                              |
  | Zdjęcie            | _Obraz_            | Pole aktywuje się w przypadku wybrania typu `Zdjęcie`. Należy dodać obraz, który będzie wyświetlany w bloku.                                                                                                                         |
  | Wspólny figcaption | _Grupa_            | Pole aktywuje się w przypadku wybrania typu `Galeria`. Umożliwia ustawienie wszystkim obrazom w galerii wspólnego `figcaption`. Aby to zrobić, należy zaznaczyć przycisk _Tak_, co odblokuje input, w który należy wprowadzić treść. |
  | Galeria            | _Galeria_          | Pole aktywuje się w przypadku wybrania typu `Galeria`. Aby dodać obraz do galerii należy kliknąć przycisk _Dodaj do galerii_, a następie wybrać obraz z biblioteki mediów, lub przesłać nowy plik.                                   |

<br/>

- #### **Osoby** - sekcja dodaje listę osób wraz z danymi kontaktowymi, informacją o dyżurach, oraz linkami do singla osoby.

    <br/>

  | Nazwa pola | Typ                | Rola                                     |
  | ---------- | ------------------ | ---------------------------------------- |
  | Osoby      | _Pole powtarzalne_ | Wybór CPT 'Osoby'.                       |
  | Funkcja    | _Tekst_            | Funkcja sprawowana przez osobę.          |
  | Dyżur      | _Obszar tekstowy_  | Informacja o dniach i godzinach dyżurów. |
  | E-mail     | _E-mail_           | Adres e-mail osoby.                      |
  | Telefon    | _Tekst_            | Numer telefonu osoby.                    |

<br/>

- #### **Dane adresowe** - sekcja dodaje listę adresów.

    <br/>

  | Nazwa pola | Typ               | Rola                                             |
  | ---------- | ----------------- | ------------------------------------------------ |
  | Nagłówek   | _Tekst_           | Treść nagłówka.                                  |
  | Link       | _Link_            | Link do którego kieruje nagłówek. _(opcjonalne)_ |
  | Adres      | _Obszar tekstowy_ | -                                                |
  | NIP        | _Tekst_           | -                                                |
  | REGON      | _Tekst_           | -                                                |
  | E-mail     | _E-mail_          | -                                                |
  | Telefon    | _Tekst_           | -                                                |
  | Fax        | _Tekst_           | -                                                |

<br/>

- #### **Lista** - sekcja dodaje numerowaną listę elementów.

    <br/>

  | Nazwa pola | Typ               | Rola                             |
  | ---------- | ----------------- | -------------------------------- |
  | Obraz      | _Obraz_           | -                                |
  | Nagłówek   | _Tekst_           | Treść nagłówka.                  |
  | Lead       | _Obszar tekstowy_ | Lead elementu.                   |
  | Link       | _Link_            | Link do którego kieruje element. |

<br/>

- #### **Osoby kontaktowe** - sekcja dodaje listę osób z danymi kontaktowymi.

    <br/>

  | Nazwa pola       | Typ                | Rola                                     |
  | ---------------- | ------------------ | ---------------------------------------- |
  | Osoby kontaktowe | _Pole powtarzalne_ | Wybór CPT 'Osoby'.                       |
  | Funkcja          | _Tekst_            | Funkcja sprawowana przez osobę.          |
  | Dyżur            | _Obszar tekstowy_  | Informacja o dniach i godzinach dyżurów. |
  | E-mail           | _E-mail_           | Adres e-mail osoby.                      |
  | Telefon          | _Tekst_            | Numer telefonu osoby.                    |

---

<br/>

## Sekcje - Strona główna

<br/>

- #### **Wyróżnione posty** _(Relacja)_ - sekcja umożliwia wybór wpisów wyświetlanych w sliderze na stronie głównej.

    <br/>

- #### **Lista** - sekcja dodaje numerowaną listę elementów.

    <br/>

  | Nazwa pola | Typ               | Rola                             |
  | ---------- | ----------------- | -------------------------------- |
  | Obraz      | _Obraz_           | -                                |
  | Nagłówek   | _Tekst_           | Treść nagłówka.                  |
  | Lead       | _Obszar tekstowy_ | Lead elementu.                   |
  | Link       | _Link_            | Link do którego kieruje element. |

- #### **Aktualności** - sekcja wyświetla siatkę aktualnych wpisów.

    <br/>

  | Nazwa pola    | Typ      | Rola                                                   |
  | ------------- | -------- | ------------------------------------------------------ |
  | Liczba postów | _Liczba_ | Wybór liczby aktualnych wpisów wyświetlanych w sekcji. |

    <br/>

- #### **Nagłówek + Tekst**

    <br/>

  | Nazwa pola   | Typ                | Rola                                                                                                                                                                               |
  | ------------ | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | Nagłówek     | _Tekst_            | -                                                                                                                                                                                  |
  | Treść        | _Obszar tekstowy_  | Treść bloku tekstowego.                                                                                                                                                            |
  | Link         | _Grupa przycisków_ | Wybór przycisku. Przycisk może być wyłączony, lub mieć wybrany typ - Typ 1 _(standardowy przycisk z etykietą i strzałką)_ lub Typ 2 _(okrągły przycisk ze strzałką, bez etykiety)_ |
  | Wybierz link | _Link_             | Pole jest wyświetlane warunkowo. Jeśli pole 'Link' nie jest wyłączone, odblokowany zostaje przycisk, który umożliwia wybranie odnośnika, do którego prowadzi przycisk.             |

    <br/>

- #### **Videos** - sekcja wyświetla slider z postami typu 'Wideo'.

  | Nazwa pola | Typ               | Rola                                                          |
  | ---------- | ----------------- | ------------------------------------------------------------- |
  | Etykieta   | _Tekst_           | Mała etykieta wyświetlana obok głównego nagłówka              |
  | Nagłówek   | _Obszar tekstowy_ | Treść nagłówka.                                               |
  | -          | _Relacja_         | Wybór postów typu 'Wideo', które będą wyświetlane w sliderze. |

  <br/>

- #### **Zdjęcie** _(Obraz)_ - sekcja pozwala na dodanie obrazu obraz, zajmującego szerokość kontenera.

    <br/>

---

<br/>

## Kontakt

<br/>

- #### **Mapa** - sekcja dodaje mapę OpenStreetMap wraz z zaznaczonymi punktami.

    <br/>

  | Nazwa pola | Typ                | Rola                                                                                                                                                                                                                                     |
  | ---------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | Markery    | _Pole powtarzalne_ | Pole umożliwia dodawanie znaczników do mapy - żeby dodać marker, należy uzupełnić dodatkowo pola **Nazwa**, **Adres** i **Współrzędne geograficzne** _(które składają się z **Szerokości** i **Długości** geograficznej)_ danego punktu. |
  | Adres      | _Obszar tekstowy_  | -                                                                                                                                                                                                                                        |
  | NIP        | _Tekst_            | -                                                                                                                                                                                                                                        |
  | REGON      | _Tekst_            | -                                                                                                                                                                                                                                        |
  | E-mail     | _E-mail_           | -                                                                                                                                                                                                                                        |
  | Telefon    | _Tekst_            | -                                                                                                                                                                                                                                        |

<br/>

- #### **Dane adresowe** - sekcja dodaje listę adresów.

    <br/>

  | Nazwa pola | Typ               | Rola                                             |
  | ---------- | ----------------- | ------------------------------------------------ |
  | Nagłówek   | _Tekst_           | Treść nagłówka.                                  |
  | Link       | _Link_            | Link do którego kieruje nagłówek. _(opcjonalne)_ |
  | Adres      | _Obszar tekstowy_ | -                                                |
  | NIP        | _Tekst_           | -                                                |
  | REGON      | _Tekst_           | -                                                |
  | E-mail     | _E-mail_          | -                                                |
  | Telefon    | _Tekst_           | -                                                |
  | Fax        | _Tekst_           | -                                                |

<br/>

- #### **Osoby kontaktowe** - sekcja dodaje listę osób z danymi kontaktowymi.

    <br/>

  | Nazwa pola | Typ       | Rola                              |
  | ---------- | --------- | --------------------------------- |
  | -          | _Relacja_ | Wybór osoby z postów typu 'Osoby' |
  | Funkcja    | _Tekst_   | Funkcja sprawowana przez osobę.   |
  | E-mail     | _E-mail_  | Adres e-mail osoby.               |
  | Telefon    | _Tekst_   | Numer telefonu osoby.             |

---

<br/>

## Powiązane wpisy

<br/>

- #### **Powiązane aktualności** _(Relacja)_ - Pole umożliwia wybór powiązanych wpisów.
- #### **Powiązane osoby** _(Relacja)_ „ osób.
- #### **Powiązane dokumenty** _(Relacja)_ „ dokumentów.

---

<br/>

## Projekt

<br/>

- #### **Link zewnętrzny** _(Url)_ - Adres zewnętrznej strony projektu.

---

<br/>

## Osoba - szczegóły sortowania

<br/>

- #### **Pracownik** _(Grupa przycisków)_ - Wybór, czy osoba jest pracownikiem naukowym czy administracyjnym determinuje, czy zostanie wyświetlona w repozytorium osób.
- #### **Nazwisko** _(Tekst)_ - Pole umożliwia sortowanie osób alfabetycznie po nazwisku zamiast po tytule wpisu.
- #### **Imię** _(Tekst)_ - - „ po imieniu, w następnej kolejności po nazwisku, zamiast po tytule wpisu. W przypadku niewypełnienia pól, wpis w repozytorium będzie sortowany zgodnie z tytułem.

---

<br/>

## Wideo

<br/>

- #### **Typ** _(Grupa przycisków)_ - Wybór, czy wideo będzie wgranym plikiem czy osadzonym na stronie Iframem YouTube lub Vimeo.
- #### **Video:**
  - #### **Poster** _(Obraz)_ - Opcjonalny obraz wyświetlany przed odtworzeniem wideo.
  - #### **Video** _(Plik)_ - Plik wideo (sprawdź [**dopuszczalne formaty**](Media.md#wideo)).
  - #### **Napisy** _(Plik)_ - Plik napisów w formacie `.vtt`.
- #### **Iframe** _(oEmbed)_ - Link do filmu Vimeo/YouTube do umieszczenia na stronie.
- #### **Link zewnętrzny** _(Prawda / Fałsz)_ - Zaznaczenie pola sprawia, włącza w sliderze przycisk z zewnętrznym linkiem. W przypadku Iframe odnośnik prowadzi do źródłowej strony Vimeo / YouTube.
- #### _(Link)_ - W przypadku wyboru Video i Linku Zewnętrznego, w polu należy wprowadzić dowolny link, który będzie otwierany przyciskiem.

---
