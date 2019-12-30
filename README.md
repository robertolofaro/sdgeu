# sdgeu
Dimension data tables created 2019-12 for a sample dashboard on EU Member States UN SDG status

# reference

- On the descriptions and information on UN SDGs: 
"Resolution adopted by the General Assembly on 25 September 2015 - 70/1. Transforming our world: the 2030 Agenda for
Sustainable Development", published by United Nations on 2015-10-21, A /RES/70/1

- On the data: 
UN SDG website https://unstats.un.org/sdgs/indicators/database/
data extracted on 2019-11-11
EUROSTAT website https://ec.europa.eu/eurostat/web/sdi
data extracted on 2019-11-11

- Subset extracted:
all the KPIs concerning EU 27, where available 2000-2018
the data about United Kingdom have been extracted but, following the announce of the confirmation of Brexit due on 2020-01-31, removed

# contents

This repository contains supporting tables for a sample dashboard created in 2019-12 on UN SDG values for EU Member States

The application will be released online in January 2020, but the datamart is available on kaggle https://www.kaggle.com/robertolofaro/sdgeu-datamart-sample

This repository contains "dimension tables", i.e. descriptions and additional information to complement the datapoints within the datamart
1. sdgeu_dimension_country.csv: country UN code, country name, country ISO code
2. sdgeu_dimension_goals.csv: UN SDG goal number and its description as per 
3. sdgeu_dimension_series.csv
4. sdgeu_dimension_time.csv

Additionally, the repository contains a CSV with a summary of the number of datapoints available for each combination of Goal, SeriesCode (i.e. KPI), TimePeriod (i.e. Year) within the datamart used for the sample dashboard: sdgeu_dataavailable.csv
