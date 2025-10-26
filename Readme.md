# 🏡 Harbour-Agent  

## 📖 Description  
**Harbour-Agent** is an **AI-powered real estate investment assistant** that helps small-scale investors, landlords, and homeowners evaluate properties instantly—without the cost and delays of traditional feasibility studies.  

With just an address, Harbour-Agent automatically gathers and analyzes a wide range of **public data sources**—including parcel and tax records, zoning and land use codes, rental benchmarks from HUD and Census APIs, flood and environmental risk data, and neighborhood indicators such as schools, crime, and demographics. It will also use computer vision to scan through MLS photos to determine different parts of condition of house. 

It then compiles this information into a **professional-grade feasibility and investment report**, showing:  
-  What can be legally developed on the property (e.g., single-family home, ADU/DADU, duplex, or mixed-use)  
- Maximum buildable area and zoning restrictions (setbacks, coverage, height)  
- Financial forecasts (rental income, resale value, and cash flow projections)  
- Market and neighborhood insights to measure demand and livability  

By automating a process that traditionally costs **thousands of dollars** and takes **weeks of consultant time**, Harbour-Agent delivers **fast, affordable, and enterprise-grade decision support in minutes**, empowering everyday investors to act with confidence and speed.  

---
## Data Flow and Processes
### Figma Visuals: [Data Flow](https://www.figma.com/design/QcYAm2GUw0EsSRiOYh4PLT/Harbour-Agent?node-id=0-1&p=f&t=GJ3VLp8RgHcmrmDx-0)
### (King County Parcel Data, ChatGPT) -> All Data Gathered Formated -> Send to GPT for analysis and formatting, using Master Output format
## 📊 Data Points  

### 🏠 House  
- Address  
- Year Built  
- Square Footage  
- Bedrooms & Bathrooms  
- Lot Size  

### 📑 Parcel & Tax Records  
- Parcel Boundaries  
- Assessed Land Value  
- Assessed Structure Value  
- Total Assessed Value  
- Past Sale Dates & Prices  
- Owner Information (when available)  

### 🏗️ Zoning & Land Use  
- Zoning Category  
- Setbacks & Height Limits  
- Lot Coverage Rules  
- ADU/DADU Eligibility  
- Existing Building Permits  
- Prior Remodels  
- Code Violations / Citations  

### 💰 Market & Financial  
- Area Rental Data (HUD & Census benchmarks)  
- Property-Specific Rental Estimates  
- Median Home Prices in Area  
- Estimated Price for Subject Property  
- Local Inventory & Market Trends  

### 🏘️ Neighborhood & Quality of Life  
- Local School Ratings & District Information  
- Crime Data & Safety Index  
- Environmental Risk Factors (floodplain, EPA hazards)  
- Nearby Transit Access & Walkability  
- Neighborhood Demographics & Income Levels  

## Thoughts
- Investors often analyze tens-hundreds of properties in a given area, and quickly filtering out those that aren’t feasible can be extremely time-consuming. Many property listings also suffer from poor photos that fail to reflect the true value or condition of the home. As a result, investors browsing the public market may see long listing times and assume that other investors have already deemed the property unprofitable—causing them to pass on opportunities that could be worth hundreds of thousands of dollars. This is where Harbour Agent comes in. By simply entering an address, the agent uses advanced computer vision to analyze MLS photos and evaluate the property’s condition alongside official city data, helping investors uncover hidden value that others overlook.
- Personal story: I bid on an fix and upper waited for 3 days for seller to review offer and chose another offer. Started doing search again on Redfin I see something I like, I look at the basic stat on Redfin, then I go onto google to search for nearby area in an more detaied report which redfin doesn't have, local news, google earth, then I go onto city's website to find the zoning of the land is it LR zoned, is it NR zoned? What kind of properties is allowed in this zoning, in this specific neighborhood, are there any restrictions in this city/neighborhood. What is the rent in this area, how much after repair cost will be my ARV, is my ARV really accurate? Does the market here usually sell more then valued, or below market, I need to see an few actual example nearby 


## Reach Goal
- To make the analysis more intuitive, Harbour-Agent can generate **AI-powered visualizations** that illustrate possible development scenarios—allowing investors to literally *see* the future potential of their property.  

## Divide and Conquer Schedule Block
### Oct 25 - etc
- Build out one page simple UI/UX
- Connect King County assessor database and make the output of, Address, Year Built, Square Footage, Bedrooms & Bathrooms and Lot Size output correctly.
