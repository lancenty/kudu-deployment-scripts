# Kudu Deployment Scripts

A library of deployment scripts for project Kudu / Azure web apps.  You can read more about Kudu on their [wiki](https://github.com/projectkudu/kudu/wiki), and more on customizing your deployments [here](https://github.com/projectkudu/kudu/wiki/Customizing-deployments).

## Usage

Create a `.deployment` file in the root of your project with the following content:

```
[config]
command = deploy.cmd
```

Alternatively, [download the sample](scripts/.deployment) from this repro.

Next, download the deployment script for your runtime or application from the list below, save it to the root of your project and rename it to `deploy.cmd`.

## Application Deployment Scripts

- [Hubot](scripts/deploy-hubot.cmd)

## Runtime Deployment Scripts

- [Node.js](deploy-node.cmd) 

## Contributions

Contributions are welcome.  Please add one script per pull request.  Scripts should be added to the `scripts` folder and added to the list above.
