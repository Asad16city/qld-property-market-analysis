# Property Deal Pipeline & Analysis System (Queensland)

A MySQL database and Power BI dashboard that tracks property leads through a deal pipeline and assesses each property against real Queensland market data.

## Business problem
A small Australian property investment team finds potential deals, contacts owners, and decides which properties are worth pursuing. Today the leads live in scattered spreadsheets, so the team cannot easily see where deals are stuck, which lead sources work, or whether a property is priced well compared with the market.

## Users
- Investor / deal manager: decides which deals to pursue
- Lead generator / acquisitions assistant: finds and logs leads

## Goals
1. Keep all leads, properties, contacts and interactions in one structured database.
2. Show the pipeline from first lead to closed deal, with conversion rates at each stage.
3. Compare each property with market benchmarks for its property type.

## Business questions
1. How many leads are at each pipeline stage?
2. Which lead sources produce the most deals?
3. How long do deals take to move from lead to close?
4. How have median prices for houses and units in Townsville changed since 2000?
5. How does each lead's asking price compare with the median for its property type?
6. What is the estimated rental yield of each property?
7. Which suburbs have the most pipeline activity?
8. Is the market heating or cooling, judged by sales volume and price growth over recent quarters?
9. How quickly does the team respond to new leads, and do faster responses lead to more deals?

## Data
- Market data: Townsville Residential Property Market dataset (Townsville City Council, via data.gov.au), licensed CC BY 4.0. Median sale prices from the Office of the Valuer-General and median rents from the Residential Tenancies Authority. Council-area level, quarterly, from September 2000.
- Leads, contacts and deals: synthetic sample data. No real people or properties are included.

## Tools
MySQL, Power BI, Excel, Git/GitHub

## Status
Phase 1: requirements complete. Phase 2: data profiling and cleaning (in progress)