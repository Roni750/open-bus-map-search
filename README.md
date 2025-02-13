# Open bus ranking app

## Welcome!
This is the official repository of the open bus (תחב"צ פתוחה / דאטאבוס) project - also known as "ShameBus".
[link to the project](https://open-bus-map-search.hasadna.org.il/dashboard)

Please feel free to submit pull requests and contribute to the project (see the "contribution" section).

## View video (Hebrew language):
[![video (hebrew) about the project](https://img.youtube.com/vi/6H6jkJCVhgk/0.jpg)](https://www.youtube.com/watch?v=6H6jkJCVhgk)

# Easter eggs
We've hidden a couple of fun surprises in our web app, just for you. Discovering them is as easy as typing a few magic words on your keyboard.

## How to Find the Easter Eggs
1. Open our [web app](https://open-bus-map-search.hasadna.org.il/dashboard)
2. **Unleash the Magic Words:**
   To reveal the hidden gems, use your keyboard to type the following commands:

   - **Type "storybook":**
     Watch the magic unfold as you type "storybook" on your keyboard. You might just stumble upon our Storybook, a treasure trove of UI components showcasing the beauty and functionality of our app.
   - **Type "english":**
     Feel like switching up the language? Type "english" and see the language toggle in action. Our app is multilingual, and you can experience it by triggering this secret command.
   - **Type "geek":**
     To get some experimental charts with some additional data and aggregation


## deployments

[![Netlify Status](https://api.netlify.com/api/v1/badges/d3ef62c2-b5bb-48ac-8299-71e5bd22b211/deploy-status)](https://app.netlify.com/sites/open-bus/deploys)

This app is created by the volunteers of [Public Knowledge Workshop](https://www.hasadna.org.il/)

## Contribution:

### Running the project:

- fork the repo
- clone the repo
- `yarn install`
- `yarn start`

### testing the project:
| command                                                           | description                                                                         |
| ----------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| `yarn test:unit`                                                       | Run the unit tests using `watch` option (good for development). |
| `yarn test:unit:ci`                                                       | Run the unit tests (good for ci). |
| `yarn test:e2e`                                                       | Run the e2e (playwright) tests (good for ci). |
| `yarn test:e2e:ui`                                                       | Run the e2e (playwright) tests with user interface. |
| `yarn test`                                                       | Run all the kind of tests. |
- additional helpful flags - https://playwright.dev/docs/test-cli

### useful resources:
* [the design file](https://www.figma.com/file/Plw8Uuu6U96CcX5tJyRMoW/Public-Transportation-visual-informaiton?type=design&node-id=0-1&mode=design&t=Dh8lI3EJ37unxvoe-0)
* [data model schema](https://github.com/hasadna/open-bus-stride-db/blob/main/DATA_MODEL.md)
* [API documentation and examples (swagger)](https://open-bus-stride-api.hasadna.org.il/docs)
* [the deployed website](https://open-bus-map-search.hasadna.org.il/dashboard)

### submitting pull requests
Thanks for your willingness to invest time and help us improve!
1. If you're new to GitHub, here is a [tutorial describing Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request). if you're familiarized with Merge Requests - it's the same concept.
2. Please make sure that the project works on your computer
3. Please tag one of the maintainers as reviewers
we're here to help! feel free to join our [Slack channel](https://join.slack.com/t/hasadna/shared_invite/zt-21qipktl1-7yF4FYJVxAqXl0wE4DlMKQ) 

## Related Repositories 
- the API client
- the data API

### API client
The client is a JS library that provides methods and data models. for example:  
https://github.com/hasadna/open-bus-map-search/blob/main/src/model/busStop.ts#L4   
[link to repo](https://github.com/iliakap/open-bus-stride-client).


### data API
The API is backend code that provides us with data and aggregations from the DB
You can see it's endpoints here:   
https://open-bus-stride-api.hasadna.org.il/docs     
[link to repo](https://github.com/hasadna/open-bus-stride-api).