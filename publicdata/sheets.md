# UMSKT Product Keys
If you clicked this, you just saw approximately 90,000 keys. One of those 90,000 keys will work with your Microsoft product (minus online activation, because someone's probably already took that key.)

## Ordering?
The way Microsoft makes keys is that it has 2 values (there's a lot more, but that's besides the point):
* A BINK ID, a hexidecimal value that Microsoft product installers use to make sure the key isn't from another product or anything (ex: using a Windows 98 key on Windows XP).
* A Channel ID, a numerical value from 000 to 999 that Microsoft products use (usually after insallation, before online activation) to further make sure the key isn't from another product.

The key has no metadata regarding to what the key is supposed to be used for, only "I'm for a product that accepts the BINK of \[00-FF\] and a Channel ID of \[000-999\]". What it was meant to be used for was up to the installer.

Because of this, most of the keys don't even have products associated with them.

This is where you come in. If you put in product keys you own/found online through https://mskt.surge.sh?validate=, you'll see this:
![image](https://github.com/UMSKT/.github/assets/57580668/3be4e4e2-6d3b-4f5d-9958-c83a08968b5b)
*contents obviously edited*

Send a screenshot of that in the comment section below (no, you're not on YouTube), including your key (if you want to), and then we can use that information to figure out what that product is, and label it on the spreadsheet. You'll be credited for finding it (if you want to).

# "Failed to generate"?

That means we don't have the numerical values that back those BINK ID's up (see https://github.com/UMSKT/UMSKT/keys.json for that). Because of that, we simply can't generate those keys.

If you have a really weird, unseen Microsoft product, so unseen that a key can't be generated, **please go to https://umskt.zulipchat.com**. We can get the values needed to make the keys, and help other people with that product.

# "Incorrect data"?

That means that we do have the numerical values that back those BINK ID's up, but we don't know how to really use them. Because of that, those keys can't be generated.

This falls into the same category of "weird, unseen Microsoft product", so **please go to https://umskt.zulipchat.com** if none of the keys work. 

# Going through the stuff that is labeled

Click on the "Data" tab, then "Filter views", then "Product". This sorts the spreadsheet alphabetically by the product name, so you can find what you want. 
