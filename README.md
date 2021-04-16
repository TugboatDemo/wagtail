# Live Previews for Wagtail CMS

This starter config is used to get [Wagtail](https://wagtail.io/) up and running on [Tugboat CI](https://tugboat.ci/).

Place `.tugboat/config.yml` in the root of your Git repository and [create an account](https://dashboard.tugboat.qa/) on Tugboat. 

Note that this config builds a Wagtail site from scratch. You'll likely want to deploy Tugboat into an existing site, so additional steps will be needed to import your database and file assets into the build. One way you can do this by importing the Tugboat Repository’s [SSH key](https://docs.tugboat.qa/setting-up-tugboat/select-repo-settings/#set-up-remote-ssh-access) to the server hosting your site's data and then using `scp` for import. Here's an [example](https://docs.tugboat.qa/starter-configs/code-snippets/import-mysql-database/) with mysql. 
