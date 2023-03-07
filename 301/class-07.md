# Class 7 notes

## Rest 

- Who is Roy Fielding?

He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.

- Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?

- What is the HTTP protocol that Fielding and his friends created?

So anyway, HTTP—this protocol Fielding and his friends created—is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

- What does a GET do?

Web pages usually have images, right? Those are separate resources. The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a URL.

- What does a POST do?

Each of the systems would retrieve information from each other using a simple HTTP GET. If one system needs to add something to another system, it would use an HTTP verb of POST. If a system wants to replace something in another system, it uses an HTTP verb of PUT, or, to do a partial update, it'll hopefully use PATCH. The only thing left to figure out is what the data models should look like.

- What does PUT do?

 it uses an HTTP verb of PUT, or, to do a partial update, it'll hopefully use PATCH. The only thing left to figure out is what the data models should look like.

- What does PATCH do?

use PATCH. 
## 6 API Keys

[LocationIQ Geocoding](https://locationiq.com/)

- yes

[Weatherbit](https://www.weatherbit.io/account/dashboard)

- yes

[yelpApi](https://docs.developer.yelp.com/reference/v3_business_search)

-yes

[MOvieApi](https://developers.themoviedb.org/3/getting-started/introduction)

-yes
