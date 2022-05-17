# Case Study Explanations  
## Background Information: 
  As a Business Insights Associate, you have been tasked to work with our retail department to identify 
  the customer profiles of our biggest clients. This involves both business acumen and technical data skills. 

+ To test these skills, there is one key task to this case study:

### Task:
  Given the technical requirements of this position, please complete an analysis highlighting:
  1) Consumer Profiles
  2) Sales Trends & Visualizations
  3) Planning, Forecasting or Business Recommendations
  4) Additional Business Insights

Please note: For this case study, building a predictive model is not a requirement. If you choose to build a model, please be sure 
to highlight your process and results. 

###  Data:
  All relevant details can be found on Kaggle: https://www.kaggle.com/competitions/ga-customerrevenue-prediction/overview
  Case Study Deliverables: 
  There are 3 key deliverables for this task
  1. Creation of a 10-minute presentation outlining your case study, audience should be MLSE 
  senior leadership
  2. A technical markdown, which clearly documents your approach, insights, visualizations and 
  model development if applicable
  3. Tie your analysis to a business recommendation 

### Data Fields
 + fullVisitorId- A unique identifier for each user of the Google Merchandise Store.
 + channelGrouping - The channel via which the user came to the Store.
 + date - The date on which the user visited the Store.
 + device - The specifications for the device used to access the Store.
 + geoNetwork - This section contains information about the geography of the user.
 + socialEngagementType - Engagement type, either "Socially Engaged" or "Not Socially Engaged".
 + totals - This section contains aggregate values across the session.
 + trafficSource - This section contains information about the Traffic Source from which the session originated.
 + visitId - An identifier for this session. This is part of the value usually stored as the _utmb cookie. This is only unique to the
 user. For a completely unique ID, you should use a combination of fullVisitorId and visitId.
 + visitNumber - The session number for this user. If this is the first session, then this is set to 1.
 + visitStartTime - The timestamp (expressed as POSIX time).
 + hits - This row and nested fields are populated for any and all types of hits. Provides a record of all page visits.
 + customDimensions - This section contains any user-level or session-level custom dimensions that are set for a session. This is a
 repeated field and has an entry for each dimension that is set.
 + totals - This set of columns mostly includes high-level aggregate data.
