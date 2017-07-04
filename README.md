### Linux Server Configuration

## IP Address:
	13.58.192.4

## SSH Port:
	2200
	
## Web App URL:
	http://13.58.192.4/catalog

## Software Installed
	
	Flask
	Postgresql
	Psycopg2
	sqlalchemy
	oauth2client
	requests

	Item_database_setup.py
		Modified the database engine to work with postgresql

	__init__.py
		Modified code to work with postgresql. Added the full path
		to client_secrets.json and fb_client_secrets.json.  
	
	client_secrets.json
		Placed the url in the file (at the end of the text string)
		so that Google OAuth will point to the right place and 
		complete the login process

	fb_client_secrets.json
		No changes necessary

	


## 3rd Party Resources
	Google OAuth Client
		Added the site url to OAuth client

	Facebook for Developers
		Added the site url to url redirects on FB site

	Amazon Web Services
	