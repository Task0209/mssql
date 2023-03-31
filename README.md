# mssql
MSSQL deployment in Kubernetes cluster
Please ensure to create the mount folder /var/opt/mssql and make the permission as below
chown mssql -R /var/opt/mssql
chgrp mssql -R /var/opt/mssql
chmod 755 -R /var/opt/mssql
