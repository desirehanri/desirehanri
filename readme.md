# Vatsy Desire 
I'm Vatsy from Madagascar and I'm a student. I really started programming for 7 months, I would like to be good at programming and my goal is to become a video game developer and a Fullstack developer.

### Skills :
* HTML, CSS, JavaScript (level: intermediate) 
* PHP (level: intermediate) 
* C# (level: beginner)
* Java ((level: beginner)

### Example of my work :
So, this is my work about knowing the tomorrow day in JS : 
```javascript
let jour = parseInt(prompt("Entrer Date"));
let mois = parseInt(prompt("Entrer Mois"));
let année = parseInt(prompt("Entrer Année"));

        // Jour 31
   if (jour == 31 && (mois == 8 || mois == 10 ||mois == 12 || mois == 1 || mois == 3 || mois == 5 || mois == 7)){
      let days = (jour - 30);
      mois++;
      alert("Demain c'est le : " + days + " / " + mois + " / "+ année);
   }else if (jour == 31 && mois == 12) {
      jour -= 30;
      mois -= 11;
      année++;
      alert("Demain c'est le Nouvel An : " + jour + " / " + mois + " / "+ année);
   }else if (mois >= 13 ) {
      alert("Il n'y a que 12 mois dans une année.");
   }else if((mois == 8 || mois == 10 ||mois == 12 || mois == 1 || mois == 3 || mois == 5 || mois == 7) && (jour > 31)){
      alert("Le 32e jour n'existe pas dans ce mois!")
   }else if((mois == 11 || mois == 9 || mois == 6 || mois == 4) && jour > 30){ 
      alert("Date invalide, le jour 31 n'existe pas dans ce mois!!!");

        // Jour 30
   }else if (jour == 30 && (mois == 11 || mois == 9 || mois == 6 || mois == 4)) {
      let days = (jour - 29);
      mois++;
      alert("Demain c'est le : " + days + " / " + mois + " / "+ année);

        // Mois de Fevrier (Divisible par 4 ny année bissextile : ilay manana 366 J (29 J ny mois de fevrier))
   }else if (jour == 28 && mois == 2 && année%4 != 0) {
      let days = (jour-27);
      mois++;
      alert("Demain c'est le : " + days + " / " + mois + " / "+ année);
   }else if (jour == 29 && mois == 2 && année%4 != 0) {
      alert("Ce date n'existe pas, cette année est COMMUNE")
   }else if (jour == 29 && mois == 2 && année%4 == 0) {
      let days = (jour-28);
      mois++;
      alert("C'est une année BISSEXTILE, demain c'est le : " + days + " / " + mois + " / "+ année);
   }else if(mois == 2 && jour > 29){
      alert("Ce jour n'existe pas dans ce mois");
   }else{
      jour++;
      alert("Demain c'est le : " + jour + " / " + mois + " / "+ année);
   }
```
### Connect with me : 
* [Facebook](https://facebook.com/bruce.bean.7982 "Vatsy Desire")
* [Twitter](https://twitter.com/desire_vatsy "Vatsy Desire")
* [Instagram](https://instagram.com/v_desire0 "Vatsy Desire")