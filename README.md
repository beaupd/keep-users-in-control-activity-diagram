> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Titel
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## User Story
<!-- Schrijf hier de User Story waar de Activity Diagram over gaat-->
Als respondent
Wil ik een formulier invullen en beide visualisaties kunnen bekijken
Zodat ik kan reflecteren op mijn handelen

## Activity Diagram
<!-- Toon de activity Diagram -->
![Wireflow](https://github.com/beaupd/keep-users-in-control-activity-diagram/blob/main/assets/Wireflow.jpg)
![Control diagram](https://github.com/beaupd/keep-users-in-control-activity-diagram/blob/main/assets/ControlDiagram.jpg)

## Uitleg pseudo-code 
<!-- Leg de pseudo-code in de control fow uit -->
```javascript
function getParameters(){
  get HTTP request -> get parameters
  dissect parameters with key(decrypt) in backend
  return data object
}

function fetch...WithData(){
  with the decrypted data object
  fetch data for view
} 

function start/stop skeleton loader(){
  start or stop skeleton
  loader to give a sense of control
}

function view...render(){
  render a view with fetched data
}
```

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
