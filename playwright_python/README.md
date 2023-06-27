Google Maps Scraper using Playwright Python

Step 1: Clone/download the repo to your local system.

Step 2: cd into the playwright_python directory.

Step 3: Install the requirements.txt using

     pip install -r requirements.txt

Step 4: Install the necessary browsers required for playwright

    playwright install

Step 5: Run the scraper code using

     python main.py

The results will be stored into a google_reviews.json in your project directory. Using the search_term as Burj Khalifa in Google, we get the sample data shown below.


```json
 {
    "author_name": "Abrar Rahman Nibir",
    "review": "The tallest building in the world and a must visit attraction if you are in Dubai. A must visit venue when staying in Dubai. Impressive views from the top.Just another big building attraction? Not exactly. It's simply colossal and is a must see if you're visiting Dubai. Price is decent and there's a bunch of interesting history about the creation of the tower.I've only ever visited at night and I'm not sure why you wouldn't, the views are incredible and if you go a the right time, you can see the fountains below.I find it more enjoyable to watch from inside Dubai Mall. The only problem is that it is an incredible crowd. For this reason, precautions have been taken and you cannot set foot wherever you want, whenever you want. People are guided by harsh warnings. You are in a race to take pictures in the short time you are given. Of course, there is a solution to this, you can sit in the restaurants on the side and enjoy the evening.",
    "rating": "Rated 5.0 out of 5"
  },
  {
    "author_name": "Oana Pop",
    "review": "Definitely a must see, no matter where you come from. Currently being the tallest building in the world, is a state of art as a whole and a very complex engineering project. The view is simply amazing, no matter if it's day or night time. Staff was very friendly and polite, the place is extremely clean considering the number of tourists around and it's easily accessible and connected with other attractions in the area. The entrance fee is cheap and even the building looks nice from outside, you shouldn't miss the view from the top. The building is sometimes used as a big screen for projections, while the music plays at the fountains. I also recommend visiting Sky Views, to see Burj Khalifa from Outside - at night, when all the lights are on is quite impressive.",
    "rating": "Rated 5.0 out of 5"
  },
  {
    "author_name": "Ross Betts",
    "review": "It's (currently) the tallest building in the world and a must visit attraction if you are in Dubai. From the moment we turned up, the staff were friendly and while we had complimentary tickets to the viewing floor, the price for the attraction is reasonable. The views of Dubai are stunning (we went at night). From the outside this building is also impressed, really cleanly built and a fascinating piece of architecture. The only reason for not getting five starts is a lack of connection, it's so new and fancy, there isn't any history (unlike say the empire state) .",
    "rating": "Rated 4.0 out of 5"
  },
  {
    "author_name": "\u013dubom\u00edr Hajas",
    "review": "The tallest building in the world. You have to see it to understand a beauty of it. Really spectacular.The views of the building from anywhere are absolutely stunning. And the views from the top are unforgettable, if you are in Dubai and you are not scared of heights you have to visit. (We came early morning 8:00am and there was almost no people, you can have whole floor 124 for yourself) and if you scared of heights this is the place to overcome your fear ! You got this.",
    "rating": "Rated 5.0 out of 5"
  },
  {
    "author_name": "Mustafa Morsy",
    "review": "Amazing place. Must visit if you are in Dubai. The area is very lively. Night time is the best, as it is much cooler than the day. During night, they have one of the best water and light show you can see. However, you can spend your day inside the mall, huge one with any brad you can think off! The shopping area and coffee shops and resultants around the Burj and very good.",
    "rating": "Rated 5.0 out of 5"
  },
  {
    "author_name": "Maggie Chen",
    "review": "A must see in Dubai - the world tallest building. Such an incredible tower. The best time to visit is during sunset, getting both the day time view and the even beautiful night time view. Must stay to watch the spectacular lighting shows as well as the fountains!! Very impressed by the speed when they built the tower - the first 100 levels only took one year to build - being one level in 3 days! That\u2019s unbelievable. It worths to buy the ticket for the level 148 viewing deck instead of level 124 and 123.  It\u2019s lot different.",
    "rating": "Rated 5.0 out of 5"
  },
  {
    "author_name": "ANSHIL ETV",
    "review": "This place is the so awesome, you will have a very different experience whenever you visit this place, they have fountain and lightning show.So many people visit this place everyday this is one of of the most and must visited place of Dubai.Everyone visiting Dubai can\u2019t miss to visit this place.There are no charges to see the fountain and the lightning show but if you want to visit from inside there are minimum charges to have an experience from inside.This place is the best example of hard-work of all the engineers and architects including workers.And lastly want to Thanks the Dubai King for such a beautiful experience my visit would be incomplete if I missed to visit this place",
    "rating": "Rated 5.0 out of 5"
  }

```





<br>

### To collect review data from Google on scale and without code visit [Scrapehero Cloud](https://www.scrapehero.com/marketplace/google-reviews/).

<br>

### More resources on scraping and other related topics can be found [here](https://www.scrapehero.com/articles/).
