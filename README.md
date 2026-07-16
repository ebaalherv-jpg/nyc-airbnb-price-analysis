# NYC Airbnb Price Analysis

Analysis of Airbnb listings across New York City boroughs to understand
how price varies by room type, neighbourhood, and review activity.

## Business Question
How do listing prices and demand differ across NYC boroughs and room
types, and what does that suggest about market positioning?

## Tools
Tableau Public, CSV data (Inside Airbnb)

## Key Findings
- Hotel room listings command the highest average price (~$600),
  well above private rooms and shared rooms.
- Manhattan has the highest concentration of "Entire home/apt" and
  "Private room" listings compared to other boroughs.
- Price and review volume don't move together consistently across
  boroughs, suggesting review count alone isn't a strong price predictor.

## Calculated Fields
   - `Duration (min)`: DATEDIFF('minute', [started_at], [ended_at])

## Dashboard
[View the interactive dashboard on Tableau Public](https://public.tableau.com/views/EmilioAlfonsoCmovaranpreciosydisponibilidaddeAirbnbentrezonasdeNuevaYork/EmilioAlfonso-CmovaranpreciosydisponibilidaddeAirbnbentrezonasdeNuevaYork?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Data Source
Inside Airbnb, New York City listings summary:
https://insideairbnb.com/get-the-data/
