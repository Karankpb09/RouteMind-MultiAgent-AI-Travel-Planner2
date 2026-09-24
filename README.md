
Planning a trip usually means juggling half a dozen browser tabs — one for flights, another for hotels, a third for the weather, and a notes app where you try to fit it all into a sensible order. TravelBrain collapses that into a single conversation. You describe the trip you want in your own words, the way you'd describe it to a friend — *"Plan a 10 day Europe trip from India in April, mid-range budget"* — and a team of AI specialists goes and researches it. One looks into flights, another finds places to stay, another checks what the weather will be doing while you're there. Their findings are then pulled together into a single plan you can actually act on, complete with a day-by-day schedule and a cost estimate. The result is a trip plan in about a minute, rather than an afternoon of research. Each part of the trip gets its own attention:

| | |
|---|---|
| ✈️ **Flights** | Likely airports, airlines on the route, typical duration and fare range |
| 🏨 **Hotels** | Accommodation options matched to your destination and budget |
| 🌤️ **Weather** | Current conditions and the forecast, with travel advice |
| 🗺️ **Itinerary** | A realistic day-by-day plan you can actually follow |
| 💰 **Budget** | An estimated breakdown of what the trip will cost |

Plans are saved as you go, so you can reopen a trip later and ask follow-up
questions without starting over.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your
local machine.

### Prerequisites

You'll need the following before you start:

- **Python 3.11**
- **[uv](https://docs.astral.sh/uv/)** — used to install dependencies
- **A PostgreSQL database** — a free [Render](https://render.com/) instance works fine
- **API keys** from the services below. All of them have free tiers:
  - [Groq](https://console.groq.com/)
  - [Tavily](https://tavily.com/)
  - [AviationStack](https://aviationstack.com/)
  - [OpenWeather](https://openweathermap.org/api)

Your results are split into tabs so you can jump straight to what you need:

**Plan** · **Itinerary** · **Flights** · **Hotels** · **Weather**

### Saving, exporting and revisiting

- Every trip is saved to the sidebar automatically — click any one to reopen it
- Ask follow-up questions on an open trip and it remembers the context
- Use the icons at the top of a result to **copy**, **download as Markdown** or **print**
- Click **New trip** to start fresh
- Switch between **light and dark mode** with the sun/moon icon at the bottom of the sidebar
- 
## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- [Groq](https://groq.com/) for fast AI inference
- [Tavily](https://tavily.com/), [AviationStack](https://aviationstack.com/) and
  [OpenWeather](https://openweathermap.org/) for the live travel data

---

Licensed under the **GNU General Public License v3.0**. See [LICENSE](LICENSE).
