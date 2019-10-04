# Magic_Circuit

## Setup

Right now, there's not much. Just a basic nginx web server on a Vagrant VM.

1. `vagrant up`

Once you have the VM running, connect to `localhost:8080` and you should see the site there.

## Working

1. `vagrant ssh`

This is not necessary for development because the root folder of this project and the `/Vagrant` folder in the VM are the same. All changes you make to this root project will propagate to the `/Vagrant` folder.

This is really only necessary if you want to make updates to your local VM. However, remember to include it in the `Vagrantfile` or `bootstrap.sh` to include provisioning changes to source control.
