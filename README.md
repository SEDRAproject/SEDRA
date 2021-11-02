# SEDRA
Selective Entry Dynamic Risk Assessment - A mechanism for safely keeping borders open during Covid-19

SEDRA uses a risk assessment formula to determine a "Safety Index" for each country in the World. This formula is calculated upon:
- the probability of importing infected passengers from a given country
- the severity of the disease in that country (death rate per million)
- the confidence level of data reported by that country

The Safety Index, ranging from 0 to 100, is then used to partition the World in Risk Groups (Very Low, Low, Medium, High, Very High), and allow governments to adopt different control measures to these Risk Gorups, for instance free entry, PCR test, 5 days isolation, 14 days quarantine etc, accordingly. 

The full description of the scheme and a description of the mathematical model is to found on: https://www.researchgate.net/publication/353038411_SEDRA_Selective_Entry_Dynamic_Risk_Assessment_A_mathematical_model_to_safely_reopen_the_borders_post_Covid-19

Report Files:
Two report files are generated every week:
- An "AZ" report, with all countries sorted alphabetically
- An "SI" file sorted by Safety Index. This one is the most useful when deciding upon immigration rules.

Only the latest reports are kept in the "main" folder. Previous ones are to moved to "Previous_Reports"

Graphics files (SEDRA Charts):
These files help get a glance at the trend of Covid safety by continent.

The World is divided by continents and by subregion (South, North, Centre). This division does not always correspond to geographical regions, but it is done specifically to reduce the number of lines in a chart, in order to improve its readability. We try to keep these charts at max 15 lines.
