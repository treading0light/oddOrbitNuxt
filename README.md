# Setup

## run:

`npm install`
`npm run dev`

## What's going on here?

I went ahead and set up your site as a nuxt 3 project. First of all, ignore all the "High vulnerability risk" type warnings, it's just a dependency thing that won't affect you and will be 
fixed eventually, it always is.

I have put my own comments throughout the project but mainly in app.vue, and both pages. I would start by looking at app.vue, and then look at both pages/index.vue and pages/alientArt.vue. All your images are in public/images, your external CSS is in assets/css/styles.css.

## Keep out of the following directories:
- .nuxt
- node_modules

There's nothing in there for you lol. 

## Creating new pages

If you want to make a new page just create a file in the pages directory and give it a .vue file name. Then add a link to it in your nav, which is in app.vue. 

## Keep in mind

Most everything works the same as with vanilla JS and and html but some things are a little different. I have made comments in the code but here's a little bit:

- All pages and components must have ONE root element inside the <template>
- Use @click="" instead of onclick="" 
- Instead of <a> use <NuxtLink> to make it super fast and cool
- When using AI to write code be sure to specify you are using Vue 3 with composition API and script setup syntax
- There are two and a half ways of writing Vue code. Originally it was "options api" and then "composition api" which was better but had to be wrapped in a setup function. and finally now you just add setup as an attribute in your script tag.
- Get used to using arrow functions, as it's really handy to have functions exist as a const when calling them from the DOM

```js
function regularFunction() {
    //
}

const arrowFunction = () => {

}
```