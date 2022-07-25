IMPORTANT!!



The Application needs preconfiguration to work.

The Application requires a Linux environment to run

It has downstream dependencies such as distrobox, podman and fastfetch

using distrobox the user must create some guests via a distrobox using the following commands

distrobox create --image docker.io/library/ubuntu:latest --pull --yes --name ubuntu

distrobox create --image docker.io/debian:latest --pull --yes --name debian

distrobox create fedora --pull --yes --name fedora

These must me pre installed on the guest system to run

The contents of the folder urs/share/applications must be extracted into the  
/urs/share/applications on the users host machine
