# IPL-Analysis
# 🏏 IPL Analysis (2008 - 2025)

An interactive Power BI dashboard analyzing Indian Premier League (IPL) 
data from 2008 to 2025, built using four datasets covering match results, 
ball-by-ball deliveries, player profiles, and team information.

 📊 Dashboard Highlights

- **Season Filte**r – Switch between seasons (2022–2025) to view 
  season-specific stats
- **Champion & Runner-Up** – Displays the winning and runner-up teams 
  for the selected season
- **Orange Cap & Purple Cap Holders** – Top run-scorer and 
  wicket-taker with player images and team details
- **Key Metrics** – Total 6s, 4s, matches played, teams, and venues
- **Top Batters Chart** – Bar chart showing sum of runs by batter 
  for the selected season

## 🗂️ Datasets Used

| File | Description |
|------|-------------|
| `ipl_matches_data.csv` | Match results, toss, venues, winners (2008–2025) |
| `ball_by_ball_data.csv` | Delivery-level data — runs, wickets, extras |
| `players-data-updated.csv` | Player profiles — batting/bowling style, images |
| `teams_data.csv` | Team names, short codes, logos |

## 🛠️ Tools Used

- **Power BI** – Dashboard design, DAX measures, data modelling
- **Power Query** – Data cleaning and transformation

## 📁 Files

- `IPL_project.pbit` – Power BI template file (connect your own data source to use)
