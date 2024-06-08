# PostgreSQL-Arch-Linux

# Install PostgreSQL  
You likely have already installed PostgreSQL using pacman, but if not, you can do so with the following command:  
```
sudo pacman -S postgresql
```
# Initialize the Database Cluster
Before you can start using PostgreSQL, you need to initialize the database cluster. This sets up the necessary directory structure and configurations.  
```
sudo -iu postgres
initdb -D /var/lib/postgres/data
exit
```
# Start the PostgreSQL Service
Start the PostgreSQL service to ensure that the server is running.
```
sudo systemctl start postgresql
```
