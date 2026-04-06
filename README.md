SmartBooker – Patienten-Buchungssystem
SmartBooker ist eine moderne Web-Applikation, die speziell für Patienten entwickelt wurde, um die Terminbuchung im Gesundheitswesen zu vereinfachen und zu digitalisieren. Das Projekt kombiniert Geschwindigkeit, Benutzerfreundlichkeit und modernste Web-Technologien.

🚀 Über das Projekt
Dieses Projekt ist ein Beispiel für moderne Softwareentwicklung unter Nutzung von künstlicher Intelligenz. Etwa 80 % des Codes und der Struktur wurden mit Hilfe von KI-Tools erstellt, um eine effiziente Entwicklung und saubere Architektur zu gewährleisten.

SmartBooker ermöglicht es Patienten:

Verfügbare Termine in Echtzeit einzusehen.

Buchungen unkompliziert und digital vorzunehmen.

Ihre Termine effizient zu verwalten.

🛠 Tech Stack
Das Projekt basiert auf einem robusten und skalierbaren Stack:

Framework: Next.js 15+ (App Router)

Sprache: TypeScript

Datenbank & ORM: Prisma mit PostgreSQL (Neon)

Styling: Tailwind CSS 4

Validierung: Zod

Icons: Lucide React

⚙️ Installation & Setup
Um das Projekt lokal auszuführen, folge diesen Schritten:

Repository klonen:

Bash
git clone https://github.com/DEIN_BENUTZERNAME/smartbooker.git
cd smartbooker
Abhängigkeiten installieren:

Bash
npm install
Umgebungsvariablen konfigurieren:
Erstelle eine .env Datei im Hauptverzeichnis (siehe .env.example) und hinterlege deine Datenbank-URL:

Code-Snippet
DATABASE_URL="postgresql://..."
Datenbank-Schema pushen:

Bash
npx prisma db push
Entwicklungsserver starten:

Bash
npm run dev
Öffne http://localhost:3000 in deinem Browser.
