# Second-Portfolio 
Hi! My name is Tyler Brian Yeager and I am a Full-Stack developer in training. I am currently enrolled in the full-time Full-Stacking Coding bootcamp through UC Berkeley. I have a lot of professional experience at the federal level though not in web developmenet. Over my years of work I have proven myself capable of adapting and learning new skills with enough proficiency to match, and sometimes exceed, the skill levels of my senior coworkers.   

## Details about this project

This is my second attempt at a professional portfolio. Initially I had ideas of utilizing some of the other css frameworks that we had used in class, however, I really wanted the chance to build a portfolio from scratch again. In particular, I wanted to experiment with a fixed position nav bar that changed when certain break points in screen size were reached. I believe I achieved that goal.  In addition to this change, I have added a link to my updated resume as well. 
![Snapshot](https://user-images.githubusercontent.com/89880190/136886516-7b1d25a1-3c19-45e3-92f0-c38210fd8fb9.png)

## Some Code Snippets
Below are a few code snippets that I enjoyed and what they do. 
First is the coding that set my navigation to the left side of the page. Additionally, by creating an id "#top" I was able to create a link that took the user back to the top of the page. 

```
#top {
    position: fixed;
    flex-wrap: wrap;
    margin-right: 70%;
}

ul {
    padding: 10px;
    margin-left: 40px;
    font-size: 30px;
}

ul li {
    padding: 20px;
    list-style-type: none;
}
```

Next is the snippet of code that set all my image parameters, such as width and height, and created a fun hover/active effect. 

```
img {
    max-width: 100%;
    box-shadow: 10px 10px 5px #9e9e9e;
}

img:hover {
    box-shadow: 10px 10px 5px #f52e2e;
}

img:hover:active {
    box-shadow: -10px -10px 5px #2eacf5;
}
```

Lastly, this bit of code was my first attempt at using media screen to change the position of an element on my page. When the break point is reached my nav bar will change positions to the top making viewing on a mobile device much easier. 

```
@media screen and (max-width: 768px) {
    #top {
        position: static;
        display: flex;
        justify-content: center;
        margin: auto;
    }

    ul {
        display: flex;
        margin: auto;
        flex-wrap: wrap;
    }

    .container1,
    .container2, 
    .container3,
    .container4 {
        margin: auto;
    }

    .hidden {
        visibility: visible;
    }
}    
```

## Cloning down a copy

To get a working copy on your machine you will need a few things such as access to Gitbash or Terminal, a working SSH key, a Github account, and a code reader like VS Code

Once you have a working SSH key added to your Github account, navigate to the Second-Portfolio Repository. Click the green "code" button on the top right, select the ssh option, and save a copy to your clipboard.  
![Snapshot2](https://user-images.githubusercontent.com/89880190/136886696-a8402d27-1085-432f-878a-6d53560da5ed.png)

Next: 
Open Gitbash or Terminal and navigate to a directory that you would like to add the cloned repository. Once in your desired directory type in
"git clone 'right click to paste'" and press enter. This will clone the repository onto your personal machine.


Lastly: 
Type 'ls' into your Gitbash or Terminal to see a list of items within the directory. If you have done the previous steps correctly then you should see a respository titled "Second-Portfolio." Simply type in "code ." to open it in your code editor of choice and have fun!


### Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* [See the Live Site!](https://tylerbyeager.github.io/second-portfolio/)


## Authors

* **Tyler Brian Yeager** 

- [Link to Portfolio Site](https://github.com/TylerBYeager/second-portfolio)
- [Link to Github](https://github.com/TylerBYeager)
- [Link to LinkedIn](https://www.linkedin.com/in/tyler-yeager-611926213/)

## License

This project is licensed under the MIT License 

## Acknowledgments

* I would like to acknowledge the rest of my fellow bootcamp students and instructors who have helped me get this far. This has been a rigorous journey and each time I think I've got the hang of something, a new challenge appears that pushes me to my limits. I look forward to learning more and to working for a great company in the future. 
