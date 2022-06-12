![Onify Blueprints](https://files.readme.io/8ba3f14-onify-blueprints-logo.png)

[![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
![Test suite](https://github.com/onify/blueprint-freshservice-create-update-ticket/workflows/Test%20suite/badge.svg)

# Onify Blueprint: Create and update ticket in Freshservice

[Freshservice](https://freshservice.com/) is a modern ITSM tool from [Freshworks](https://www.freshworks.com/). In this Blueprint we show how to first create a new ticket and then update the same ticket and last but not least we add a note to the ticket. Everyting is done through [Freshservice REST API](https://api.freshservice.com/).

![Onify Blueprint: Create and update ticket in Freshservice](flow.png "Flow")

## Requirements

* Onify Hub  
* Camunda Modeler
* Freshservice 

## Included

* 1 x Flows

## Setup

### Deploy

1. Open flow/bpmn in Camunda Modeler
2. Change settings/vars the the `Define Freshservice settings` task
3. Click `Deploy current diagram` and follow the steps

### Run 

To test and run the flow, click `Start Current Diagram`

## Support

* Community/forum: https://support.onify.co/discuss
* Documentation: https://support.onify.co/docs
* Support and SLA: https://support.onify.co/docs/get-support

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Thanks

Thanks [Academic Work](https://github.com/orgs/academicwork) and [Mattias Frykstrand](https://github.com/Mfryk85) for assisting us with a Freshservice sandbox environment!
