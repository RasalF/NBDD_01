# NBDD_01

CucumberBDD FW with TestNG and Maven

# HOW T0 RUN TEST

mvn verify -Denv=qa -Dbrowser=ch -Dcucumber.filter.tags="@smoke"

#How to merge code
git checkout main
git pull origin main
git merge features branch name goes here.
Example: git merge QA-1
git push origin master

#How fix merge conflict

##To write a commit message and get out of VI, follow these steps:

press i (i for insert)
write your merge message
press esc (escape)
write :wq (write & quit)
then press enter