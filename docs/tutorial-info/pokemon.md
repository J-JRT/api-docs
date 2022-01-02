---
sidebar_position: 2
---

# Info Pokemon

```jsx title="API Endpoint:"
    http://mzkapi.me/pokemon/search?=`keyword`
```
## Return data

```jsx title="http://mzkapi.me/pokemon/search?name=Pikachu"
{
    "pokemon": {
        "id": 25,
        "name": "Pikachu",
        "type": [
            "Electric"
        ],
        "base": {
            "HP": 35,
            "Attack": 55,
            "Defense": 40,
            "Sp. Attack": 50,
            "Sp. Defense": 50,
            "Speed": 90
        },
        "species": "Mouse Pokémon",
        "description": "Trong khi ngủ, nó tạo ra điện trong các túi ở má. Nếu ngủ không đủ giấc, nó sẽ chỉ có thể sử dụng nguồn điện yếu.",
        "evolution": {
            "prev": [
                "172",
                "high Friendship"
            ],
            "next": [
                [
                    "26",
                    "use Thunder Stone"
                ]
            ]
        },
        "profile": {
            "height": "0.4 m",
            "weight": "6 kg",
            "egg": [
                "Field",
                "Fairy"
            ],
            "ability": [
                [
                    "Static",
                    "false"
                ],
                [
                    "Lightning Rod",
                    "true"
                ]
            ],
            "gender": "50:50"
        },
        "image": "http://raw.githubusercontent.com/Purukitto/pokemon-data.json/master/images/pokedex/hires/025.png"
    },
    "author": "D-Jukie"
}
```