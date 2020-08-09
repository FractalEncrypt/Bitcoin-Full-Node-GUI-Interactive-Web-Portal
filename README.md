# Bitcoin-Full-Node-GUI-Interactive-Web-Portal
To house ideas related to translating the Bitcoin Full Node Sculpture blueprint to a fully functional web interface

# Desired Functionality

- Hover interactivity
  - Magnifying Glass on Hover
  - Show numerical data links on hover
  
  - Block Explorer Functionality
    - User enters block height, stats for the search are displayed within the Node 
      - (outer ring will have the current block hash, date/timestamp, mempool info, etc)
      - "zoomed" containers are displayed on sides of node circle
        - I may need to create a "Clock Hand" that has "holes" for the relevant data containers
        - This can disappear when not in use, then when in use, node cirlces rotate opposite directions and meet in the top center, and now rthe clock hand appears.
      - The data containers within the node related to the search will "highlight"
    - AI/ML dataset analysis could be used to predict blocks that will be mined in the future
      - Predict future date/time of block mining
      - Predict future hashrate
      - Predict future difficulty
      
  - Full Node Functionality
    - connected to full node
    - Coin Selection by UTXO GUI
    - Craft raw transactions and broadcast to the network
    - Outer Node stas ring would be kept current with network chaintip
