> [!NOTE]  
> This is a copy of the repo: https://github.com/BurningButter/websitefountain for the purposes of showcasing the features of the project without being a part of the U32 school district.

<img src="https://cloud-avxkw4ux3-hack-club-bot.vercel.app/0frame_2.png" width=240px>

Drinking Fountain Reviewer
===============

Website designed for reviewing and viewing reviews for the water fountains at U32 Middle & High School
Very soon it will be pulling data from the API at ~~https://github.com/BurningButter/foutaindatagrabber~~ to automatically fill reviews and calculate star ratings!

Demo
---------------

The website is live here:
https://hackclub.burningbutter.com/fountain

How to run your own review site (unfinished)
---------------

- Create a Google Form and link it to Google Sheets (creating a Google Form on a school/work account allows you to restrict access to only people in your school district or workspace)
- Navigate to the Google Sheet and go to `File > Share > Publish to Web` and change "Web Page" to "Comma-Separated Values (.csv)". Hit publish and copy the link.
- If you want to hide your data you can use a free website that provides serverless functions (in my case Vercel) and treat the url to the published document as if it was an API key or other senstive item.
- Use [papaparse](https://www.papaparse.com/) to convert the CSV data to JSON on your vercel serverless function or directly in your website's Javascript.

More specifics on how to use this repo coming soon