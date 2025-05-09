# Startup Search Engine Project – CS46 Final Project

Team Members: Kazuma, Hill, Haven, Evelyn  
Course: CS46 – Data Structures, Spring 2025

## Overview

This project implements an interactive command-line search engine to explore the 2021 Crunchbase Startup Funding dataset. Users can:

- Search startups by sector, keyword, or investor (supports partial matches)
- View the top funded startups
- View the top sectors by number of startups (as both a table and bar chart)
- Explore startup connections based on shared investors using DFS traversal
- Save top funded startups into a CSV file for future use

The system applies core data structures and programming concepts from CS46.

## Data Structures Used

- Hash tables for sector and investor lookups
- Graphs to represent startup–investor relationships
- Stacks for DFS traversal
- Lists, dictionaries, and counters for data organization

## Libraries Used

- pandas  
- collections  
- matplotlib  
- tabulate

## How to Run

1. Open the project in Google Colab:  
   [Startup_Search_Engine_Colab_Link](https://colab.research.google.com/drive/1WMj0UTw_1abGkF8oPvJv5qryCuszLdjg?usp=sharing)

2. Upload `startup_funding2021_cleaned.csv` into the Colab environment.

3. Run all cells in the notebook.

4. Use the on-screen menu to search by sector, keyword, or investor; view top funded startups or sectors; explore connections via DFS; and export results.

## Project Highlights

- Partial match support for flexible keyword and investor search
- Clean visual output for top sectors using matplotlib
- Graph traversal to uncover connections across startups
- CSV export functionality for saved results

Thanks for checking out our Startup Search Engine.
