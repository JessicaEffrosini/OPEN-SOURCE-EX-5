# OPEN-SOURCE-EX-5
# NAME : L Jessica Effrosini
# REG NO : 212224110026
# DEPT : CSE(iot)
# STEPS INVOLVED:
# STEP 1 : sudo -i
# STEP 2 : crontab -u harry -e
# STEP 3 : # Run daily at 12:30 PM
# 30 12 * * * /bin/echo "hello"

# Run every 2 minutes
# */2 * * * * /bin/echo "Hi I'm Running"

# Run daily at 2:23 PM
# 23 14 * * * /usr/bin/logger "RHCSA EXAM TRAINING"

# Run daily at 12:00 PM
# 0 12 * * * /usr/bin/logger "EX200 in Progress"

# STEP 4 : crontab -u harry -l
# STEP 5 : systemctl status crond
# STEP 6 : systemctl start crond systemctl enable crond
# STEP 7 : sudo -u harry /bin/echo "hello" sudo -u harry /usr/bin/logger "RHCSA EXAM TRAINING"
# STEP 8 : journalctl | grep RHCSA
# OUTPUT:
<img width="825" height="579" alt="Screenshot 2025-11-13 134833" src="https://github.com/user-attachments/assets/a1dbf5c1-96ba-4509-a685-66e1fea6a063" />

# RESULT:
he commands are successfully compiled in RetHat Lab(Terminal)
