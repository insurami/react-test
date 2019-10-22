# react-test
React test using the Companies House API

## resources
Signup for a Companies House developer account [here](https://developer.companieshouse.gov.uk). To be able to use the Companies House API locally you need to add an entry in your hosts file:

```
127.0.0.1       application.com
```

Then you need to register an app [here](https://developer.companieshouse.gov.uk/developer/applications/register). Select REST API and a generic application name and add "application.com" to your Authorised JavaScript domains.


## assignment

Create a fresh React project we recommend using [create-react-app](https://github.com/facebook/create-react-app). Setup state management using either Mobx (we use it) or Redux. 

Once the initial setup is done you need to complete a few user stories:

+ The user should be able to paste in their companies house API key at the top of the react application UI.

+ Given that a user has entered their API key the user should be able to search for a company using a text input field using the companies house API. Then the user should be able to select a company.

+ Given that the user has selected a company they should be able to see the companies details displayed below (companies name, company number,description, address). They should also be able too see a list of the companies directors.

## bonus

+ Given that a user sees a list of directors the user should be able to filter the list via an input field by name.

## technical requirements
+ React
+ Mobx or Redux
+ Testing (you can choose)
