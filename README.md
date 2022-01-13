# Configuration

- Edit `sudo vim ~/.bashrc`
- Edit the `backup.bash` file and add the database name 
- Add the below configuration in the file 

```shell
export MG_CRM_DB_USER="your database user name"
export MG_CRM_DB_PASSWORD="your database password"
export SERVER_IP="Your server IP"
```
After this done schedule the cron job at the desired time for below command
```shell
/yourpath/backup.bash
```
