# Shell Scripting with CodeSignal
## System Automation with Shell Scripts

This repository contains shell scripting tasks organized by units for practicing system automation.

---

##  UNIT 1: Package Management

### Task 1
Write a shell script from scratch. The script should:

- List all installed packages and save them to `package_list.txt`
- Update the list of available packages and save the output to `updated_list.txt`
- Simulate an upgrade and save the output to `upgrades.txt`
- Print the contents of all three files using `cat`

---

##  UNIT 2: User Management

### Task 2
Write a script that:

- Prints the list of users to `users.txt`
- Shows the current user, their home directory, and shell
- Adds a new user and sets up their home directory
- Switches to the new user and shows their environment details
- Run the script to observe the output

---

### Task 3
Write a shell script that:

- Creates two users: `Cosmo` and `Nova`
- Set home directories:
  - Cosmo → `$PWD/users/spaceship`
  - Nova → `$PWD/users/galaxy`
- Use `-d pathname` to set home directory
- Print their entries from `/etc/passwd`
- List the `users` folder to verify home directories

---

##  UNIT 3: Disk Usage Monitoring

### Task 4
Write a script that:

- Monitors `/tmp`
- Uses `df` to show disk usage
- Uses `du` to display directory usage
- Creates a large file
- Rechecks disk usage
- Displays updated statistics

---

##  UNIT 4: Scheduling Tasks with Cron

### Task 5
Create and automate a script using `cron` that:

- Checks disk usage daily
- Runs every weekday at 9 A.M.
- Appends output to a log file
- In `check_usage.sh`, append:
  - Current date
  - Human-readable disk usage (`df`)

---

##  UNIT 5: Automating Backups

### Task 6
Write an automated backup script.

---

### Task 7
Write a script that:

- Creates `data` and `logs` directories
- In `data`:
  - `d1.txt` → "File D1"
  - `d2.txt` → "File D2"
- In `logs`:
  - `l1.log` → "Log L1"
  - `l2.log` → "Log L2"
- Defines source directories
- Creates timestamped backup directories
- Copies files to backup folders
- Lists contents of the `backups` directory

---

##  Author
Suriya C U

Shell scripting practice for CodeSignal – System Automation Course
