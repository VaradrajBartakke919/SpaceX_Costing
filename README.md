# SpaceX_Costing
## Data Science Capstone Project

SpaceX API: https://github.com/r-spacex/SpaceX-API
url
response = requests.get(url)
response.json() ### to view the data

### Wrangling Data using an API
data = pd.json_normalize(response.json())



