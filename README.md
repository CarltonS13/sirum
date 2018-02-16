# sirum
# create and cd into the folder in which you want to install
npm install dscsa/development

# add development, server, client, pouch, and csv
“add” is a bit confusing I think it will make more sense if you said “clone”
unless thats not what you want to do?

# as repositories to your git client and link to github
I didn’t really understand what you meant by "git client" 
so I created a new repository in the folder with the command line then uploaded it to github
https://github.com/CarltonS13/sirum
However I had to run :
$ git submodule init
$ git submodule update
To register development, server, client, pouch, and csv as modules before I committed
Now I can update sub modules by calling “git pull” in the submodule folder
also for some reason I had to force the initial commit 

# build the client with watch and run server
This was a bit confusing 
I eventually realized that watching and building was automatic and all I needed to do was run 
# will ask for couchdb credentials on first run
# should work from localhost and localhost:9000
sudo npm start
