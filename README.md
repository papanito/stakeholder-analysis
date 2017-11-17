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