# Dataset Information

## Source
Kaggle: BitcoinHeist Ransomware Dataset
https://www.kaggle.com/datasets/sapere0/bitcoinheist-ransomware-dataset

## Files Needed
- BitcoinHeistData.csv (download from Kaggle)

## Features Description
- address: Bitcoin address (string)
- year: Year of transaction (int)
- day: Day of year (int)
- length: Transaction length (int)
- weight: Transaction weight (int)
- count: Transaction count (int)
- looped: Number of loops in transaction (int)
- neighbors: Number of neighbors (int)
- income: Transaction value in satoshis (float)
- label: Ransomware family or 'white' for legitimate transactions (string)

## Dataset Size
- 2,916,697 transactions
- Time period: 2009-2018
- 29 ransomware families + 'white' label

## Usage
1. Download BitcoinHeistData.csv from Kaggle
2. Place in this data folder
3. Update file path in the main Python script if needed
