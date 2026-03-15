# glit-vault

GLIT Vault
Analytics architecture for football clubs (SaaS)

Data is fragmented across too many systems - clubs typically use multiple platforms at the same time:
Match event data, video analysis, GPS training data, medical data, scouting reports, etc.

The goal is to integrate data into a unified analytics platform for staff:
Sporting directors, scouts, analysts, scientists, physios, coaches, etc.

The project scope: Nordic players and leagues - focusing on players that have yet to reach their peak (>26 years old)

The development of this project will follow specific themes that are laid out in the degree "IT Architecture" at Erhvervsakademi Aarhus:
1st semester: Data Visualization
2nd semester: Application Development
3rd semester: Application Integration
4th semester: Architecture

Requirements specification:
Dashboard - pages such as reports, alerts, database, finances, analytics, staff planning calendar, squad planner
Sectors - varying layout and permissions (user-groups) to ensure confidentiality - scouts will be restricted to certain
~~ features, sporting director will have the most complete view
Storage - players, leagues, clubs, staff, contracts, values
Integration - scraping, collection, entries, uploads, downloads
Calculations - contract amortization, league level adjustment, climate adaptability, cognitive level, analysis, adaptability, cultural
~~ fit, Club Fit
AI/ML utilization - translation from words to numbers, speech to text, data lookup, comparison, trends, analysis
UI - works in the cold, big buttons, high contrast, mobile focus

Topics:
Scout - data entry is time-consuming, and scout reports lead to a mess of PDF files full of biased sentences, scouts need to be able to
~~ speak or write into a box that translates words into numbers
Player mentality - if a player loses their parent or goes through a divorce, the Saas should have a feature that adds a note and
~~ uses that data to compare technical ability before, during, and after, to add perspective - did their performances drop during
~~ personal tragedy? -1 mental resillience
Communication - Members across the platform should be able to communicate through direct messages and forums
Reports - parser: "Undersized, Missing speed, Super technique = Speed: +1.5 / Technique: +4.5"

Sources: Transfermarkt, Capology, FBref, UEFA, Fotmob

Tech stack:
HTML, CSS, JS, C#, Python, Cloud, PostgreSQL, Windows/Mac/iOS/Android
