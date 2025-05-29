# Cloudflare DNS Manager
A sleek and intuitive web interface for managing your Cloudflare DNS records. This tool allows users to connect via API Token and Zone ID, view existing DNS records, and perform actions like add, edit, delete, and filter.


# 🚀 Features
🔐 Connect securely using your Cloudflare API Token and Zone ID

📋 List all DNS records in a card-style UI (mobile-friendly)

➕ Add new records with full support for multiple DNS types

✏️ Edit existing records with type-specific fields (MX, CAA, SRV, URI, etc.)

🗑️ Delete records with confirmation prompt

🔍 Filter records by name/content and type

🌈 Beautiful, responsive UI with live status messages

# 📁 How to Use
Clone the repository:

<pre>
git clone https://github.com/your-username/cloudflare-dns-manager.git </pre>
Open index.html in your browse

Enter your Cloudflare API Token and Zone ID, then click Connect.

Manage your DNS records right from the interface.

# ⚠️ Disclaimer
This is a client-side-only tool. Your API token is never stored or sent anywhere except directly to the Cloudflare API.

The app uses a CORS proxy (https://cors.obitosnu.workers.dev/proxy) to communicate with the Cloudflare API due to browser CORS restrictions. You can replace it with your own if needed.

# 🔐 Security Recommendation
Always use read/write scoped API tokens and do not expose your token publicly.

Do not deploy this file publicly with an embedded token in the code.

# 📜 License
This project is open-source under the MIT License.

