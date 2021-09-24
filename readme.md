# Wiro Agency - HTML & CSS Challenge

The task was to recreate a webpage that looked as close as possible to [this](https://user-images.githubusercontent.com/74301627/134665862-f82321f7-78ca-4265-9848-b3015050330c.jpg) design file I was given.

## How to run

- Ensure you have node.js, yarn and express.js installed on your machine.
- Clone this repository and navigate to the root of the project
- Run `yarn start`
- Navigate to http://localhost:3000 to view the page

## My approach

This was my first attempt at a challenge like this and I enjoyed it alot. I found my progress got alot quicker as I worked, in particular as I became more confident using Flexbox which made positioning much easier. Unfortuntaly, as I'm currently on holiday in the UK visiting family and friends, I had prior family commitments which meant I could only spend around 6 hours on the challenge and it is nowhere near finished.

I initially tried to get to grips with Photopea as I had no prior experience with that or Photoshop. In the time I had I couldn't figure out how to export the images so decided the best approach was to focus on building the page without any of the images as they could be added later. I filtered them out and worked off the file looking like [this](https://github.com/JLBrigham/wiro-agency/issues/1#issue-100635288) as this seemed like a more managable way to approach the challenge.

To ensure that fonts, icons and images were always available I decided to host them on my own server. To do this I set up a server using express.js.

## Improvements and what I would do next

My next steps would be to finish the nav bar, products banners and then move onto the footer. After that I would then look at including the icons and images. Hopefully I may have some time in the coming days to continue working on the project and I would really like to progress with it further.

Positioning and layout were what took up the majority of my time. The positioning of my product banner is not quite right at the moment as the required space isn't there for the first row, I would need to relook at my calculations to figure out where I have gone wrong here. The positioning of the navigation links and X button aren't correct at the moment. As there didn't seem to be a grid in place I calculated the positions using the pixels dimensions layed out. I feel like I have a much better understanding of Flexbox now but would like to learn more about Grid as I think this would also have helped me. This is definitely somthing I plan to look into further.

I would have like to have made the page responsive. When building it have followed the dimensions of the file I was sent which seems wider than you would expect from a standard webpage and does not fit well on my 13inch screen. In order to make the page responsive I would like to look into using media queries, they aren't something I am familiar with at the moment so are something I am keen to learn more about.

I didn't use any CSS frameworks, it would however be interesting to look into frameworks I could have used to make my workflow quicker. However as I am still learning and improving on some aspects of CSS it felt like it was benficial for me to write everything from scratch as this will give me a better understanding if I use frameworks in future.
