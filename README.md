# Ursus Park sample app for Trailhead project [Build Flexible Apps with Lightning Web Components](https://trailhead.salesforce.com/content/learn/projects/lwc-build-flexible-apps)

Note: we are not accepting contributions on this app.

# Create a Hello World Lightning Web Component

Authorize your Trailhead Playground with the Salesforce CLI: `sfdx force:auth:web:login -s -a bear-tracking`

Deploy the app code to the org: `sfdx force:source:deploy -p force-app/main/default`

Assign the Ursus Park User permission set to the current user: `sfdx force:user:permset:assign -n Ursus_Park_User`

Import the sample data: `sfdx force:data:tree:import -p data/plan.json`

Open the org in a browser: `sfdx force:org:open`



