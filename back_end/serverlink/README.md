## Setup
You must:

1. Run init_db.php (creates tables + inserts an admin user)
2. Insert a row into the servers table.
3. Change the ip and port inside run_serverlink.sh - the ip MUST match your server's external ip!
4. chmod 755 run_serverlink.sh && ./run_serverlink.sh

I may have forgotten a step. Worst case you will run into a db insert issue.

On the 3SPN side you *must* enable bot stat recording.
