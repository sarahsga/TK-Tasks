# Tech Karo - Final Test
### The Lotus Translations App

| **Powered By** Tech Karo  |

**Oct 4th, 2018**

### Task ###
Create a Recipe app:
    - Go to http://www.khanapakana.com/ and choose a recipe
    - Create a web page of your chosen recipe. 
    - Your recipe should have lists of:
        - Ingredients
        - Instructions
    - Each ingredient quantity should be in italics

### What does it look like?

![mockup](screenshots/mockup-1.png)

----

## Rules
1. Your app should look like the mockups attached in the `screenshots` folder. Try to achieve pixel perfection.

----
## API Instructions
When the flags on the top are clicked, the language should change - For example, clicking the Chinese flag should display text in Chinese. The translations can be fetched from the API using query string:

**API URL:** https://techkaro-test.herokuapp.com/api/v1/getdata
**Query Parameter:** lang
**lang values**: `en` for English, `zh` for Chinese, and `ur` for Urdu

**Example:** To get data in Chinese, use https://techkaro-test.herokuapp.com/api/v1/getdata?lang=zh

-------------------
