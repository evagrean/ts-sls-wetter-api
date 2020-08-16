# Serverless Wetter-API mit TypeScript

Zu Übngszwecken habe ich hier versucht, den Service aus [diesem Projekt](https://github.com/evagrean/sls-wetter-api) anstatt mit JavaScript mit **TypeScript** zu schreiben.

Dafür habe ich zunächst mit Hilfe des `Serverless Framework` und dem `aws-nodejs` Template die Boilerplate für einen neuen Service erstellt. Details zu Konfiguration und Setup nachulesen im [JavaScript Projekt](https://github.com/evagrean/sls-wetter-api).

Um TypeScript benutzen zu können, habe ich `serverless-plugin-typescript` und `typescript` als devDependencies installiert, sowie eine `tsconfig.json`  Datei hinzugefügt. Dabei habe ich die Standard-Einstellungen übernommen, die das Plugin anbietet. Und natürlich heißt handler.js jetzt `handler.ts`.

[Link zum Endpoint für diese TypeScript Wetter-API](https://0u8u73qc99.execute-api.eu-central-1.amazonaws.com/tsdev/wetter)






