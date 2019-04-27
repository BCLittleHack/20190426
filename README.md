# 20190426
Blair County Little Hack #2!

Here's a link that has how to use a private container with VIC https://cormachogan.com/2017/05/17/image-management-vic-harbor/
And here's the commands to deploy to a VIC host

Deploy the Application to a VCH
The steps in this section make the following assumptions:

You have deployed a virtual container host (VCH).
You deployed the VCH with a volume store named default by specifying --volume-store datastore_name/path:default.
You deployed the VCH with the --no-tls option, to disable TLS authentication between the Docker client and the VCH.
You are using Docker Compose 1.8.1.
In the procedure below, run the commands from the example-voting-app folder that contains the modified docker-compose.yml file.

Run the docker-compose command:

**docker-compose -H vch_address:2375 up -d**
