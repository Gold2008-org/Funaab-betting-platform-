# FUNAAB Vote — responsive front-end prototype

## Preview
## Included
- Student signup/login and student profile fields
- Departmental, College and SUG election sections
- Separate free official-ballot (one ballot per position per browser session)
- Candidate prediction UI with ₦1,000 per entry and a maximum of two entries per session
- Nomination form catalogue and simulated checkout
- Wallet balance, simulated top-ups and transaction history
- Election countdown, sample results and admin dashboard preview
- Mobile navigation, animations, modals and toast notifications

## Important: preview feature
This is a browser-only prototype. It does not connect to FUNAAB student records, a database, an identity-verification provider, a payment gateway, an actual election system, or a regulated betting/payout provider yet. data is held in JavaScript memory; the sample signup profile is stored in browser localStorage for convenience. No real money is accepted, transferred, wagered or paid out till it's officially launched and live. Prediction entries only simulate a ₦1,000 wallet deduction and are capped at two per page session.

## Run locally
Open `index.html` directly, or from this folder run:
`python -m http.server 8000`
Then visit `http://localhost:8000`.


## Added in the student dashboard update
- Registered profile details are repeated in a personal dashboard after signup/login, including full name, matric number, email, phone, department, college and level.
- Dashboard activity summaries show wallet balance, prediction entries, ballots and nomination form applications.
- Each prediction shows its stake, illustrative odds, potential payout and potential profit; candidate directory cards show the stake recorded on that candidate.
- Candidate directory filters across SUG, College and Departmental elections, with profile details and manifesto views.
- Candidate names, roles, biographies and manifestos are illustrative sample content and must be replaced with approved records.

## Developer 
LADEJOBI OLUWASEMILORE