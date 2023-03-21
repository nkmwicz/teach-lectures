# teach-lectures
This is where I store my slides for my react-presentations. I also store the  The react presentation takes a JSON object that stores an array of images and slide object that auto populate the react-presentation.

# Intro Format
{
  "number": 0.1,
  "slide": true,
  "intro": true,
  "title": "string",
  "subTitle": "String",
  "byLine": "String",
  "url": "String"
},

# Centered Format with Text
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

# Centered Format with Images
{
  "number": 2.1,
  "slide": true,
  "centered": true,
  "title": "Background Information",
  "subTitle": "A Clash of Civilizations?",
  "images": [{
      "image": "https://upload.wikimedia.org/wikipedia/commons/c/cb/BattleOfInab.jpg",
      "description": "Nur-ad-Din's Victory at the Battle of Inab, 1149 during the Second Crusade.",
      "opacity": 1
    },
    {
      "image": "https://upload.wikimedia.org/wikipedia/commons/e/e2/Le_si%C3%A8ge_de_Constantinople_%281453%29_by_Jean_Le_Tavernier_after_1455.jpg",
      "description": "Ottoman Siege of Constantinople (1453) by Jean Le Tavernier (1455)",
      "opacity": 0.5
    },
    {
      "image": "https://upload.wikimedia.org/wikipedia/commons/6/65/The_Battle_of_Lepanto_by_Paolo_Veronese.jpeg",
      "description": "The Battle of Lepanto (1571), by Paolo Veronese",
      "opacity": 0.5
    }
  ]
}
# Split Format
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


