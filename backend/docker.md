# Uruchom FindMe server w dockerze

## Wymagania

- Docker >= v20.10
- Docker Compose >= v1.29.2

[⬇️ Pobierz Docker Desktop dla Windows](https://docs.docker.com/desktop/windows/install/)  

[⬇️ Pobierz Docker Desktop dla Mac](https://docs.docker.com/desktop/mac/install/)

\* Razem z instalacją Docker Desktop zainstaluję się automatycznie Docker Compose

## Uruchom serwer w dockerze

Przygotuj plik środowiskowy w folderze głównym projektu (/.env).
```bash
# Ustaw zmienną ENV na wartość docker
ENV = docker

# Ustaw port na którym serwer będzie nasłuchiwał
LISTEN_PORT = 3005
```

Uruchom serwer w dockerze z logami w konsoli.

```bash
$> yarn docker:up
```

ALBO uruchom serwer w tle (detached mode).

```bash
$> yarn docker:up -d
```

Zatrzymaj wszystkie uruchomione aplikację w tle (detached mode).

```bash
$> yarn docker:down
```

Usuń skompilowany obraz z dysku komputera (może być pomocne w przypadku błędów paczek npm).

```bash
$> yarn ocker:clear
```
