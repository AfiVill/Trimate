# Trimate
A Streamlit travel workspace for researching destinations, tracking flight/hotel prices, mapping routes, building budgets, and checking visa/safety info — with PDF and CSV export.


 ✨ Key Features

- **Destination Explorer:** Filter and search curated places, regions, and activities based on trip styles and vibes.
- **Dynamic Route Mapping:** Visualizes your itinerary on an interactive Mapbox plot, detailing segment distances and transfer times.
- **Flight & Hotel Analytics:** Log, edit, and analyze observed prices to calculate median, average, and best available rates.
- **Budget Engine:** Automatically compiles your observed analytics, daily allowances, and contingency buffers into a master trip budget.
- **Safety & Visa Intelligence:** Integrates entry requirements and safety advisories based on your origin/passport and destination.
- **Collaboration & Export:** Share the underlying SQLite database, download raw CSVs, or generate a polished PDF brief of the entire trip.

 🗂️ Categories & Trip Styles

The planner adapts the pacing and suggestions based on your selected trip category:
*   **Culture:** Focuses on historic anchors, museums, and old-town walks.
*   **Adventure:** Highlights nature, outdoor anchors, and buffers for weather recovery.
*   **Food:** Prioritizes markets, signature local food stops, and evening resets.
*   **Beach:** Structures days around coastlines, harbors, and sunset windows.

 🔄 Workflow

1. **Initialize Trip:** Select your destination, passport country, month, and pacing mode from the sidebar.
2. **Research & Log:** Use the *Flights reviewed* and *Hotels reviewed* tabs to log prices.
3. **Review Insights:** Check the *Dashboard* for high-level insights on seasonality and safety.
4. **Refine Route:** Head to the *Route planner* to view your day-by-day itinerary and transfer logistics.
5. **Finalize Budget:** Check the *Budget engine* for a rolled-up financial estimate.
6. **Export:** Save the trip session and generate a PDF report via the *Collaboration + reports* tab.


 🤝 Collaboration

The application stores all data locally in `storage/travel_intelligence_v7_3.db`. To collaborate:
- Share the `.db` file directly with your peers.
- Or, use the built-in CSV export/import functionality via the app's collaboration tab.

📦 Building an Executable
