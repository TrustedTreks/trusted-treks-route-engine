# Trusted Treks – Route Engine Repository

## Purpose
This repository contains all routing logic, trip clustering, telemetry ingestion, and transportation optimization code for Trusted Treks.

The route engine is responsible for:
- Processing Uber and Lyft historical data
- Identifying peak pickup/drop-off clusters
- Creating optimized morning/evening driving routes
- Predicting surge windows
- Suggesting vehicle positioning
- Running energy usage and EV range planning (ID Buzz)

This repo acts as the “navigation brain” for dispatch and routing AI agents.

---

## Folder Breakdown

### /algorithms
Routing logic, clustering models, heuristic code, optimization scripts  
(e.g., k-means, DBSCAN, smoothing, heuristics, time-series)

### /data_import
Holds Uber and Lyft datasets

#### /data_import/uber
Raw Uber data (CSV exports)

#### /data_import/lyft
Raw Lyft data (CSV exports)

### /exports
Generated route maps, JSON outputs, CSV summaries

### Metadata
- `LLM_README.md`
- `instructions_for_agents.md`

---

## AI Agents Allowed to Access This Repo
- GPT-2 Dispatch Engine  
- GPT-6 Routing & Optimization AI  
- GPT-8 Founder AI  
- GPT-3 Finance AI (data modeling only)  

---

## AI Tasks Allowed
- Analyze Uber/Lyft data  
- Create route optimization logic  
- Write clustering algorithms  
- Suggest time-based route patterns  
- Generate .csv summaries  
- Create route export JSON  
- Build heatmaps / cluster files  
- Recommend data cleaning procedures  

---

## AI Tasks NOT Allowed
- Invent fake data  
- Modify raw CSV uploads  
- Delete datasets  
- Change folder structure  
- Overwrite human-created algorithms  

---

## Purpose Summary
The Route Engine repo is the core system used to determine:
- Where Trusted Treks vehicles should be  
- When peak demand occurs  
- How many rides/hour the system can achieve  
- The optimal AM/PM patterns for maximum revenue  
- EV energy patterns for ID Buzz  
