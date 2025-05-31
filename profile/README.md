# Let's Be Decent

Decent Apps are fully local web apps. where everything, including an LLM, runs in the user's browser. This realizes benefits in privacy, security, performance, and cost. For more information about Decent Apps, please visit [decentapps.net](https://decentapps.net).

For community discussion, we welcome you to the [Decent Apps Discord server](https://discord.gg/kkp3x4X2Vb)!

# Repository Guide

## Top-Level Repos

* [create-decent-app](https://github.com/DecentAppsNet/create-decent-app) - a project source generator that quickly creates a web app with local LLM functionality, following Decent sensibilities

## Supporting Repos
* [decent-portal](https://github.com/DecentAppsNet/decent-portal) - library containing functionality specific to the Decent Portal, including GitHub workflows for deployment and the Decent Bar. Used by `decentapp-template`
* [decentapp-template](https://github.com/DecentAppsNet/decentapp-template) - the boilerplate project source used by `create-decent-app`
* [decent-actions](https://github.com/DecentAppsNet/decent-actions) - a monorepo that builds GitHub actions supporting Github workflows for deployment. These deploy to individual repos:
  * [deploy](https://github.com/DecentAppsNet/deploy) - serves the DecentAppsNet/deploy GitHub action used by the deploy workflow in `decent-portal`
  * [promote](https://github.com/DecentAppsNet/promote) - serves the DecentAppsNet/promote GitHub action used by the promote workflow in `decent-portal`
  * [rollback](https://github.com/DecentAppsNet/rollback) - serves the DecentAppsNet/rollback GitHub action used by the rollback workflow in `decent-portal`
* [decent-info](https://github.com/DecentAppsNet/decent-info) - static website content deployed to https://decentapps.net. Made public in the spirit of transparency and accountability.

## Support / Filing Issues

Just use the [create-decent-app issue tracker](https://github.com/DecentAppsNet/create-decent-app/issues) rather than an issue tracker in a supporting repo. That's going to be the easiest thing for now.
