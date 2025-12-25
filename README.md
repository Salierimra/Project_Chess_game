# Chess Game Analysis Project

## Project Description
Using the Chess.com API to collect all my chess games and analyze the data using Tableau(Python-Jupiter Notebook)
EDA + cleaning datas (Python)
Exporting datas in csv (Python)
Visualization with Tableau

## Project Goal
Improve my chess skills through data-driven insights with Tableau visualization.

## Key Questions
- Which openings give me the best results?
- Which openings should i train?
- Do my results depend on the date(month)?
- Do my results depend on the time of day?
- How does my rating evolve over time in classical, rapid, and blitz formats?
- What is the ELO distribution of my opponents?

## Technologies Used
- Python(numpy,pandas,chess.com API)
- Tableau

## Findings
- Which opening should i train ?
    B01(scandinavian defence) type opening is the most played opening it should be train but let's focus into details
  <img width="1442" height="721" alt="image" src="https://github.com/user-attachments/assets/575662ef-bf5b-46e5-9f19-cfcc3bff4172" />

    <img width="1443" height="715" alt="image" src="https://github.com/user-attachments/assets/2382790e-b261-4a2c-a6d0-9314766c6538" />

    D00(Queen's pawn opening) should be train because it's often played and my results aren't so good

  <img width="1445" height="712" alt="image" src="https://github.com/user-attachments/assets/a82b5179-7b0e-4de8-b913-647bc49f7ec6" />

- Do my results depend on the time?
    Seems that playing at 6AM gives me the best results but playing at 10PM is not a good idea (i'm kinda surprised)

  <img width="1442" height="722" alt="image" src="https://github.com/user-attachments/assets/7a7e1d3e-29e2-43e4-a811-e97b0934f3a7" />

## Data Collection
Every month using python script which uses chess.com API
