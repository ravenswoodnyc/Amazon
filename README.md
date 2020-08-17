# Amazon
Pull information together from Amazon using UPC / ASIN codes

On Thu, Jul 16, 2020 at 5:35 PM Brian Morris <brian@jfmorris.net> wrote:

> My initial desire is to catalog my digital and non-digital DVDs.
> Most all has been shifting to a personal cloud, but I still have
> DVDs/BluRay.
>
> I found an app that scans UPC and will email me the whole list In csv file
> or email
>
> I have most my digital movies in Plex.  Would be nice to be able to export
> that collection.  I suspect the file is there somewhere.
>
> Then pull it all together with some basic information at least
> Title, rating, length ... but if cover art, cast, description, link to
> trailer that would be cool.
> Project creep...
>
>
> Sent from my iPad


Fri, Jul 17, 2020 at 2:03 PM  
Subject: Re: Scanning DVDs/books  
From: John Patrick Morris <johnpmorris@gmail.com>  
To: Brian Morris <brian@jfmorris.net>  
  
Fun stuff.

You'll need to get from UPCs to ASINs - Amazon

Bulk lookup: [https://www.synccentric.com/features/upc-asin/](https://www.synccentric.com/features/upc-asin/)

Thumbnails are listed as [images.amazon.com/images/P/ASIN.01.20TRZZZZ.jpg](images.amazon.com/images/P/ASIN.01.20TRZZZZ.jpg)

so the thumbnail for Inferno: The World at War 1939-1945 (ASIN 0307475530, on web at: [https://www.amazon.com/Inferno-World-at-War-1939-1945/dp/0307475530](https://www.amazon.com/Inferno-World-at-War-1939-1945/dp/0307475530))
is available at: [images.amazon.com/images/P/0307273598.01.20TRZZZZ.jpg](images.amazon.com/images/P/0307273598.01.20TRZZZZ.jpg)

There's a whole schema to the thumbnails - if you want larger, smaller,
tilted, etc. [http://etutorials.org/Misc/amazon+tips+tools/Chapter+1.+Browsing+and+Searching/Hack+5+Link+Directly+to+Product+Images/](http://etutorials.org/Misc/amazon+tips+tools/Chapter+1.+Browsing+and+Searching/Hack+5+Link+Directly+to+Product+Images/)

All of this is from a memory of doing it at your mother's house, rebuilt by
looking at the html of [http://straightbounce.com/books](http://straightbounce.com/books)

Title looks like a field in the output [https://asinscope.com/blog/quick-and-easy-way-to-lookup-products-on-amazon-by-upc](https://asinscope.com/blog/quick-and-easy-way-to-lookup-products-on-amazon-by-upc)

One imagines runtime is something that you could do via IMDB API --
[http://www.omdbapi.com/](http://www.omdbapi.com/).  Movie posters are available if you support the
patreon: [https://www.patreon.com/join/omdb](https://www.patreon.com/join/omdb)

It looks like there are folks asking for a UPC / ASIN lookup to IMDB ID,
but none exists. Even though IMDB is an amazon property, the integration
isn't great.  Goodreads is amazon as well, and it's mostly been left to die
on the vine.

This looks like a fun project. Lucy is getting better at sleeping, which
may free up some time and I'd love to help. Else, have fun!

Jack
  
 
