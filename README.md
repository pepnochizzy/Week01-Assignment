# Week01-Assignment

A splash page

## TIPS

- use full relative path to link files (./)

```html
<link rel="stylesheet" href="./styles.css" />
```

## Reflection

Please also provide an assignment reflection in your project README.md file.

Required
🎯 What requirements did you achieve?
🎯 Were there any requirements or goals that you were unable to achieve?
🎯 If so, what was it that you found difficult about these tasks?
Optional
🏹 Feel free to add any other reflections you would like to share about your submission, for example:

Requesting feedback about a specific part of your submission.
What useful external sources helped you complete the assignment (e.g Youtube tutorials)?
What errors or bugs did you encounter while completing your assignment? How did you solve them?
What went really well and what could have gone better?

## References

-any links used (eg images) and any links used for research

- SOURCE : https://64.media.tumblr.com/6b9040d2353a06211f4ab647872569fb/8c932cb66fd8c5a1-c1/s540x810/6cdc6e2ec577206862484fb1ddb31d460ab0a72d.pnj art by Sea Spines
- RESEARCH : https://www.w3schools.com/css/css3_shadows_box.asp wanting to learn how to make shadow cards, used to make the welcome msg div "lift" when hovered.
  -Research: W3/MDN for checking what the order of values is for shorthand properties and other small checks.

## Questions

- I have used a font awesome icon for a shopping basket, I have seen on their website that by default these are ignored by screen readers. As I understand it, best practice would be to also have text- in this case "basket". However, I do not want this to be visible on my page, I just want it available for screenreaders so that they know where to press. I have seen aria-hidden but I think that does the opposite. I have used alt for now but I think that this is mainly for images. Is there an easy way to do this/correct ettiquete?
- Is there a way to blur image edges? I wanted to blur the edge of #about-img (rat), I took a look at this https://stackoverflow.com/questions/24709915/blur-the-edges-of-an-image-or-background-image-with-css but sadly was unable to replicate this result within my own code (I did have a div for the image when trying but still, no dice).
- in my about section, I really struggled to try and remove the large gap whilst also maintaining the rough layout. I know this is because of the absolute elements and large margins, but I found without that I couldn't quite get the look I wanted. Any tips would be greatly appreciated.

## comments for reflection

## What requirements did you achieve?

- I tried to achieve all of the achievements and a few of the stretch goals.
- Although I did complete them, I found the absolute/relative relationship a lot more difficult in the about section, I believe this is because unlike the "digipets" section, the text was not just going on top of images, I also wanted the <p> tags to go in different places across the section. It did frustrate me because I was able to understand the "frog game" about flexbox so I felt I should have found this a bit more doable than I did but I think this is just a familiarity/do it loads of times thing 😂
- I found the majority of the work to be a fun exercise, I really enjoy the design aspect and trying to make it look like a "real" website vs just a word document. I am most happy with the "home" section, I feel it does pass as a genuine website. The about section is my least favourite and as discussed, was my most difficult section.

- I got stuck when trying to avoid overusing divs as this is something I realised I do. When doing the #digipets section, my plan was to have the img and h2 elements all in the section with no divs and have the h2 elements overlay the images by making the section a flexbox AND make the h2 elements absolute (relative to the container), and separate them out using their own flexbox manually until they were spaced how I wanted over the images. The result was the images styled how I wanted but the h2 elements sat to the right of the images and all stacked on eachother. I realise now that this is because they were all absolutely positioned making them stack on each other vs stack on the images. In this case, my wanting to avoid divs meant I stopped using them where actually appropriate. I ended up checking with chatgpt to see if this was correct. I also used stackoverflow. Overall the issue was stemming from me overcomplicating things, this seems to be a common problem I face.

## What to do moving forward

- I would like to continue trying to use absolute/relative in my work (as I know I will have to anyway) to gain proficiency, this will help in the future with making more complex design and more professional sites.
- I feel I have a decent understanding, and a good understanding when it comes to simple layouts (like in the #digipets section).
- Learn media queries (I know this is next week), I found it really frustrating that my page looks nice at full screen but, once again, the about section does not look good scaled down D:
