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
  "images": [{
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
    "description": "String"
  }
}


