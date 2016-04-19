# What this does?
This creates go lang structs for a mysql table, along with its json tags.

#How it works?
Run following in the command line (at the location of this file)
*go run struct-generator.go -u=root -p=12345 -d=test_db -t=contacts*

This command takes 4 paramters:
	a. u ==> username 
	b. p ==> password 
	a. d ==> Db name 
	a. t ==> table name 