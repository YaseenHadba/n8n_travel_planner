# ✈️ AI Travel Email Planner (n8n + OpenAI)

This project is a smart travel planning workflow built using [n8n](https://n8n.io/). It automatically generates personalized travel itineraries using AI (OpenAI GPT), enriches them with real-time flight, resort, and activity data from public APIs, and delivers a fully formatted HTML email to the user via Gmail.

## 🚀 Features

- ✅ Collects trip info from user (origin, destination, dates)
- ✈️ Fetches best 3 flight options via SerpAPI
- 🏨 Finds top 3 resort options in destination city
- 🎯 Adds local activities with links and summaries
- 🤖 Uses OpenAI to generate a polished, HTML email
- 📩 Sends the final email to the traveler via Gmail

## 🧰 Stack

- **n8n** – Automation platform (low-code)
- **OpenAI (ChatGPT 4o)** – Email content generation
- **SerpAPI** – Flights, Hotels, and Activities
- **Gmail API** – Email delivery
- **JavaScript** – Code node for JSON formatting

---


📸 Output Example
Section	Preview
✈️ Flights	3 options with airline, times, duration, connections
🏨 Resorts	Linked names, images, price per night, nearby places
🎯 Activities	Clickable names, short descriptions
📧 Email Format	Clean, HTML-based with sections & styling

Want to try it live? Clone the repo, set up n8n locally or in the cloud, and run the webhook.
------

📄 License
This project is open-source under the MIT License.
------
🤝 Author
Yaseen Hadba
GitHub Profile → https://github.com/YaseenHadba


