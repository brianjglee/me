# Electrical Engineer (Plasmonics / Communications / Microwave / RF)

#### Technical Skills: Lumerical FDTD, MATLAB, Keysight ADS, Python

Hello! My current research projects involve translating ideas from microwave and RF electronics to tiny electromagnetic devices. When visible and near-infrared (NIR) light interacts with subwavelength structures, strong field confinement supports resonant modes. At metal and dielectric surfaces, this coupling can excite surface plasmon polaritons: surface-bound electromagnetic waves associated with collective electron oscillations. These waves propagate along the interface and decay away from it.

We attempt to apply microwave structures, like cavities and waveguides, and techniques, like impedance matching, to understand and enhance electromagnetic properties at the nanoscale. In my research, I use Lumerical FDTD to design and simulate plasmonic devices, then characterize their optical response with spectroscopy and microscopy. I’ve developed designs that improved optical transmission by 25% and produced 26× electric-field enhancement relative to baseline designs.

Meanwhile, since I’m learning the physics and engineering principles behind microwave electronics, I’m designing high-frequency circuits as a hobby. Join me in my journey in all things electromagnetics!

I also enjoy learning about data analytics, machine learning, and communications.

## Projects

Below are projects I’ve completed in machine learning, data analytics, plasmonics, and high-frequency circuit design.

## Enhanced Optical Transmission with a Nanoslit Transformer

[Paper Link](https://www.sciencedirect.com/science/article/pii/S266695012600146X)

How can we improve the amount of light transmitted through a nanoscale slit? In this project, I designed and simulated multilayer plasmonic nanoslit structures in Lumerical FDTD. Taking inspiration from quarter-wavelength impedance transformers in microwave engineering, I explored how a nanoscale structure could improve coupling between free-space light and a metal-insulator-metal (MIM) plasmonic waveguide.

The optimized design improved optical transmission by up to 60% compared with the baseline design. This project explores how familiar RF concepts can guide the design of optical devices. My related work was presented at the 2025 IEEE Green Energy and Smart Systems Conference and the IEEE Silicon Beach Annual Conference, where it received a Best Poster Award.

## Broadband Field Enhancement for Surface-Enhanced Raman Spectroscopy

Surface-enhanced Raman spectroscopy (SERS) uses enhanced electromagnetic fields near a surface to strengthen the Raman signal from molecules. In this project, I studied plasmonic structures for electromagnetic field enhancement and quantified this enhancement experimentally via SERS.

I used Lumerical FDTD to investigate how the structure’s geometry and resonances affected the local electric field. The resulting design produced 26× electric-field enhancement relative to a baseline design. I also supported experimental characterization and analysis using spectroscopy and microscopy. This work was presented at the 2025 MRS Fall Meeting, 2026 Engineering Horizons, and the 38th CSULB Student Research Competition.

## 2.5 GHz to 5 GHz Frequency Doubler

[Project Link](https://drive.google.com/drive/folders/16uOcr8zH6xvGFkNuyfOgYP5oi4vpMuZC?usp=drive_link)

I designed and simulated a BFP420 BJT frequency doubler in Keysight ADS using harmonic-balance analysis. The design produced a 5 GHz output of −7 dBm from a 2.5 GHz input while suppressing undesired harmonics to −59 dBm.

After simulation, I fabricated an FR-4 prototype using copper-tape RF traces and characterized its frequency response with a spectrum analyzer and vector network analyzer.

## 9 GHz Power Amplifier

[Project Link](https://drive.google.com/drive/folders/144v_WeVsoRgzEKuDb7DXbJwozMXUPGyg?usp=drive_link)

For this project, I designed and simulated matching networks for a single-stage power amplifier using an S-parameter file of an NE67383 MESFET in Keysight ADS. The amplifier achieved 12 dB of gain over a 10% bandwidth centered around 9 GHz. This project was one of my first real design projects in Keysight ADS, giving me hands-on experience with high-frequency matching and RF circuit simulation without having to worry about DC-biasing the transistor, but still helping me explore different tools in ADS such as the optimization feature.

## Acoustic Piano to Digital MIDI Controller

[Project Link](https://drive.google.com/drive/folders/1MkgJkEuPikOoJbhd8d_K6pq7zs_JsCn7?usp=drive_link)

![breadboard_image](/assets/breadboard-image.jpg)

I designed a mixed-signal sensing interface to convert the linear mechanical motion of piano key hammer into digital time-of-flight measurements. The system used TCST2103 optical encoders, 555-timer Schmitt-trigger circuits, and an Arduino Nano. This project brought together optical sensing, analog circuitry, and microcontroller programming to explore a practical musical application.

## Predicting Home Value with a Random Forest Regressor

[Project Link](https://github.com/brianjglee/zillow-time-series-rfr)

I scraped housing data from Zillow using Python, imported it into a pandas DataFrame, and cleaned the data for analysis. After exploring the dataset, I created a random forest regressor to predict the home values of current listings.

## Uber Supply and Demand Data Analysis

[Project Link](https://github.com/brianjglee/uber-supply-demand)

Using a provided dataset, I imported a CSV file into a pandas DataFrame and cleaned the data for analysis. I used pandasql for SQL-style queries, along with pandas functions like `to_datetime`, `merge`, `plot`, and `groupby`, to explore supply and demand patterns and gather business insights.

## Cocktail Recommendations with Natural Language Processing

[Project Link](https://github.com/brianjglee/cocktail-recommendations)

Cocktails can be overwhelming, so the goal of this project was to use natural language processing to recommend drinks.

Using PRAW, Reddit’s API, I compiled text from multiple Reddit comments. Then, with spaCy’s Named Entity Recognition (NER), I created a model to extract cocktail names that people enjoyed. I wrote a spell-checking function based on the distance between strings to correct misspellings and build a more consistent list of cocktail names.

Finally, I explored how cocktails appeared together in posts. Using mlxtend’s frequent pattern growth algorithm, I found commonly grouped cocktails, and I built an item-item collaborative filtering approach using a correlation matrix to recommend cocktails.

## COVID Data Analytics

[Visualization Link](https://public.tableau.com/app/profile/jeong.gyu.lee/viz/CovidDashboard_17024232948120/Dashboard1?publish=yes)

![COVID dashboard](/assets/covid-dashboard.png)

This project was my first foray into creating a database and uploading, exploring, and visualizing data. I used Docker to create a MySQL container, then connected to it with Azure Data Studio. Using SQL queries, I created tables for COVID deaths and vaccinations and bulk-uploaded data from CSV files.

For my data exploration, I focused on how infection rates, death rates, and vaccinations changed over time and across locations. I used aggregate functions, common table expressions (CTEs), and views to help answer those questions.

Finally, I exported the tables to Excel, connected them to Tableau, and created a visualization of COVID deaths and infections over time. Thanks for taking a look!

## Research and Publications

- [J. G. Lee, Y. Trivedi, A. Ahmed, “Free Space to MIM Slit Plasmonic Waveguide Coupling via a Quarter-Wavelength Impedance Transformer” (2026)](https://www.sciencedirect.com/science/article/pii/S266695012600146X)
- [J. G. Lee, K. Luhm, S. Carrillo, A. Ahmed, A. Lee, “Review of Light Detection and Ranging (LiDAR) Systems from Rotating Mirrors to Chip-Scale Beam Steering” (2026)](https://doi.org/10.1016/j.optlastec.2026.116440)
