[GitCV]: none
[Email]: mailto:dlamardima@gmail.com
[Phone]: tel:+375257391102
[Location]: https://www.google.com/maps/place/%D0%9C%D0%B8%D0%BD%D1%81%D0%BA/@53.8933405,27.5770606,12z/data=!4m5!3m4!1s0x46dbcfd35b1e6ad3:0xb61b853ddb570d9!8m2!3d53.9006011!4d27.558972
[GitHub]: https://github.com/dlamar228
[LinkedIn]: https://www.linkedin.com/in/dzmitry-krylou/
[CodeWars]: https://www.codewars.com/users/dlamar228

[EmailSign]: https://github.com/dlamar228/battle-field/blob/main/email-sign.svg
[PhoneSign]: https://github.com/dlamar228/battle-field/blob/main/phone-sign.svg
[LocationSign]: https://github.com/dlamar228/battle-field/blob/main/location-sign.svg
[GitHubSign]: https://github.com/dlamar228/battle-field/blob/main/github-sign.svg
[LinkedInSign]: https://github.com/dlamar228/battle-field/blob/main/linkedin-sign.svg
[CodeWarsSign]: https://github.com/dlamar228/battle-field/blob/main/codewars-sign.svg


# [rsschool-cv](GitCV) #

# DZMITRY KRYLOU #

# CONTACT #

![alt][EmailSign] [**dlamardima@gmail.com**](Email)  
![alt][PhoneSign] [**+375 25 7391102**](Phone)  
![alt][LocationSign] [**Minsk, RB**](Location)  
![alt][GitHubSign] [**github.com**](GitHub)  
![alt][LinkedInSign] [**linkedin.com**](LinkedIn)  
![alt][CodeWarsSign] [**codewars.com**](CodeWars)  

# EXPERIENCE #

I've had practical experience in devуloping websites via **`JavaScript`** and **`Python`**. I'm currently having deal with **`SQL`**,**`Python`** for backend and **`Vue`**, **`JavaScript`** for frontend at a startup.I take part in this project as a Junior so I adjust json, create new tables and write queries, add new and revise old functional for backend regularly.

# CODE EXAMPLE #
```
function scramble(str1, str2) {
  
  function getFrequency(array){
    let entries = Array.from(new Set(array)).map((element)=> [element,0])
    let frequency = new Map(entries)
    
    array.forEach((element)=> frequency.set(element,frequency.get(element) +1))
    
    return frequency
  }
  
  function hasLetter(str,letter,count){
    
    let result = true
    let index = -1
    
    for(let i = 0; i<count;i++){
      index = str.indexOf(letter,index + 1) 
      
      if(index == -1 ){
        result = false
        break
      }
      
    }
    
    return result
  }
  
  let result = true
  
  let frequency = getFrequency(Array.from(str2))
  
  for(let [letter,count] of frequency){
    
      result = hasLetter(str1,letter,count)
      if(!result) break

  }
 
  return result
  
}
```

# SKILLS #

**`Python`, `Django`, `Bottle`, `Web3`**  
**`JavaScript`, `Web3`**  
**`SQL`, `SQLite`, `MongoDB`, `Oracle SQL`**  
**`HTML`, `CSS`, `BEM`**  
**`Git`, `WebStrom`, `PyCharm`, `VS`, `VScode`**  


# EDUCATION #

**Belarusian National Technical University** &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; **Minsk**  
Information Technology faculty, bachelor degree &nbsp;&nbsp; &nbsp; &nbsp;Sep. 2017 - June 2021

# LANGUAGES #

**English, B1**  
**Russian**

