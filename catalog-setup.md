# **Things to remember: Catalog Module**

## List of sites to remember so far

1. [Basic OPAC](https://34.135.201.171/opac.php)
1. [Basic Search OPAC](https://34.135.201.171/opacbb.html)
1. [Catalog Module](https://34.135.201.171/cataloging/)

## **Remember to check for updates each time:**

```
sudo apt update
```
```
sudo apt -y upgrade
```

## Notes to jog memory on process:

1. HTML page
	- Provides the form for entering data
1. PHP script
	- Used to communicate and add the data from the form to the MySQL database

**Apache2 provides the mechanism to add site authorization**
	- Remember this directory 
	```
	cd /etc/apache2
	```
	- **FYI** browser will remember username and password until it is restarted

## Point of confusion this week:

In the lecture video, the following script is written as follows, instead of just changing `none` to `all` as described in the text:

	```
	#AllowOverride None
	AllowOverride All
	```
It seemed to work the same.  
