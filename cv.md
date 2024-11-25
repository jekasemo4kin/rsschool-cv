# Siomochkin Eugene
### Frontend Developer

---
---


### Contacts for communication:
**Phone:** в вк отпишу
**Gmail:** jekasemo4kin@gmail.com
**VK:** https://vk.com/v13ss
**inst:** zasolyvsolo


---
---


### Information about yourself:

After 11 years of school, I went to the Belarusian Russian University, which is located in my hometown of Mogilev.Specialty - Automated electric drives. Faculty - Electrotechnical. The diploma will say: "electrical engineer", "power engineer", "electronics engineer". I decided to enter there because the future work is highly paid, physics and mathematics, a technical mindset were interesting. Now I decided to try my hand at programming.

---
---

### Skills:

- HTML5 
- CSS
- JavaScript Basics
- SCSS, SASS
- Git, GitHub
- VS Code
- NodeJS Basics
- Figma Basics

---
---

### Code example:

**Stop gninnipS My sdroW!**
*Write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces. Spaces will be included only when more than one word is present.

Examples: spinWords( "Hey fellow warriors" ) => returns "Hey wollef sroirraw" spinWords( "This is a test") => returns "This is a test" spinWords( "This is another test" )=> returns "This is rehtona test"*

```javascript
function spinWords ( string ){
    let xx = [];
    let yy = string.split(" ");    
    if (string.split(' ').join('').length>1 ){
    for (let i = 0; i < yy.length; i++){   
        xx.push(yy[i]);        
    if (yy[i].length>4){       
        xx[i] = yy[i].split("").reverse().join(""); 
    }
    }
        return  xx.join(" "); 
    }
    else{
        return '';
    }
    }
    spinWords ("Hey fellow warriors");
    spinWords ( "This is a test");
    spinWords ( "This is another test");
```
---
---