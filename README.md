# Capstone-Project_Consumption-and-Forecasting
This blocks of codes helps to calculate energy consumption and predict future consumption

#These funtions takes five input tables:

- `appliances`
- `consumption_log`
- `energy_balance`
- `energy_purchase`
- `energy_accounts`

It returns:

- `consumption_log_filled` — with estimated daily usage and remaining units
- `energy_balance_updated` — with lifetime consumption, current units, days remaining, and forecast depletion date
