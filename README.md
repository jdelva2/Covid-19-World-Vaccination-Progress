# [Covid-19 World Vaccination Progress](https://jdelva2.github.io/Covid-19-World-Vaccination-Progress/)

## Planning the Project
### The Covid-19 event has been a very troubling time for all of us around the world. Due to this, I plan to use this project to conduct a study on the amount of people getting vaccinated and leverage off fear that some people have about the virus. With this I hope to share this with family members and close friends that getting fully vaccinated is one step closer to helping combat the virus.

## Questions worth discovering
#### - How has the Covid Vaccination Process progressed throughout the year?
#### - What does the total vaccination progress for certain countries look like? i.e U.S, Mexico, Canada, China, UK, etc.
#### -What does the daily vaccination progress look like for certain countries?

## Loading in libraries/modules
```markdown
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

import warnings
warnings.filterwarnings('ignore')
```

## Data Pre-Processing
### Getting a glimpse of the data
```markdown
#Gives a quick description of the data
vaccine_data.describe()
```
