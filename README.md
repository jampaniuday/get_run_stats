# get_run_stats
- Karl Arao, OakTable, Oracle ACE, OCP-DBA, RHCE
- http://karlarao.wordpress.com


### The general workflow:

* Create the get_run_stats table and package
    * run_stats_create.sql
* Modify testcase.sh and insert custom SQL
* Execute testcase.sh with one parameter (the test name)

    ```
    sh testcase.sh TEST1
    ```
* Run the instrumentation SQLs
    * run_stats_hcc_query.sql
    * run_stats_query_all.sql
