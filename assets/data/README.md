# App Data

This app generally isn't meant to be updated very often, so a database seemed like overkill. Instead, create and add content to the following data files using the templates below, and add them to this directory before building the app.

###skills.json
```
{ 
    "Skill Category 1": [
        {
            "tech": "Skill 1", 
            "level": 9.9,
            "note": "I am some text that could be a tooltip one day"
        },
        {
            "tech": "Skill 2", 
            "level": 8,
            "note": "I am some text that could be a tooltip one day"
        }
    ],
    "Skill Category 2": [
        {
            "tech": "Skill a",
            "level": 10,
            "note": "I am some text that could be a tooltip one day"
        }
        ...
    ],
    ...

}
```
note: level should contain a float between 1 and 10

###package.json
```
{
    "projects":[
        {
            "title": "Project 1",
            "img": "assets/images/portfolio/project1.png",
            "description":"Some cool description here. Can include html tags."
        },
        {
            "title":
        ...
    ]
}
```
add the portfolio images (which need to have a 3wX2h aspect ratio) to assets/images/portfolio