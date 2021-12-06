# Here is a list of my notable Code 201 Projects from Code Fellows

## [Busmall App](https://daniel-jacks.github.io/busmall-project/)
This project is used to collect 'votes' for images every time you click on them. After 25 clicks, it will render the results to the left collumn, as well as use canvas to make a graph at the bottom of the page. It also uses local storage to track your results locally, meaning you could refresh/revisit the page, and continue to vote for your favorite images, and it would tally them all up. 
### Things To Note
- Local storage is easy to implement, and nice if you want to avoid sending data somewhere to store it. 
- You will not see the same image numerous times when they rerender to the page. You will also not see the same image consecutively. Each iteration is 3 distinct images that are dissimilar to the 3 before. 
- I could have made this process faster by comparing an _index_ of the image, rather than the entire image object itself. 
- Using graphs to show data can be east to manipulate. I tried to make mine abundantly clear how many time an image was shown and also clicked, whereas if I only graphed how many times and image was clicked, it would be easy to alter what the end user would interpret. 