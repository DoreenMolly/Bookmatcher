# Bookmatcher
#By Doreen Molly Wanjiru

Book lovers at times find themselves wanting to get a random book recommendation and they don’t know where to start looking.  This is their chance to search for various  books from a broad variety of genres, using the author’s name.
This website therefore allows users to find a random book recommendation in just a click of a button!

# Functioning of the app
I used the https://bookshelves.p.rapidapi.com/books API to access different authors and some of their books. 

There's more information about the website on my blog: https://medium.com/@doreen.wanjiru/my-website-f67043e75f7d

# Part of the code
```
fetch('https://_bookshelves.p.rapidapi.com/books', options)
	.then(response => response.json())
	.then(response => {

		sample.Books.forEach(element => {
		singleElem(display(element))
			
		});
```
