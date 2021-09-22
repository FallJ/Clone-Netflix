```
mutation movies_romance {

titanic: insertmovies_by_genre(
    value: { 
      genre:"Romance", 
      year:1997,
      title:"Titanic",
      synopsis:"A ship of dreams becomes a ship of nightmare and horror after craping along an iceburg.",
      duration:194,
      thumbnail:"https://imgur.com/pMCrpy9"}) {
    value{title}
    }

lovemercy1: insertmovies_by_genre(
    value: { 
      genre:"Romance", 
      year:2014,
      title:"Love and Mercy",
      synopsis:"In the 60s, Beach Boys leader Brian Wilson struggles with emerging psychosis as he attempts to craft his avant-garde pop masterpiece. In the 80s, he is a broken, confused man under the 24-hour watch of shady therapist Dr. Eugene Landy.",
      duration:121,
      thumbnail:"https://i.imgur.com/tZtTkBf.mp4"}) {
    value{title}
  }

perfectmatch1: insertmovies_by_genre(
    value: { 
      genre:"Romance", 
      year:2016,
      title:"The perfect match",
      synopsis:"A playboy named Charlie, convinced that all his relationships are dead, meets the beautiful and mysterious Eva. Agreeing to a casual affair, Charlie then wants a bit more from their relationship.",
      duration:96,
      thumbnail:"https://i.imgur.com/XqSrnvi.mp4"}) {
    value{title}
  }
  
}
```
