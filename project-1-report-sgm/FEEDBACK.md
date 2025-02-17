# COMMENTS

## Report

* good report
* nice abstract and intro 
* explained sys arch with diagram
* implementation in detail 
* changed from mongodb to postgres
  * why?
* changed from cron job to faktory
* very detailed explanation of the collected data, 
* napkin math contains volume predictions - mentions volume will increase  - in per week

## Implementation

* NOTES.MD contain the documentation 
* using faktory and docker 
* in `fetch_data.py` = why is the location of local machine ?
* Hardcoded output CSV file pat `output_file = "/home/mvenkatarama/Documents/DSSMP/Projects/project1_impl/4chan_crawler/data/posts_table_oct_23.csv"`
  * Ok, but...
* so does analysis.py
* there is also a .ipynb file; you are ahead of the game I guess?
* every 5 mins crawler for 4chan 
* using time.sleep for 5 mins for crawling subreddits
  * Why not just schedule it via faktory?
* Is this all running in VM?
* they have implemented everything needed except the list of subreddits and boards

# NOTES FROM 1:1

* thought mongo would be easier but... turns out mongo is not 100% easy
* analysis code has some hard coded stuff
* code recently changed away from using sleep.

# GRADING

## Report

* ACM format 0/-1000
* Final system design 10/10
* Plots 10/10
* Updated data projections 5/5 

### Total

25

## Implementation

* Continuous data-collection + Data-schema 29/30
* reddit crawler 5/5
* subreddits not hardcoded 10/10
* 4chan crawler 5/5

### Total

49
