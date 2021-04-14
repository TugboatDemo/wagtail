# Live Previews for Wagtail CMS

This starter config is used to get up and running on [Tugboat CI](https://tugboat.ci/).

Place `.tugboat/config.yml` in the root of your Git repository and create an account on Tugboat. 

Please note that this config creates a Wagtail site from scratch. You'll want to deploy Tugboat into a working site, so additional steps will be needed to import your database into the build. One way you can do this by importing the Tugboat Repository’s [SSH key](https://docs.tugboat.qa/setting-up-tugboat/select-repo-settings/#set-up-remote-ssh-access) to the server hosting your site's data and then using `scp`.