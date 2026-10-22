# vocabs-common-production
Deyploment for the production version of vocabs commons (on sshopencloud.eu)

Remarks:
* The Dockerfile.ubuntu of Skosmos is overwritten with the Dockerfile.ubuntu.adapted file of the root folder
* Change in main and merge into `prod` to start from there the action to deploy the cahnges
* When cloning add `--recurse-submodules` to have the latest version of the skosmos-submodule available
* To update the submodule of Skosmos, run `git submodule update --remote --merge`

Working with environment secrets:
* the file to copy is defined in the CONFIG_FILE_NAME-secret

