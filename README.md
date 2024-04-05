# Password-Policy
Attempt at porting Password Policy from D7 to Backdrop using Coder Upgrade module. Converison appeared to work until it was installed and produced: SQLSTATE[42S02]: Base table or view not found: 1146 Table 'role' doesn't exist.  Role definitions now are stored as a JSON configuration file and not within DB.
