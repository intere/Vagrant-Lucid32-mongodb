#Vagrant-Lucid32-mongodb
##Initial Setup
    $ #Install Vagrant
    $ gem install vagrant
    $ # Install librarian-puppet
    $ gem install librarian-puppet
    $ # Clone the Repo
    $ git clone https://github.com/intere/Vagrant-Lucid32-mongodb.git
    $ # Install the puppet modules
    $ cd manifests ; librarian-puppet install

##Bring up the VM
    $ # Now bring up the VM
    $ cd <Vagrant-Lucid32-mongodb folder> ; vagrant up
    $ # Note: This will take some time the first time as it has to pull the mongodb tarball and unpack it

## SSH to the VM
    $ vagrant ssh
    $ # Now you'll see a shell prompt on the Mongo VM
