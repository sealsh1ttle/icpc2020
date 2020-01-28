----------------------------------------------------------------------------------------------------------------
# ICPC2020 - Replication Package

bots.txt contains the names of the 147 bots.

users.txt contains the names of the 728 users.

users_noCommitData.txt contains the names of the 13 users whose past commits data was not computed.

raw_data (folder) contains cross-proj_scenario.csv and single-proj_scenario.csv (i.e., the raw data of the 32062 PRs used for the cross-project and single-project scenarios).

tables-complete-results-statistical-tests (folder) contains the tables with the complete results of statistical tests, for both the single-project scenario and the cross-project one, grouped by independent variable (PastCommits and PastPRs).

sentiment_polarity (folder) contains:
- the raw conversations(.csv) analyzed by the two tools;
- the cross-project_scenario subfolder with the 4 boxplots of the sentiment polarity scores by SentiStrengthSE and Senti4SD for the general and source code discussions, when PastCommits and PastPRs are used as independent variables in the cross-project scenario;
- the single-project_scenario subfolder with the 4 boxplots of the sentiment polarity scores by SentiStrengthSE and Senti4SD for the general and source code discussions, when PastCommits and PastPRs are used as independent variables in the single-project scenario.


----------------------------------------------------------------------------------------------------------------
