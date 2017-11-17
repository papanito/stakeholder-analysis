# stakeholder-analyzis
A webapp which helps me to do stakeholder analyzis i.e. graphical representation of power and interest 

# Foreword
Inspired by [this post](https://medium.com/unicorn-supplies/angular-vs-react-vs-vue-a-2017-comparison-c5c52d620176) I decided to use [Vue](https://vuejs.org/). I have no experience at all with JavaScript Frameworks, so I guess this will be an interesting Journey.

# First steps

Before starting we need to install Vue
* [Include vue.js](https://vuejs.org/v2/guide/#Getting-Started)
* [Install DevTools](https://github.com/vuejs/vue-devtools#vue-devtools)


As I uses VS Code I also recomment these extensions
* [Vue Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=liuji-jim.vue)
* [Vue Development Extension Pack](https://marketplace.visualstudio.com/items?itemName=changjoo-park.vscode-vue-devpack)

# Testing
There is a specific page for unit testing at https://vuejs.org/v2/guide/unit-testing.html with specific recommendation to use [Karma](http://karma-runner.github.io/) Test runner.


# Simple vue example
```
<html>
    <head>
          <script src="https://unpkg.com/vue"></script>
    </head>
    <body>
        <div id="app">
            {{ message }}
        </div>
        <script>
            var app = new Vue({
                el: '#app',
                data: {
                    message: 'Hello Vue!'
                }
            })
        </script>
    </body>
</html>
```

# Stakeholder Analysis
Checkout https://www.mindtools.com/pages/article/newPPM_07.htm for details. Below a summary of the important key elements
## Terms
*Stakeholders* all the people who are affected by your work, who have influence or power over it, or have an interest in its successful or unsuccessful conclusion.
*Interest* Some may be interested in what you are doing, others may not care.
*Power* Some of these may have the power either to block or advance
## Actions	
High power, interested people: 
these are the people you must fully engage and make the greatest efforts to satisfy.
High power, less interested people:
put enough work in with these people to keep them satisfied, but not so much that they become bored with your message.
Low power, interested people: 
keep these people adequately informed, and talk to them to ensure that no major issues are arising. These people can often be very helpful with the detail of your project.
Low power, less interested people: 
again, monitor these people, but do not bore them with excessive communication.
## Key Questions
What financial or emotional interest do they have in the outcome of your work? Is it positive or negative?
* What motivates them most of all?
* What information do they want from you?
* How do they want to receive information from you? What is the best way of communicating your message to them?
* What is their current opinion of your work? Is it based on good information?
* Who influences their opinions generally, and who influences their opinion of you? Do some of these influencers therefore become important stakeholders in their own right?
* If they are not likely to be positive, what will win them around to support your project?
* If you don't think you will be able to win them around, how will you manage their opposition?
* Who else might be influenced by their opinions? Do these people become stakeholders in their own right?

You can summarize the understanding you have gained on the stakeholder map, so that you can easily see which stakeholders are expected to be blockers or critics, and which stakeholders are likely to be advocates and supporters or your project. A good way of doing this is by color coding	
green	advocates and supporters
orange	neutral
red	blockers and critics