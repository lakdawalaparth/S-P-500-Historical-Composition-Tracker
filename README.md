S&P 500 Historical Composition Tracker

**Description:**
A Python-based tool that tracks and analyzes historical changes in S&P 500 index composition. This project scrapes Wikipedia data to maintain a comprehensive database of S&P 500 constituent changes from 2008 to present, including company additions, removals, and yearly snapshots of index composition.

**Key Features**
Scrapes and processes S&P 500 historical data from Wikipedia
Maintains a SQLite database of company information and index changes
Tracks company additions and removals with precise dates
Generates yearly snapshots of index composition
Provides easy-to-use query functions for historical analysis
Handles multiple date formats and data validation
Includes comprehensive logging for monitoring and debugging

**Tech Stack:**
Python
Pandas for data processing
SQLite for data storage
Beautiful Soup (via pandas read_html) for web scraping

**Database Schema**
1.Companies: Stores unique company information (ticker, name, CIK)
2.Holdings: Tracks yearly index composition
3.Historical Changes: Records all additions and removals with dates

**Use Cases**
Track index composition changes over time
Analyze sector rotation and market trends
Research historical market events
Generate custom investment universe snapshots
Support backtesting of investment strategies

