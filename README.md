🧭 The EDA Project Briefing
-------------------------------------
Decoding the DNA of Spotify Hits through Data & Sound Design

This repository contains our team’s submission for The Manhattan Project’s First Exploratory Data Analysis (EDA) Project, focused on Spotify Music Intelligence.

Our mission: analyze the Spotify audio features dataset to uncover actionable insights that guide artists, producers, and labels toward data-driven hit creation — blending sound analytics, listener psychology, and production science.

🚀 How to Run the Project
--------------------------------------------
To replicate our findings, open the main notebook: Spotify.ipynb

Dependencies used:

Pandas

Numpy

Matplotlib

Seaborn

🔍 Key Insights & Findings
--------------------------------------------
🎧 Strategic Music Direction
-----------------------------------
🎚️ 1. The Hit Zone Blueprint
Hit tracks cluster between 2.7–4.3 minutes, 100–130 BPM, and −6 to −4 dBFS loudness, representing the sweet spot for replayability and perceived punch.
Maintain energy (0.6–0.85) and danceability (0.55–0.8) balance for best listener engagement.

🎤 2. Vocal Dominance Wins
High-popularity tracks are vocal-led, showing low instrumentalness and low speechiness.
Polished studio mixes with low liveness outperform live-leaning tracks.

🎵 3. Song Composition Strategy
Short intros, early hooks, and mid-tempo grooves outperform longer experimental formats.
Key and mode have little influence — hook and flow drive success.

🎧 4. Mixing & Mastering Guidelines

Keep loudness in the hit corridor (−6 to −4 dBFS).

Moderate acousticness ensures mainstream polish.

Avoid ultra-long durations or low-energy profiles.

🌍 5. Language & Mood Strategy

Tamil → Party / Feel-Good

Korean → High-Energy / Hype

Hindi → Romantic / Filmic Mainstream

English → Global Scale / Sync-Ready

Prioritize Happy/Excited and Intense/Angry moods for wide reach; use Peaceful/Chill for retention and longer play sessions.

🎛️ 6. Rap & Groove Intelligence
Rap-leaning tracks perform best around 85–105 BPM or 120–140 BPM, with moderate speechiness for playlist success.

📈 7. Release & Growth Strategy

Exploit the long tail: identify hidden gems that meet hit-zone metrics but have low visibility.

Cross-promote through top artist and album clusters.

Optimize energy, loudness, and duration through iterative A/B testing.

⚠️ 8. Key Risks & Considerations
Extremes in acousticness, instrumentalness, liveness, or duration underperform.
Use these traits deliberately for niche artistry, not mass-market targeting.

🧠 Algorithmic Optimization Highlights
-----------------------------------------------
🎯 1. Cold-Start Priors:
Boost tracks with mid-high energy and danceability, low liveness/speechiness, standard 4/4 meter, and radio-length durations.

🔍 2. Hidden Gem Discovery:
Target low-popularity tracks already fitting hit-zone parameters (energy, loudness, danceability) for editorial tests and algorithmic boosts.

🧮 3. Feature Engineering:
Regularize correlated features (energy–loudness, acousticness–energy) and winsorize extreme energy_dance ratios for cleaner model performance.

🧩 Repository Structure
---------------------------------------
README.md → Project overview and summary

spotify_data_description.csv → Brief description of Raw dataset

spotify_tracks.csv → Raw dataset analyzed

Spotify.ipynb → Main analysis notebook

Spotify.pdf → Summary of insights & visuals

📽️ Presentation (Canva Link):
👉(https://www.canva.com/design/DAG0p4BsSF0/AXzRlGdgCucOXAAg8GYtTA/view?utm_content=DAG0p4BsSF0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h538f873404)

🎶 Conclusion
----------------------
This project bridges music production and machine intelligence — translating Spotify’s data patterns into strategic creative guidance.
It’s a roadmap for modern artists and producers who want to blend artistry with analytics and consistently land in the hit zone.

💫 “Data doesn’t kill creativity — it perfects it.”# Spotify-Tracks-Analysis
