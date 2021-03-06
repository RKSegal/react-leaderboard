# react-leaderboard

## Stack
- React
- Lodash
- Node.js (8.12.0LTS)
- Gulp
- react-dom
- react-compound-timer

## Task - Recreate the Leaderboard component. 

- The top 3 people based on rank should be displayed to the left. 
- The rest of the people should be displayed in the right hand side. 
- The right hand side should paginate on a timer of every 30 seconds. Once it has gone through all the pages it should go back to the original. If there is only 1 page it shouldn't display the page bars at the bottom and it should not refresh every 30 seconds. 
- Bonus for making it animate to another page. 
- Please feel free to use React and whatever other frameworks you would like. 

```json 
data = [
  {"id":"ba4cd453-668f-4ec3-8146-05a0cf08883a","attainment":2.10859,"avatarURL":"https://a.wattpad.com/useravatar/Existentialism6.256.371671.jpg","name":"Max Jensen","userID":"c1d67fb8-ff8d-4839-9f44-da172d32bd96","rank":1},
  {"id":"8058b3d0-eeab-4f92-9e7b-db8be7a596f9","attainment":0,"avatarURL":"https://secure.gravatar.com/avatar/7ba0d855b088f8c45c549e46870c0a1e?s=96&d=mm&r=g","name":"Sarah Smith","userID":"34529a9c-611b-4caf-82d7-883b2cc2efda","rank":2},
  {"id":"e129aeed-0c37-4d7b-9be3-9d982686b88b","attainment":0.11418,"avatarURL":"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPpeGGpJvxVeoWGMNH30lnxR2TnxxUVBS7Z9hWxlsWUjJc2BEz","name":"Jane Fitzpatrick","userID":"34238232-23e9-46b6-abb4-56ae3a8d6cc0","rank":3},
  {"id":"759ad951-a4f5-4121-90b2-a372ebbb89d4","attainment":0.332657,"avatarURL":"https://pbs.twimg.com/profile_images/2939127611/134c960f84cfd95f5b1fa7ceb71a22ce.jpeg","name":"Will Westin","userID":"a1c4678e-a627-42b8-ab71-f9645d54239b","rank":4},
  {"id":"7d2970fa-5692-492c-a682-4e2360a3bb8a","attainment":0.492308,"avatarURL":"https://pbs.twimg.com/profile_images/378800000774186373/748aff9380e64c7d95ac0210523e931d.jpeg","name":"Chris Olliver","userID":"056d8e22-c253-46bf-83f4-7ad5797386cb","rank":5},
  {"id":"ca3cf83c-ea79-49dc-919a-ddc6b91d8db3","attainment":0.427807,"avatarURL":"https://media.licdn.com/dms/image/C5103AQHrNgms2Pe6gQ/profile-displayphoto-shrink_200_200/0?e=1541635200&v=beta&t=Rp1D_TrR2jRHThktFC8c6ZSNBEkkw2SGHYXKpJBqQy4","name":"Jim Brennan","userID":"66586300-c8c0-4503-818d-1f9b0d983740","rank":6},
  {"id":"f841f62d-2075-44af-9f56-1902f1f0fc3f","attainment":0.0775194,"avatarURL":"https://pbs.twimg.com/profile_images/674697461156319232/IxqU4Gsu_400x400.jpg","name":"Sally Bronsen","userID":"4a5a0386-0d71-42c8-9cb2-db3434db7a18","rank":7}]
```