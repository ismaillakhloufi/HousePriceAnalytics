
# 🏡 Real Estate Data Dashboard

![Project Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Technologies](https://img.shields.io/badge/Technologies-Python%20%7C%20Power%20BI-blue)
![Database](https://img.shields.io/badge/Database-PostgreSQL-lightblue)

A web scraping and data visualization project that extracts house prices from [Mobawab.ma](https://www.mobawab.ma/), stores the data in a database, and creates an interactive dashboard using Power BI.

---

## 🌟 Project Overview

This project aims to provide actionable insights into real estate pricing trends by leveraging:
- **Web scraping**: Extracting real estate data (e.g., price, location, type, etc.) from Mobawab.ma.
- **Database storage**: Organizing and storing the data in a structured relational database.
- **Data visualization**: Building an interactive dashboard in Power BI for analysis and reporting.

---

## 🔧 Features

- Automated **data extraction** from Mobawab.ma using Python and BeautifulSoup.
- Structured data storage in **PostgreSQL** for easy querying and management.
- A visually rich and interactive **Power BI dashboard** for real estate trends.

---

## 🛠️ Tools & Technologies

| Technology    | Purpose                           |
|---------------|-----------------------------------|
| ![Python](https://img.shields.io/badge/-Python-blue?logo=python) | Web scraping with BeautifulSoup and Requests |
| ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-blue?logo=postgresql) | Database for storing extracted data          |
| ![Power BI](https://img.shields.io/badge/-Power%20BI-yellow?logo=power-bi) | Dashboard for data visualization             |

---

## 📂 Project Structure

```
📦 real-estate-dashboard
├── 📂 data            # Folder for scraped data and backups
├── 📂 scripts         # Python scripts for scraping and loading data
├── 📂 database        # Database schema and SQL scripts
├── 📂 dashboard       # Power BI files
├── README.md          # Project documentation
└── requirements.txt   # Python dependencies
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+ installed
- PostgreSQL database setup
- Power BI Desktop installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-dashboard.git
   cd real-estate-dashboard
   ```

2. Install the Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure the database:
   - Update the database connection string in `scripts/config.py`.

---

## 🖥️ Usage

1. Run the **scraping script** to extract data:
   ```bash
   python scripts/scrape_mobawab.py
   ```

2. Load the data into the database:
   ```bash
   python scripts/load_to_db.py
   ```

3. Open the **Power BI dashboard** file and connect it to your database to visualize the data.

---

## 📊 Dashboard Preview

![Dashboard Screenshot](https://via.placeholder.com/800x400.png?text=Dashboard+Preview)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes and submit a pull request.

---

## 📧 Contact

For questions or suggestions, feel free to reach out:

- **Ismail Lakhloufi**  

  📧 ismail.lakhloufi.10@gmail.com  
  📞 0777527102
```

### Personnalisation :
1. Remplacez `https://via.placeholder.com/800x400.png?text=Dashboard+Preview` par un lien vers une capture d’écran de votre tableau de bord.
2. Ajoutez vos propres liens GitHub dans les sections `Clone` et `Contact`.
3. Mettez à jour les noms des scripts et fichiers Power BI si nécessaire.

Ce README rendra votre projet clair et attrayant pour les visiteurs et potentiels contributeurs. 🎉
