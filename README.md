Initial Population
- Generate a blank database, columns: name, appid, g2aid, banner, retailPrice, purchasePrice, resellPrice, keyCode
- Grab Steam game list from SteamAPI (http://api.steampowered.com/ISteamApps/GetAppList/v0001)
    - This will have to be updated daily
    - Insert into DB: name, appid

Features
- Scrape from Steam
    - Banner Image
    - Retail Price

- Search G2A by name, save ID

- Scrape from G2A by ID
    - Number of listing
    - Prices

- Input game names individually with/without purchase price and key
    - Calculate profit from purchase price vs resell price

- Input game names as a bundle with/without purchase price and key
    - Calculate profit from bundle based on bundle purchase price vs resell price of each individual game

- Provide URL of website and scrape bundle information to process
    - Will need to be pre-formatted/templated by hand for each website

- Mark games as sold, input sold price and associated fees

- Generate a graph/report of profit filtered by:
    - Date range
    - Source website
    - Price range

- Display current game inventory and potential profit/value

- Manage game DB with manual entry correction



