# Celestial Content Agent: The Autonomous AI Suite for Scalable News Discovery, Summarization, and Publishing

This project is part of a **mission to enhance a registered media group with over 26 million+ reach worldwide** by building an **autonomous AI-powered content agent**.  
The goal is to **automate news discovery, summarization, and publishing** in a way that scales our coverage, strengthens our editorial process, and maintains our high quality standards.

---

## 📌 Mission & Vision
Our media group has a proven track record of delivering impactful, timely, and engaging content to millions of readers.  
This system is designed to:
- **Expand coverage** to more sources, topics, and languages.
- **Leverage AI agents** to streamline workflows and improve efficiency.
- **Preserve editorial quality** while increasing publishing speed.
- **Enable 24/7 operations** without requiring constant manual intervention.
- **Enhance creative flexibility** for journalists, editors, and content managers.

---

## ⚖️ Copyright & Compliance
We are a **registered media entity** committed to:
- **Respecting copyright**: All external content used is sourced from licensed feeds, public APIs, or with explicit permission.
- **Proper attribution**: Summaries will credit original sources and link back when required.
- **Ethical AI use**: This agent supports editorial teams, it does not replace human oversight for sensitive or high-impact stories.

---

## 🚀 Features
- **Autonomous Agent** – Operates continuously, powered by AI.
- **Content Discovery** – Fetches news from approved APIs, licensed RSS feeds, or partner networks.
- **AI Summarization** – Condenses articles into concise, engaging one-liners.
- **Image Intelligence** – Selects or generates relevant visuals to match the story.
- **Platform-Agnostic Publishing** – Integrates with multiple distribution channels.
- **Duplicate Prevention** – Maintains a clean, non-redundant feed.
- **Customizable Tone** – Matches the style and voice of our media brand.

---

## 🧠 How the Agent Works
1. **Monitor** – Scans approved content sources continuously.
2. **Analyze** – Evaluates relevance and editorial fit.
3. **Summarize** – Uses LLMs to create concise summaries.
4. **Visualize** – Finds or generates relevant images.
5. **Publish** – Posts to chosen platforms with brand-consistent formatting.
6. **Log & Learn** – Tracks published content for analytics and avoids duplication.

---

## 🛠 Architecture
![Architecture Diagram](docs/architecture.png)

This architecture is modular:
- Swap the summarizer (OpenAI, Claude, Llama 3, etc.).
- Add or remove content sources dynamically.
- Target multiple platforms from one pipeline.

---

## 📦 Installation
```bash
git clone [placeholder]
cd ai-news-auto-poster
pip install -r requirements.txt
cp .env.example .env
````

---

## ▶️ Usage

Run manually:

```bash
python src/scheduler.py
```

Run hourly with cron:

```bash
0 * * * * /usr/bin/python3 /path/to/src/scheduler.py
```

---

## ⚙️ Environment Variables

See `.env.example` for required API keys and configuration.

---

## 💡 Example Use Cases

* Automated distribution of breaking news updates.
* Expanding coverage into new categories or languages.
* Rapid reporting during live events.
* Efficient content syndication across multiple platforms.

---

## 📜 License

MIT License
