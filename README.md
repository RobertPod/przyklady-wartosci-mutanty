# Przykłady, własności mutanty 

Source code from my presentation „Przykłady, Własności, Mutacje, czyli wypaśne testy jednostkowe”. 

1. Slides https://slides.com/koziolek/przyklady-wlasnosci-mutacje
1. Getting code: `git clone https://github.com/Koziolek/przyklady-wartosci-mutanty.git`
1. Running code:
    1. `mvn test` – run basic test set without pitest mutations.
    1. `mvn test -Pm` – run all tests with pitest mutations.
1. Knows issues:
    1. When running `m` profile JGiven generates reports in main directory
    
  