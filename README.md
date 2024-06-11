# The objective:
The goal of this project is to devise a prototype of a time-of-use tool to assist users in saving money on electrical rates. Currently there are no such products on the market as there is a lack of a centralized database for time-of-use rates. Ideally our users will tell us their state and electrical provider and the app would approximate savings if users were to swap to a different electrical rate plan with their selected company. We've developed devices that would non-invasively approximate within 5 mA how much current a device is drawing from an outlet. This device is described in the documentation I've done for the device.

# Trailer & concept

Below is a teaser trailer explaining the concept of time-of-use rates for our project and the prototypes we've developed for backend and frontend. THis trailer also elaborates on the hardware usage and how data is posted as well. Our frontend was done in Kotlin and churned out to be more complex developing an app than a webpage.
[![Video Title](https://img.youtube.com/vi/lQb-QEtX2oo/0.jpg)](https://www.youtube.com/watch?v=lQb-QEtX2oo)



# PERN web ap tool

Instead of continuing with the app in Kotlin, we've developed a new and improved back end using PostgreSQL, ExpressJS, React, and NodeJS (PERN). Using a pre-devised web stack eliminated the complexities we previously encountered in developing a phone app. JavaScript has several pre-defined functions that simplified the work of packing and unpacking data from JSON traffic from backend APIs. Our design can update every second by default, up to every 5 ms. In our demo, we demonstrate a number of features, which are also highlighted in our presentation.


[![Video Title](https://img.youtube.com/vi/stkasKSqz8k/0.jpg)](https://www.youtube.com/watch?v=stkasKSqz8k)


# Readings
Given are two PDFs, one is the documentation written for the project and the other a IEEE draft paper both written by Calvin Li and Nicholas prokoso. The documentation is a indepth look into the original build of green grid advisor before the swap over to the web application build.

# Disclaimer
Please do not reuse my material without permission, please contact me at calvinhuanli@gmail.com for inquires about this project. More documentation on code can be provided upon request.