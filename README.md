- 👋 Hi, I’m @Ehammond79
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ehammond79/Ehammond79 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Install dependencies
cd quickstart/frontend
npm install
# Start the frontend app
npm start
# ...
PLAID_COUNTRY_CODES=GB # Or any supported European countries (DE, ES, FR, GB, IE, NL)
PLAID_REDIRECT_URI=http://localhost:3000/
PLAID_PRODUCTS=payment_initiation
{
  "interest_rate": "0.0199",
  "transfer_codes": {
    "ach": {
      "account_number": "string",
      "routing_number": "031176110",
      "wire_routing_number": "string",
      "supports_debit": true,
      "supports_credit": true
    },
    "eft": {
      "account_number": "string",
      "institution_number": "004",
      "branch_number": "1320",
      "supports_debit": true,
      "supports_credit": true
    },
    "iban": {
      "account_number": "string",
      "bank_code": "NORD",
      "country_code": "FR",
      "location_code": "ZZ",
      "branch_code": "80A",
      "supports_debit": true,
      "supports_credit": true
    },
    "payment_card": {
      "card_number": "string",
      "expiry_month": "01",
      "expiry_year": "2021",
      "security_code": "363",
      "supports_debit": true,
      "supports_credit": true
    },
    "acats": {
      "account_number": "string",
      "receiving_member_identity": {
        "organization": {
          "name": "Doe Business, Inc.",
          "structure": "sole",
          "mcc": "5542",
          "owner_identity_ids": [
            "string"
          ],
          "tax_identifier": {
            "tax_authority": "IRS",
            "tax_payer_id": "string"
          }
        },
        "person": {
          "first_name": "Jane",
          "middle_name": "Joan",
          "last_name": "Doe",
          "date_of_birth": "1987-01-31",
          "tax_identifier": {
            "tax_authority": "IRS",
            "tax_payer_id": "string"
          }
        },
        "email": "jane@plaid.com",
        "mailing_address": {
          "lines": [
            "413 Leeward Way",
            "Apt 3A"
          ],
          "city": "San Francisco",
          "region": "US",
          "country": "US",
          "postal_code": "94106",
          "phone": "+1 415 555 1212"
        },
        "id": "d7f1b8b9-0006-4135-91c0-b5532045a314",
        "name": "Jane Doe"
      },
      "dtcc_clearing_ids": [
        "string"
      ],
      "supports_debit": true,
      "supports_credit": true
    }
  },
  "maturity_date": "2018-08-28",
  "statements": [
    {
      "statement_id": "string",
      "open_date": "2018-08-28",
      "close_date": "2018-08-28",
      "balance": "100.95",
      "document_url": "string"
    }
  ],
  "id": "R13oiR6lC5jNC5jK",
  "last_activity_at": "2020-04-21T12:45:00+00:00",
  "ownership_type": "individual",
  "owner_identity_ids": [
    "string"
  ],
  "non_owner_identity_ids": [
    "string"
  ],
  "status": "active",
  "type": "depository",
  "subtype": "checking",
  "name": "Vacation Money",
  "official_name": "Pro Checking",
  "display_mask": "9833",
  "opening_date": "2018-01-31",
  "current_balance": "850.55",
  "available_balance": "149.45",
  "tax_advantaged": true,
  "currency": "USD",
  "non_iso_currency": "string"
}
