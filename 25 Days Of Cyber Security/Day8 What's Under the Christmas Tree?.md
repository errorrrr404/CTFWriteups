# Day8

## What's Under the Christmas Tree?

Deploy the machine and go through the dossier. Then lets head straight over to the questions. 

The first question can be found using: Google!

Now, let's run the ***nmap scan***:

`nmap -sC -sV 10.10.176.108`

And it'll show you the ports as well as the answer to the next question that is asking for the type of linux distribution.

Now, let’s run a nmap script to determine the http-title: 
`nmap --script http-title -p 80 10.10.176.108`

![45](https://user-images.githubusercontent.com/83836972/122218858-7c5c3500-cecc-11eb-8a88-a94b63da9a8c.PNG)

And here' you'll get the answer for what this website might be used for!!



