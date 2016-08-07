# jekyll-vagrant

## Setup
1. Make sure Vagrant and Virtualbox are installed.
1. Clone this repository
1. Open command prompt to location of the Vagrantfile and run ```vagrant up --provider=virtualbox```
1. Jekyll and all it's dependencies are installed!

## Existing Jekyll Projects
1. Copy the projects folder to the folder that contains the vagrantfile.  
1. Open a command prompt to location of the Vagrantfile and run ```vagrant ssh```
1. Once on the VM prompt ```cd [sitename]```
1. Start the jekyll server ```serve``` or ```jekyll serve --host 0.0.0.0 --force_polling``` (force polling is required with vagrant because of share)

## New Jekyll Projects
1.  Open a command prompt to location of the Vagrantfile and run ```vagrant ssh```
1.  Create new site with ```jekyll new [sitename]```
1.  Start the jekyll server ```serve``` or ```jekyll serve --host 0.0.0.0 --force_polling``` (force polling is required with vagrant because of share)

Blog post from original creator: http://www.jamessturtevant.com/posts/running-jekyll-in-windows/
