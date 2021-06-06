# one-nativefier
Example usage with nativefier


### install nativefier

npm install -g nativefier


### install promagen
    sh .apicra/promagen

### execute promagen by nativier

    nativefier 'localhost'

## API foundation

.promagen - web management dla devops
.apicra - skrypty do instalacji env
.apifunc - funkcje, implementacja apiunit
.apiunit - metadane potrzebne do stworzenia aplikacji
.apibuild - budowanie plaikacji, deployment

---

1. Środowisko - .apitee
+ pobranie
+ uruchomienie
+ aktualizacja


2. Kod - .apifork
+ pobranie
+ aktualizacja


3. Aplikacja - .apibuild
+ przygotowanie modułów, bibliotek
+ kompilacja, budowanie kodu aplikacji


4. Uruchomienie aplikacji -  .apiexec
+ start
+ stop


---

Kod - .apifork

    sh .apifork/download

Uruchomienie aplikacji -  .apiexec
    
    sh .apiexec/start

    sh .apiexec/stop

---

uruchamianie



# First Steps with .apicra

## on linux

### install
    sh .apicra/install


### .apicra

    sh .apicra/update



### .apiexec
start application 

    sh .apiexec/start

stop application

    sh .apiexec/stop

### open in browser
    sh .apicra/browser


## on windows

### install
    .apicra\install.bat

### start
    .apicra\start.bat


### open in browser
    .apicra\browser.bat



