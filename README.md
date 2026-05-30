# Netflix-Subscriber-BI-Analytics

An interactive Power BI dashboard tracking global subscriber engagement, monetization tiers, and cultural taste profiles for 25,000 users.

# 📋 Project Overview

This repository hosts a production-ready Power BI Business Intelligence solution that analyzes an aggregate dataset of 25,000 global Netflix subscribers.

Instead of relying on basic, flat reports that offer little business context, this project features an application-style dark interface designed around a relational star schema and advanced DAX calculations. It translates raw operational user data into strategic, localized insights regarding engagement depth, community tastes, and subscription tier distributions.

# 🛠️ System Architecture & Data Model

To maximize query execution speeds and keep performance completely smooth, the report discards flat-file structures in favor of a clean Star Schema:

f_Netflix_Users (Fact Table): Tracks unique Subscriber IDs, demographics (Country, Age Group), monetization levels (Subscription Type), Favorite Genre, and performance metrics (Watch Time).

d_Calendar (Dimension Table): A dedicated continuous calendar table generated entirely via DAX to provide bulletproof time-intelligence boundaries for platform login trends.

# 💡 Key Behavioral Insights Surface Content

The Engagement Leader: While the United Kingdom represents the largest absolute subscriber footprint ($2,592$ users), Canada holds the most dedicated power-users, leading the world with a massive average consumption rate of $511.4$ hours per subscriber.Monetization Hotspots: Germany serves as the prime hub for high-tier value retention, commanding the global leaderboard with a $34.4\%$ Premium Tier adoption rate.Cultural Taste Synchronicity: Audiences in India and Brazil share an identical entertainment footprint, with Romance ranking as the undisputed #1 favorite genre across both nations, whereas the UK market heavily prioritizes Horror.

# Contact & Links

Name: Aishika Nandy

LinkedIn: https://www.linkedin.com/in/aishikanandy/
