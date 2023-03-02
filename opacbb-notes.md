# General Notes

This week I watched both videos and read the script before starting the assignment.
This was more time comsuming but it helped me understand the context better for when I began the assignment.

I also tried taking notes on the steps while watching the video.
Then when I went to execute the assignment, I followed my notes.
	- While this wasn't as helpful as I though it would be with the actual assignment, it definitely helped me with my note taking skills.
	- It is important to take notes, but knowing which parts are most important to note is even more helpful.

I have finished the assignment for the week but am still confused on one portion.
	- I believe this has caused an issue in my OPAC eventhough it is generally working as it should.
	- I have consulted Element and I will update notes once I hear back.

Addressed in the video and notes, use the `sudo` command in front of `nano` when in the html directory. 
	- See *Managing Software* section in Syslib text to explain `sudo`

# Steps to remember

1. Make sure to start in html directory
```
cd /var/www/html
```

I should have made a note of this last week because I had to go digging in last weeks script.

2. To find the original opac, use
```
sudo nano opac.php
```

**For Steps 3 through 5, make sure to replace IP address with my own**
```
34.135.201.171
```

3. Create a new php code to make the opac searchable
```
sudo nano opacbb.php
```
Use html code in this weeks script.

4. Create html file using same code in last step
```
sudo nano opacbb.html
```
**note: the php file name has to reflect html script**

5. Enter the given php script in the following file
```
sudo nano search.php
``` 

6. To add books to the database, go back to home directory and enter the following:
```
mysql -u opacuser -p
```
Run the following
```
	- show databases;
	- use opacdb;
```
Use script in class notes for format.

# To see my opac

Visit
```
http://34.135.201.171/opacbb.html
```
