Hi Ida!

Absolutely outstanding! It looks and works great.

The only thing to be aware of in the future is that Math.random() produces a decimal between 0 and 1, and Math.floor rounds down. A math random number looks like 0.319549834618013. So in your case 

  Math.floor(Math.random() * 47

if the Math.random starts with anything less than about 0.02 it will return 0. Eg 0.020000000 * 47 = 0.94, which rounds down to 0.

This means the API url will be "https://finalspaceapi.com/api/v0/character/0" and the API returns a 502 error. This actually happened to me on my third button click believe it or not. 

BUT this is exactly why we need to handle errors, and you handled the error perfectly so well done! 

As you see below I only have one comment on 1 file, this is excellent work.

29.5/30, but we'll round up to 10/10 and Välgodkänt. Congratulations!

*************************************

CRITERIA FOR GRADING

*************************************

GODKÄNT:
-------------------------------------

Connect to an API ✅

User fired event to launch the fetch ✅

Data is returned and handled efficiently ✅

Display more than one property of the returned data ✅

RWD
  Desktop ✅
  Mobile ✅
 
-------------------------------------

VÄLGODKÄNT:
-------------------------------------

Error handling when fetching the data ✅

Append arguments to the request ✅

Multiple calls to the API ✅

Code style
   Html - 9.5/10 - the img tag always should have an alt attribute.
   CSS -perfect, 10/10
   JS - perfect, 10/10