# 📦 DevOps Foundations

### ⏰ Category 14: Scheduling & Automation (Commands 151–162)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 151 | `crontab` | Manages scheduled tasks for current user account. | `crontab -e` |
| 152 | `crontab -e` | Opens current user's cron table for editing. | `crontab -e` |
| 153 | `crontab -l` | Lists all scheduled cron jobs for user. | `crontab -l` |
| 154 | `crontab -r` | Removes all scheduled cron jobs permanently. | `crontab -r` |
| 155 | `cron` | Executes scheduled background tasks automatically every minute. | `sudo systemctl status cron` |
| 156 | `at` | Schedules one-time command execution at specified time. | `at 10:30 PM` |
| 157 | `atq` | Lists all pending one-time scheduled jobs. | `atq` |
| 158 | `atrm` | Removes specified pending scheduled job safely. | `atrm 2` |
| 159 | `batch` | Executes commands automatically when system load decreases. | `batch` |
| 160 | `sleep` | Pauses command execution for specified duration. | `sleep 10` |
| 161 | `time` | Measures execution duration of specified command accurately. | `time ls -la` |
| 162 | `timeout` | Stops command after specified execution time expires. | `timeout 30 ping google.com` |
