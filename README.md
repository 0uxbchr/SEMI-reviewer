# SEMI Freight

SEMI Freight is a freight transport prototype connecting shippers, loaded-trailer owners, truck owners, drivers, and transport companies. It demonstrates the journey from requesting transport and comparing offers to assigning a driver, confirming delivery, and recording payment acknowledgment.

The experience includes a mobile-style interface for individual users and a dedicated management portal for transport companies. It is a demonstration, not an operational transport service.

## Languages

- Interface: English, French, and Arabic, including right-to-left layout.
- Built with: TypeScript, JavaScript, HTML, and CSS.
- Demonstration currency: Algerian dinar (DZD).

## Demo accounts

The account selector provides eight fictional profiles. Demo profiles do not require a password.

| Account type | Demo profiles | Experience |
| --- | --- | --- |
| Shipper | Karim Benali — independent; Samir Belkacem — Atlas client | Mobile interface for requests, offers, delivery, and payment acknowledgment |
| Loaded-trailer owner | Leïla Saidi | Mobile interface for requesting tractor-only transport |
| Truck owner | Amine Mansouri | Mobile interface for offers, vehicles, missions, and driver applications |
| Driver | Nabil Cherif — independent; Adel Karim — Atlas driver | Mobile interface for applications and assigned missions |
| Transport-company manager | Mohamed Ali — Atlas Transport; Yasmine Haddad — Nord Logistique | Company portal for requests, missions, fleet, drivers, clients, and documents |

Company managers manage their own company. There is no platform-wide administrator account. Company drivers use the mobile interface; financial amounts are hidden for Adel by default.

## Suggested review

1. **Transport request to delivery:** use Karim to request transport, Amine to submit an offer, and Karim to accept. Continue through loading, departure, arrival, delivery photo, recipient name, and signature. Explore payment acknowledgment and mutual reviews.
2. **Company operations:** use Samir's private request and Mohamed's company portal to assign a tractor, trailer, and Adel as driver. Compare the views available to Adel and Yasmine.
3. **Driver opportunities:** use Nabil to apply for a mission, then Amine to accept the application. Return to Nabil to follow the assigned mission.
4. **Private requests:** explore the choice to keep a request private or explicitly open it to the market after its waiting period.
5. **Fleet and relationships:** explore availability, clients, the company's private transport network, and document submissions.
6. **Presentation:** switch between Arabic, French, and English, and compare light and dark themes.

## Data and demonstration limits

All supplied people, companies, vehicles, requests, and scenarios are fictional. Use fictional information and documents when reviewing the prototype.

Changes, uploaded files, and signatures are stored in the same browser on the same local address. They remain after a refresh, but do not sync to other devices. Tabs share demonstration data while keeping their own selected accounts. Switching profiles does not reset the demo. Resetting the demo or clearing browser data removes saved changes.

Account access and company separation demonstrate intended workflows; they are not production security. Registration and document verification are simulated. No SMS is sent, no money is transferred, and no live GPS tracking is provided. Payment records acknowledge a simulated external payment. Premium views are previews; unimplemented future services are not operational.

## Review materials

[Download the runnable prototype](https://github.com/0uxbchr/SEMI-reviewer/raw/refs/heads/main/SEMI-Reviewer.zip), then extract the ZIP.

1. Install Node.js 22 LTS if it is not already installed.
2. On Windows, double-click **Start SEMI.cmd**. On macOS or Linux, open a terminal in the extracted folder and run `sh start.sh`. Alternatively, run `npm start` in that folder.
3. Open **http://127.0.0.1:4173/demo** and choose a demo profile.
4. Keep the launch window open while reviewing. Press Ctrl+C to stop.

No dependency installation or build is needed. Open the address above rather than double-clicking the included HTML file.

The download includes the runnable build, assets, required notices, and a small local launcher. Original application source files, source maps, development files, and development history are excluded. As with any browser application, the compiled JavaScript delivered to the browser remains inspectable.

This repository provides reviewer documentation and a runnable download. No GitHub account is needed to access the public review materials.

