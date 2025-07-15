# S2.03.Estructura-de-dades---MongoDB
📄 **Description - Exercise Statement**

This project consists of designing and documenting the structure of a database for an optician shop called **"Cul d'Ampolla"**. The main objective is to model the relationships between clients, glasses, suppliers, and sales using MongoDB technologies and represent this structure visually.

The project includes:
- MongoDB collection creation
- Sample data in JSON format
- Entity-relationship diagram created from the live database using Moon Modeler

The structure supports two perspectives:
- **Client perspective:** understanding purchases, referrals, and employee interactions
- **Glasses perspective:** understanding suppliers, technical details, and sales

---

💻 **Technologies Used**

- MongoDB
- MongoDB Compass
- Moon Modeler
- JSON (for document storage and import/export)

---

📋 **Requirements**

To open and view this project you’ll need:

- MongoDB Compass (latest version)
- Moon Modeler (Free or Trial Edition)
- Any system with MongoDB installed **OR** a MongoDB Atlas connection
- A Git client (optional, for cloning)

---

🛠️ **Installation**

1. Clone the repository:
git clone (https://github.com/ascargo/S2.03.Estructura-de-dades---MongoDB.git)
Open MongoDB Compass and connect to your local or cloud MongoDB instance.

Import the collections if needed:

Go to each collection in Compass (e.g., clients, glasses, sales, suppliers)

Use the “Import” button to upload the corresponding .json files

Open the .mmp file inside the /diagram folder with Moon Modeler to explore the schema visually.

▶️ Execution

No application execution is required. This project is focused purely on data modeling and documentation.

To explore the structure:

Use MongoDB Compass to navigate through the collections and documents

Use Moon Modeler to view relationships and schema design

🌐 Deployment

This project is not intended for production deployment, but you can import the structure into a MongoDB Atlas cluster if needed:

Create a free cluster at https://cloud.mongodb.com

Use the Data Import feature in Atlas or mongoimport via terminal

Use the .json files provided as your data source

🤝 Contributions

This is an academic project and not open for public contribution at this time.

However, if you're forking or collaborating privately, here are the recommended steps:

Fork this repository

Create a new branch:

git checkout -b feature/YourFeature
Commit your changes:

git commit -m "Add YourFeature"
Push your changes:

git push origin feature/YourFeature
Open a Pull Request

📌 Important Notes

This database structure was created for an academic assignment based on the following exercise:

An optician called "Cul d'Ampolla" wants to manage clients and glasses sales.
The system must track:

Suppliers (with address, contact, and tax ID)

Glasses (brand, lens data, frame type/color, price)

Clients (with optional referrer)

Employees who sold each item and the exact time/date of sale

