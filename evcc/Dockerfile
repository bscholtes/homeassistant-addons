# Verwende das offizielle EVCC-Image als Basis
FROM evcc/evcc:latest

# Kopiere ggf. zusätzliche Dateien oder passe Konfigurationen an
COPY run.sh /run.sh
RUN chmod +x /run.sh

# Setze den Startbefehl
CMD [ "/run.sh" ]

