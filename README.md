# Serverless Wetter-API mit TypeScript

Hier habe ich die AWS Lambda Funktion aus [diesem Projekt](https://github.com/evagrean/sls-wetter-api) mit **TypeScript** geschrieben.

## Dependencies und Tools

Dafür habe ich mit Hilfe des `Serverless Framework` und dem `aws-nodejs` Template die Boilerplate für einen neuen Service erstellt und den Endpoint eingerichtet. Details zu Konfiguration und Setup nachzulesen in der [JavaScript Version des Projekts](https://github.com/evagrean/sls-wetter-api).

Um TypeScript benutzen zu können, habe ich `serverless-plugin-typescript` und `typescript` als devDependencies installiert, sowie eine `tsconfig.json`  Datei hinzugefügt. Dabei habe ich die Standard-Einstellungen übernommen, die das Plugin anbietet. Und natürlich heißt handler.js jetzt `handler.ts`.

## Link

[Link zum Endpoint für diese TypeScript Wetter-API](https://0u8u73qc99.execute-api.eu-central-1.amazonaws.com/tsdev/wetter)






