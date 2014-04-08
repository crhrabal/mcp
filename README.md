mcp
===

Master Control Program:  A program to control Cyber Security Gymnasiums.  

Setting up the environment:

* In the EC2 Managment Console Click Launch Instance
* Then click community AMI
* Search for 14.04 and pick the 64 bit AMI.
* Connect to instance, sudo apt-get update && sudo apt-get dist-upgrade -y
* sudo apt-get install ruby-rails-4.0 sqlite3 libsqlite3-dev nodejs git
* $ git config --global user.name "John Doe"
* $ git config --global user.email johndoe@example.com
* $ git config --global core.editor emacs
* Visit github and fork https://github.com/dkrovich/mcp
* mkdir rails_projects
* cd rails_projects
* git clone https://github.com/username/mcp.git
* cd mcp/mcprails
* bundle install
* rails server

If all goes as expected WEBRick will fire up and your rails app will be running on port 3000.
Make sure your AWS security policies allow it and connect to http://your.ip.address.here:3000

