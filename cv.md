# Maksim Amialchuk  
**Junior Frontend Developer**  

**Date of birth**: 22/09/1992  
**Place of birth**: Republic of Belarus, Brest region, Pinsk  
**Current location**: Republic of Belarus, Minsk
## Contacts
**Email**: omelchukmaxim@gmail.com  
**Phone number**: +37529-378-68-78  
**GitHub**: MaximOmelchuk  
## About me  
Started learning JavaScript about 1 year ago through codewars.com  
just for work out the mind, but then codding got me hooked.  
Nowadays I have own private legal practice and work as a legal  
advisor with several IT-companies. In the near future I want to change  
my profession and become a frontend developer, because codding is really  
interesting for me and because it is impossible to be a lawyer in country  
without law.  
## Skills  
* HTML  
* CSS  
* JavaScript  
* Git  
## Code example  
Task: [Range Extraction.](https://www.codewars.com/kata/51ba717bb08c1cd60f00002f/javascript)  
Solution:

```
function solution(list){
 
  list=list.map((x,i)=>{
    if (x+1!==list[i+1]) {
      return x;
    } else {
     let last=list.slice(i)
                  .findIndex((y,j)=>y+1!==list[j+i+1]);
     if (last>=2) {
       let tmp=x+'-'+list[last+i];
       for (let e=i+1; e<=last+i; e++) {
         list[e]='';
       }
       return tmp;
     } else return x;
    }
  })
  return list.join(' ').trim().split(/ +/).join();
}
```  
## Experience in development  
in progress...  
## Education  
* University: Belarusian State University, Law Faculty
* Courses:
    * [learn.javascript.ru](https://learn.javascript.ru/)
    * [CS50](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA) 
    * [codewars.com](https://www.codewars.com/)  
    * [The Rolling Scopes School](https://rs.school/) (in progress)  

## English  
B2, EF SET certificate (60 points).  
I got some speaking practice while traveling, constantly  
improve reading and listening skills (technical docs, podcasts,  
films in original voice acting, etc.)
