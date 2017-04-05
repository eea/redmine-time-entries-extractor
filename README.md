# redmine-time-entries-extractor

For specific usecase of EEA, do not use it :)

Usage

redmine_time_entries_extractor_run.sh --context_param redmineUrl="https://myredmine.me" --context_param aptkey="apikey" --context_param timeFrom="-1" --context_param timeTo="-5" --context_param outputDir="/redmine" --context_param dbDatabase=DBDATABASE --context_param dbHost=DBHOST --context_param dbPort=DBPORT --context_param dbUsername=DBUSERNAME --context_param dbPassword=DBPASSWORD --context_param dbSchema=DBSCHEMA --context_param forceDelete=FORCEDELETE

redmine_time_entries_extractor_run.bat --context_param redmineUrl="https://myredmine.me" --context_param apikey="upikey" --context_param timeFrom="-1" --context_param timeTo="-5" --context_param outputDir="c:/redmine" --context_param dbDatabase=DBDATABASE --context_param dbHost=DBHOST --context_param dbPort=DBPORT --context_param dbUsername=DBUSERNAME --context_param dbPassword=DBPASSWORD --context_param dbSchema=DBSCHEMA --context_param forceDelete=FORCEDELETE

Output

csv files, one per day

Mandatory context parameters:

apikey redmineUrl

Optional context parameters:

timeFrom - default [0] timeTo - default [-15] outputDir - default [/tmp/redmine]
