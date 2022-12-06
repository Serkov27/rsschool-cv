# Andrey Serkov
## Student
## Contacts
e-mail: andrewserckov46@gmail.com
phone: +375 (33) 6293833
telergram: @Serkov_A
## Resume
I graduated from Mogilev State University of Food. Want to become front-end developer. My strength are knoledge how to work in a team, quickly adapt to changes, have stress resistance, have a desire to learn something new. I'm currently working as a process engineer.
## Skills
HTML
CSS
JS
## Code example
''' function transform(arr) {
        if (!Array.isArray(arr)) {
          throw new Error();
      }
        let newArr = [];
        for (let i = 0; i < arr.length; i+=1) {
         if(arr[i] === '--discard-next') {
           if (arr.length - i >= 2) {
            i+=1
           }
         } else if(arr[i] === '--discard-prev') {
            if (i >= 1 && arr[i - 2] !== "--discard-next") {
              newArr.pop()
            }
         }else if(arr[i] === "--double-next") {
           if(arr.length - i >= 2) {
             newArr.push(arr[i+1])
           }
         }else if(arr[i] === "--double-prev") {
           if(i >= 1 && arr[i-2] !== "--discard-next") {
             newArr.push(arr[i-1])
           }
         } else {
          newArr.push(arr[i])
        }
        }
        return newArr
      };
'''
## Experience
I have no experience of Junior Dev.
## Education
*Mogilev State University of Food (2017 specialist)*
*Mogilev State University of Food (2019 magistracy)*
## English
English level B1+ (B2)