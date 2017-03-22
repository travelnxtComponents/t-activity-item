# Activity itinerary Components

### Component data

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
