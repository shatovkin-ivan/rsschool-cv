# Shatovkin Ivan

## Junior Frontend Developer

### Contact information:

***Phone:*** _+8-017-1234567_

***E-mail:*** _shatowkin.ivan@yandex.ru_

## About me


My acquaintance with frontend development began in 2019 when my friend asked me to create a website for his small business. At that time, I didn't know how it all worked, but I was very curious about it, so I spent six months studying this process in detail. After I got a job at a digital agency and did freelance tasks at the same time. Currently I'm a member of the development team of the programmatic advertising project. Frontend development for me is a promising direction where I can realize my full potential, so I think this is an area that I will be doing all my life.

## My skills
* HTML 5, CSS 3
* Preprocessors: PUG || SASS
* JavaScript
* Vue + vue ecosystem (Vuex, vue-router, etc.)
* Node.js basics
* Git

## Code example
Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case).
```
function toCamelCase(str) {
    let result = []
    for(let i  = 0; i < str.length; i++) {
        if (str[i] === '-' || str[i] === '_') {
            result.push(str[i+1].toUpperCase())
            i++
        } else {
            result.push(str[i])
        }
    }
    return result.join('')
}
```