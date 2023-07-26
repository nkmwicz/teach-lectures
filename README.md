# teach-lectures
This is where I store my slides for my react-presentations. The react presentation takes a JSON object that stores an array of images and a slides object that auto-populates the React-Presentation.

## Intro Format
{
  "number": 0.1,
  "slide": true,
  "intro": true,
  "title": "string",
  "subTitle": "String",
  "byLine": "String",
  "url": "String"
},

## Centered Format with Text
{
  "number": 1.1,
  "slide": true,
  "centered": true,
  "title": "String",
  "text": [{
      "text": "String",
      "color": "String",
      "children": [{
          "text": "String",
          "color": "String"
        },
        {
          "text": "String",
          "color": "String"
        }
      ]
    }
  ]
}

## Centered Format with Images
{
  "number": 2.1,
  "slide": true,
  "centered": true,
  "title": "string",
  "subTitle": "string",
  "images": [{l
      "image": "string",
      "description": "string",
      "opacity": Number(0-1)
    },
    {
      "image": "string",
      "description": "string",
      "opacity": 0.5
    },
    {
      "image": "string",
      "description": "string",
      "opacity": 0.5
    }
  ]
}
## Split Format
{
  "number": 3.1,
  "slide": true,
  "split": true,
  "title": "Background Information",
  "subTitle": "Cross-Confessional Collaboration",
  "text": [{
      "text": "String",
      "color": "String"
    },
    {
      "text": "String",
      "color": "String"
    },
    {
      "text": "String",
      "color": "String"
    }],
  "image": {
    "image": "String",
    "description": "String",
    "alt": "String"
  }
}

## Split Text Format
{
  "number": 3.1,
  "slide": true,
  "splitText": true,
  "title": "Course Basics",
  "text": [{
      "text": "Course Overview",
      "color": "lightgrey"
    },
    {
      "text": "Learning Objectives",
      "color": "darkslategrey"
    },
    {
      "text": "Required Reading: Everything on Zotero.",
      "color": "darkslategrey"
    }
  ],
  "rightText": "From the Renaissance to the present, Europe transformed from a minor region to a global power. This course will explore the process of that transformation. It will emphasize cultural changes in Europe as well as the role of interactions around the globe—including the exploitation of indigenous populations—in that transformation."
},

## SplitSlideChild format
This format takes in a _year_ that determines which map to use, the _mapLabel_, to set below the map, the _mapCenter_, and the _zoom_. _stateColors_ indicates which colors to shade the boundaries based on the name of the feature. _popup_ and _popupCoords_ are content and the coordinates of the popup that are passed in and the 
  {
    "number": 8.4,
    "split": true,
    "map": true, 
		"title": "Immediate Causes:",
    "subTitle": "Crisis in the Balkans in early 20th century",
    "text": [
      {
        "text": "Balkan countries revolting against Ottoman Empire, especially Bulgaria (1908)",
        "color": "darkslategrey"
      },
      {
        "text": "Austria-Hungary annexes Bosnia and Herzegovina (1908)",
        "color": "darkslategrey"
      },
      {
        "text": "First Balkan War: Balkan States Vs. Ottoman (1912-1913)",
        "color": "darkslategrey"  
      },
      {
        "text": "Reaction of Great powers",
        "color": "lightgrey"
      }
    ],
    "year": 1914,
    "mapLabel": "The Balkans  After the First Balkan War",
    "mapCenter": [52.0, 10.0],
    "zoom": 5,
    "stateColors": {
      "Ottoman Empire": "yellow",
      "German Empire": "red",
      "Russian Empire": "green",
      "Austro-Hungarian Empire": "darkorange",
      "France": "blue",
      "United Kingdom of Great Britain and Ireland": "purple"
    },
    "popup": "Austro-Hungarian Empire",
    "popupCoords": [48.0, 11.0]
  },
