# Activity itinerary Component

### Component Data

```javascript

{
    "id": "55610",
    "name": "Deluxe Las Vegas Helicopter Flight",
    "operator": "Universal Tours",
    "duration": "3 hours 30 minutes",
    "description": "See the bright lights of the Las vegas strip and the surrounding region in 15-minute helicopter flight",
    "fare": {
        "amount": 120.86,
        "currency": "USD"
    },
    "discount": {
        "amount": 30.0,
        "currency": "USD"
    },
    "image": "http://d3mj096p5q0e20.cloudfront.net/ti/HBD/55610/043509a_hb_a_001.jpg"
}

```

### Resources

```javascript
{
    "currencySymbols": [
        {
            "code": "USD",
            "symbol": "$"
        },
        {
            "code": "INR",
            "symbol": "₹"
        }
    ],
    "defaultImage": "",
    "fare": {
        "prefix": "starts from",
        "suffix": "per traveler"
    },
    "operatorPrefix": "by",
    "buttonText": "CHECK OPTIONS"
}

```

### Settings

```javascript

{
    "cardView":false,
    "showButton":true
}


```

### Events (all events return item id as data)

```javascript

image tap\click - t-activity-item-img-tap
title tap\click - t-activity-item-title-tap
button tap\click - t-activity-item-options-tap

```

## Important Information

- 


## Test Cases

- 

## Steps to Start
- Set Github repository at your end for this project, we will merge them later
- You can use Google/Vaadin's elements (like calender element and textboxes etc.)
- You can use some Tavisca's elements like auto-suggest if required from https://github.com/atomelements/t-autosuggest but all the features and properties mentioned in scope should be added. (Fork the existing element and create V2)

## Performance standard
- Any component if opened via [web page tester](https://www.webpagetest.org/), it should load under 500ms (milli seconds).

## Documents
- Visual designs for Activity item list view - https://projects.invisionapp.com/share/6E9PJ7R4Q#/screens/224624778 and card view - 
- API access : Url - http://demo.travelnxt.com/dev
- Tavisca Elements - https://github.com/atomelements and https://github.com/travelnxtelements
- Vaadin elements - https://vaadin.com/docs/-/part/elements/elements-getting-started.html
- Google - https://elements.polymer-project.org/browse?package=google-web-components
- Tavisca Web component style Guide - https://drive.google.com/open?id=0B7BT_2nBFNYVR2tscE9pRnVJYmc

