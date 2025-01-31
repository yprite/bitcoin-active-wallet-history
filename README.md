# Bitcoin On-Chain Data - Active Addresses

## Overview
This website provides a visual representation of Bitcoin's on-chain data, focusing on **active addresses**. Users can interact with an **interactive chart** to analyze historical trends over different time periods.

## Features
- **Interactive Chart**: Displays the number of active Bitcoin addresses over time.
- **Time Range Selection**: Users can choose from different time ranges:
  - Last 7 Days
  - Last 30 Days
  - Last 1 Year
  - Last 3 Years
  - Last 5 Years
  - Last 10 Years
  - Since Inception
- **Real-Time Data Fetching**: Data is sourced from Blockchain.info.
- **User-Controlled Filtering**: Users can dynamically change the time range.

## Technologies Used
- **HTML**: Structure of the website.
- **CSS**: Basic styling.
- **JavaScript**: Handles data fetching and chart updates.
- **Chart.js**: Used for rendering the interactive line chart.
- **Chartjs-Adapter-Date-Fns**: Handles time-based scaling on the x-axis.

## Data Source
- **Blockchain.info API**: Retrieves the number of unique active Bitcoin addresses.
- **CORS Proxy**: `corsproxy.io` is used to bypass API restrictions.

## How It Works
1. The page loads with the default **7-day** chart view.
2. Users can select a different time range from the dropdown menu.
3. The site fetches Bitcoin active address data for the selected period.
4. The chart updates dynamically with the new dataset.

## Setup & Deployment
### Running Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/bitcoin-onchain-data.git
   ```
2. Open the `index.html` file in a browser.

### Hosting
This site can be hosted on any static hosting provider (e.g., GitHub Pages, Vercel, Netlify).

## Future Enhancements
- **Glossary**: Explanation of key Bitcoin on-chain terms.
- **Blog Section**: Updates and insights on Bitcoin active address trends.
- **Comparison Tool**: Analyze different time periods for deeper insights.

## Contributions
Feel free to contribute by submitting pull requests or reporting issues.

## License
This project is open-source and available under the MIT License.

