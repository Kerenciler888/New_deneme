# DENEME YAPILIYOR
I just started to learn python programming.
## Bir Alt Baslik Olusturma
We can create a python dictionary and then encode it using JSON and write it to a file:
...
course_films = {}
course_films['Jack goes Boating'] = 'Java: Might We Be Friends Project'
...
with open('course_films.json', 'w') as film_file:
    film_file.write(json.dumps(course_films))
...

