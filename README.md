# tennis-tracker

Ultimately, I'm going to build a website to track all this information, but for now, I'm going to create a java command line tool that will store matches and be able to return them in a list when prompted
## The Problem

As a tennis player, I play a lot of matches and shorter games, and there's no one-place stop to log my matches and track my goals. Because of this, I'm making a comprehensive way to track my tournament and outside matches since not all of them get logged to UTR, and it'd be helpful to have a system in place to do so. 

## MVP Scope
Step 1: Set up Git repo and development environment
Step 2: Create the match data model
Step 3: Add Jackson JSON file storage engine
Step 4: Build a raw string score validator
Step 5: Integrate Picocli base command structure
Step 6: Implement the 'add match' command
Step 7: Implement the 'list matches' command
Step 8: Test the program

## How It Works

- (insert bullet points later)
  
<img width="1372" height="551" alt="Tools Final Project Flowchart drawio" src="https://github.com/user-attachments/assets/1ac73e6e-ed36-4e7f-ba27-e02398ba7c11" />


## Tech Stack

- Writing in Java, later HMTL/CSS
- External Libraries: Picocli, H2 Database
- To store data: Jackson for JSON file or Apache Commons CSV for CSV file

## Setup

```bash
git clone https://github.com/charishee/tennis-tracker
cd tennis-tracker
./install.sh 
```

## Usage

- N/A for now
## Roadmap


- how long the match took
- graph tracker to see growth - monthly, every 6 months, every year
- write notes about the match
- be able to mark if match is in UTR or not
- tennis journal
- mark different types of matches, 2 out of 3 set, 5 set, 3 set, pro set, tiebreaker, etc
- gamify it!
- mark whether it was completed or not
- calendar view for matches - both to see past matches and also schedule reminders for new ones
  
[Tools Final Project  - Eisenhower Matrix.pdf](https://github.com/user-attachments/files/34308938/Tools.Final.Project.-.Eisenhower.Matrix.pdf)


## Author

Charishee Modgil
https://github.com/charishee
