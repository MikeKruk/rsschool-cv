# Mikhail Kruk

---

## Contact

* Phone / Telegram: 793-563-785

* Email: mi.kruk95@gmail.com

* [GitHub:](https://github.com/MikeKruk)

---

## About me

"I am 25 years old, born in Belarus. Now I live in Poland and work as a lawyer's assistant. I like to develop and programming is a constant self-development. My goal is to become a Junior Developer and only grow ! "

---

## Education 

* Belarusian State University 
    * Faculty: Law Specialisation: Administrative Law 
    * Educationlevel: Bachelor'sdegree

---

## Skills

* HTML

* CSS (BEM , Bootstrap)

* JS

---

## Code Examples

```
function flatten(array) {
    const res = []

    for (let i = 0 ; i < array.length ; i++){
        if (Array.isArray(array[i])){
            const flat = flatten(array[i])
            // рекурсия
            for (let j = 0 ; j < flat.length ; j++) {
                res.push(flat[j])
            }

        } else {
            res.push(array[i])
        }
    }

    return res
  }

  console.log(flatten([['sdad'], [['2', 3]], [[[4]]]])) // -> [1, 2, 3, 4]
  
```

---

## Languages 

* Russian: native level 

* Polish: B1

* English: A2
