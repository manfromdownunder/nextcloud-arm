# nextcloud-arm
Nextcloud using MariaDB

Mount USB Hardrive
sudo mkdir /mnt/data
sudo mount /dev/sda1 /mnt/data

Create Nextcloud data folder and set permissions
sudo mkdir /mnt/data/nextcloud
sudo chown -R www-data:www-data /mnt/data
sudo chown -R www-data:www-data /mnt/data/nextcloud
