# Jest to mój pierwszy projekt. Opisuję tutaj znalezione błędy i wstawiam screeny wraz z krótkim komentarzem na zdjęciu.


### Po wejściu na stronę i spędzeniu na niej kilku sekund zauważyłem już błąd

* Zdjęcia produktów posiadają inną rozdzielczość
  
  Pierwszy produkt z prawej strony od góry zajmuje dwa razy więcej miejsca od pozostałych.
  Problem występuje w każdym podmenu gdzie znajdują się produkty oraz gdy będziemy sortować produkty korzystając z wewnętrznego szukacza.
  Większe zdjęcia posiadaja rozdzielczość o wymiarach 778x329 a wszystkie inne 384x329. W efekcie przyczynia się to do gorszego efektu wizualnego.
  
  ![Imgur](https://i.imgur.com/L2tWboc.png) 

  Na urządzeniach mobilnych wygląda to trochę inaczej. Zdjęcie znajduje się na górze.
  ![Imgur](https://i.imgur.com/i5RmB4F.png)

  Rozwiązaniem tego problemu jest poprawa zdjęć na odpowiednią rozdzielczość.


