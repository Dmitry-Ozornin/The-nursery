# Task 1
mkdir animals
cd animals
cat > home_animal
cat pack_animal
cat home_animal pack_animal > all_animal
mv all_animal  mans_friends

# Task 2

mkdir animals2
sudo mv mans_friends animals2/

# Task 3

wget https://dev.mysql.com/get/mysql-apt-config_0.8.24-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.24-1_all.deb
sudo apt-get update
udo apt-get install mysql-server

# Task 4
wget https://dev.mysql.com/get/Downloads/Connector-J/mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
sudo dpkg -i mysql-connector-j_8.0.32-1ubuntu22.04_all.deb
sudo dpkg -r mysql-connector-j
sudo apt-get autoremove