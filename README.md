mysql;
CREATE DATABASE myHomeApp;

CREATE TABLE mySmartHomeDevices(id INT(10) AUTO_INCREMENT, deviceName VARCHAR(32) NOT NULL, deviceType VARCHAR(32) NOT NULL,temperture INT(10), volume INT(10), isOn BOOLEAN, isOpen BOOLEAN, PRIMARY KEY(id));