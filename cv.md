## [rsschool-cv](https://github.com/llfssaa/rsschool-cv.git)
***
# Liubovi Topolcean
***
### Contacts
***
* Location: Tiraspol, Moldova
* Phone: +373 7775 6218
* Email: liulia.1758@gmail.com
* Discord: llfssaa
* Github: [llfssaa](https://github.com/llfssaa)
* Linkedin: [Liubovi Topolcean](https://www.linkedin.com/in/liubovi-topolcean/)
***
### About me
***
### Skills
***
* HTML
* CSS/SASS
* JavaScript 
* React JS / Redux
* GIT
 ***
### Code Example
***
```
function cakes(recipe, available) {
    let A = Object.keys(available);
    for (let prop in recipe){
        if (A.indexOf(prop) === -1) {
            return 0;
        }
    }
    let arr = [];
    for (let prop in available){
        if (prop in recipe){
            arr.push(available[prop] / recipe[prop]);
        }
    }
    return Math.floor(arr.sort((a,b) => a - b)[0]);
}
```
***
### Experience
***
