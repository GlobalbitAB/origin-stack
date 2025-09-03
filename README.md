# 🌍 OriginStack — East Africa Export Verification Hub

OriginStack is a **lean digital infrastructure** for verifying and showcasing African exporters to global buyers.  
It combines **trust badges, SEO visibility, and structured onboarding** into one system — starting with East Africa.

---

## 🚀 Current Sites

- [VerifyCoffee.com](https://verifycoffee.com) → Pan-African coffee trust & traceability hub  
- [KenyaOrigin.com](https://kenyaorigin.com) → Coffee, tea, flowers, avocados  
- [EthiopiaOrigin.com](https://ethiopiaorigin.com) → Coffee, sesame, livestock  
- [UgandaOrigin.com](https://ugandaorigin.com) → Coffee, tea, vanilla, fish, agriculture  
- [RwandaOrigin.com](https://rwandaorigin.com) → Coffee, tea, horticulture  

---

## 📂 Repository Structure

origin-stack/
├── docs/ # Shared templates & specs
│ ├── badge-spec.md # Exporter verification badge rules
│ ├── exporter-profile-template.md
│ ├── report-template.md
│ └── verification-checklist.md
│
├── automation/n8n-flows/ # Automation workflows (n8n JSON)
│ ├── badge_qr_page_generator.json
│ ├── buyer_waitlist_to_mailerlite.json
│ └── exporter_intake_to_sheets.json
│
├── sites/ # Country-specific content
│ ├── ethiopiaorigin.com/content/
│ ├── kenyaorigin.com/content/
│ ├── ugandaorigin.com/content/
│ ├── rwandaorigin.com/content/
│ └── verifycoffee.com/content/
│
├── CONTRIBUTING.md # Contribution guide
├── LICENSE # MIT open license
└── README.md # This file
