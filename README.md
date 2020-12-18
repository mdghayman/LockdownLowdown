# LockdownLowdown

1.1. What problem are we solving?
- Understanding the optimal political and financial response to the COVID19 pandemic
  - Dangerous idea of "following the best science".
  - Science is not stationary or one-sided.
- With time series analysis, we can show:
  - How much the science has changed, and continues to change; and
  - Negative effects of lockdowns (some of which are more clear in poor countries, so would thus require extension of the model).
- Noting that long-term effects of lockdowns will only become apparent in the long-term.

1.2. What niche have we found?
- This problem varies widely across location and time.
- Focus here is the Uniteg Kingdom (UK), from 1 January 2020 to present.
  - Geographical scale of the whole of UK.
  - Also possible to examine the 4 nations of the UK (England, Northern Ireland, Scotland, and Wales) with the database used.
  - Also possible to examine municipalites or scale of local lockdowns, by integrating additional databases.
- Possible extension to selected countries, for comparison.
- Oxford COVID-19 Government Response Tracker (OxCGRT) database shows COVID-19 and lockdown data globally:
  - 187 countries, along with subnational regions;
  - 18 indicators and 13 flags, along with COVID-19 infections and deaths;
  - Daily data points, which are updated daily;
  - Currently over 32MB, including notes.
  
1.3. What would we like to analyse?
- Benefits of lockdown, including:
  - Reduced COVID-19 deaths;
  - Reduced short-term illness due to COVID-19 infections; and
  - Reduced potential long-term health impacts of COVID-19 infections.
- Costs of lockdown, including:
  - OxCGRT measures (containment and closure policies, economic policies, health system policies, and miscellaneous policies);
  - Additional opportunity costs which are often excluded (e.g. suspended cancer screening and treatment); and
  - Societal changes and lifetime impacts (which may be impossible to measure using existing metrics).
  
2.1. Is this a data analysis or recommendation study?
- Data analysis (recommendations may result, but decision-making is necessarily a social and political process)

2.2. What will this study deliver?
- Clearer understanding of potential costs of lockdown; and
- Clearer understanding of opportunity costs of ignoring societal issues other than COVID-19.

2.3. How does this study address the problem?
- Politicians and practitioners will be better placed for decision-making.
- Citizens will be better informed.
- Some drastic changes have been made across the world in 2020, presenting the opportunity to learn from this study's results, and work together going forward with COVID-19 and future crises.

3.1. Is this a machine learning or deep learning study?
- The initial core model is a machine learning time series analysis.
- However, deep learning Recurent Neural Networks (RNN) may add greater insight, and these will be applied next.
- The sentiment analysis on media and social media will experiment with Long Short-Term Memory (LSTM) RNN deep learning analysis.

3.2. Where will the data come from?
- Primary:
  - OxCGRT Covid Policy Tracker
- Secondary:
  - Twitter API
- Tertiary:
  - Wikipedia
  - Published news media
  - JHU CSSE COVID-19 Data
  - UK Government's COVID-19 recovery strategy
  - Full Fact

3.3. How can this study be deployed?
- Ideally, users can experiment with relationships among variables and time scales:
  - Probably best achieved with a Streamlit app
- Open source approach could lead to further improvements.
- Potential extension module can forecast outcomes based on policies recommended by users, which may inform discussion and understanding for effective and rapid democratic responses to future crises.
