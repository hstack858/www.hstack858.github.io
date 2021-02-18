---
name: Best Foot Forward
image_path: "/assets/tinder.png"
---
## Summary

With 2020 bringing a global pandemic, many have had to turn to online dating to meet potential partners. We've all heard classic lines such as "If you have a fish pic, I'm swiping left", but what makes an objectively successful dating website profile has yet to be confirmed. My good friend, Shaan Hossain, and I decided to develop Best Foot Forward to help everyone make the best profile they can through big data. We will assign your Tinder profile with a percentile and advice on how to improve so you can put your best foot forward!

## Technical Details

Data was gathered through a custom built web scraping bot using Python and Selenium. We stored 10,000 male profiles and 10,000 female profiles in JSON format. 

We are currently waiting for all of the profiles in our database to be rated. Once this data is classified, we will be able to use a k-nearest neighbors algorithm along with Tensor Flow to train our model. 

If successful, we have plans to extend this model to other profiles such as LinkedIn.
