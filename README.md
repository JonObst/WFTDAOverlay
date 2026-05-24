CRG Stream Overlay with Team Color Swatches
A modified version of the default CRG ScoreBoard stream overlay that adds a team color swatch to the left of each team name in the scorebug, making it easy for viewers to identify which team is which color at a glance.
Changes from Default Overlay

Adds a 10px color swatch to the left of each team name in the scorebug
Swatch color is pulled from the scoreboard color type set in Team Colors in CRG

Setup

Back up your existing index.html and index.css from the CRG html/overlays/ folder
Replace them with the files from this repo
In CRG, open Team Colors for each team and set the scoreboard Background color to that team's jersey color
The swatch will appear automatically in the scorebug

Requirements

CRG ScoreBoard v2025.x (tested on v2025.9 and v2025.10)
No other dependencies -- drop-in replacement for the default overlay files

License
GPL-3.0 -- see LICENSE for details.
