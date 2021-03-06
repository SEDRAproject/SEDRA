# SEDRA
Selective Entry Dynamic Risk Assessment - A mechanism for safely keeping borders open during Covid-19

SEDRA uses a risk assessment formula to determine a "Safety Index" for each country in the World. This formula is calculated upon:
- the probability of importing infected passengers from a given country
- the severity of the disease in that country (death rate per million)
- the confidence level of data reported by that country

The Safety Index, ranging from 0 to 100, is then used to partition the World in Risk Groups (Very Low, Low, Medium, High, Very High), and allow governments to adopt different control measures to these Risk Gorups, for instance free entry, PCR test, 5 days isolation, 14 days quarantine etc, accordingly. 

The full description of the scheme and a description of the mathematical model is to found here: https://www.medrxiv.org/content/10.1101/2021.12.05.21267311v1

Report Files:
Two report files are generated every week:
- An "AZ" report, with all countries sorted alphabetically
- An "SI" file sorted by Safety Index. This one is the most useful when deciding upon immigration rules.
- An Excel (XLSX) file containing the numerical values of the above.

Only the latest reports are kept in the "main" folder. Previous ones are to moved to "Previous_Reports"

Charts:
These files help get a glance at the trend of Covid safety by continent.
Charts are uploaded to https://sedraproject.github.io/index.html

The World is divided by continents and by subregion (South, North, Centre). This division does not always correspond to geographical regions, but it is done specifically to reduce the number of lines in a chart, in order to improve its readability. We try to keep these charts at max 15 lines.
