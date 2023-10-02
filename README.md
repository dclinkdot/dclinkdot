- 👋 Hi, I’m @dclinkdot
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
dclinkdot/dclinkdot is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import re, os

id_pattern = re.compile(r'^.\d+$') 

API_ID = os.environ.get("API_ID", "23679347")

API_HASH = os.environ.get("API_HASH", "7de55f9c943538839c4bdb877724a773")

BOT_TOKEN = os.environ.get("BOT_TOKEN", "6342241349:AAGPIotH3nI3rjl1xwW-JECiJYxeN4Qx0wQ") 

FORCE_SUB = os.environ.get("FORCE_SUB", ") 

DB_NAME = os.environ.get("DB_NAME", ")     

DB_URL = os.environ.get("DB_URL", "mongodb+srv://Devaraju:UI5aFVqlgYeb80v3@cluster0.ues7phb.mongodb.net/?retryWrites=true&w=majority")
 
FLOOD = int(os.environ.get("FLOOD", "10"))

START_PIC = os.environ.get("START_PIC", "https://te.legra.ph/file/119729ea3cdce4fefb6a1.jpg")

ADMIN = [int(admin) if id_pattern.search(admin) else admin for admin in os.environ.get('ADMIN', '5421323272').split()]

PORT = os.environ.get("PORT", "8080")
