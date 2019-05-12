Należy skonfigurować przeglądarkę wykorzystywaną podczas testowania.
Ustawić:
System.setProperty("webdriver.firefox.bin", "path\\firefox.exe");
lub odpowiednik dla innej przeglądarki.
Dla przeglądarki Firefox konieczne jest pobranie programu geckodriver.
https://github.com/mozilla/geckodriver/releases
Oraz ustawienie ścieżki do niego:
System.setProperty("webdriver.gecko.driver", "path\\geckodriver.exe");
