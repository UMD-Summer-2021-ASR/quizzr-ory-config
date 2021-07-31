# Quizzr.io Access Control Configuration
This repository contains the configurations necessary to set up [ORY Oathkeeper](https://www.ory.sh/oathkeeper/docs/) and [ORY Keto](https://www.ory.sh/keto/docs/v0.5/) with the Quizzr.io network. Refer to their individual installation instructions for more information.\
Required ORY Oathkeeper version: `0.38.14-beta.1`\
Required ORY Keto version: `0.5.7`

If you plan on setting up the components in a Docker network (i.e., locally), be sure to supply the appropriate name of each container to the `--name` argument in the associated `run` command. Otherwise, change all instances of each component's URL to point to the actual URL.