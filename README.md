# scroll-to-elements
# **How to Use**

## **Step 1: Connect the Script File**

First, ensure that you have the `index.js` file available in your project. If not, you can create one. Next, link the script file to your HTML document. Add the following line inside the `<head>` tag of your HTML file:

```html
<script src="index.js"></script>
```

## **Step 2: Create a Scroll Goal ID**

Create a unique identifier for your scroll goal by assigning an id to the HTML element you want to scroll to. For example

```
<section id="scrollGoal">
    <!-- Your content goes here -->
</section>
```

## Step 3: Create a Link with href Attribute

Generate an anchor (```<a>```) element with the href attribute pointing to the previously defined id. This link will act as the trigger for a smooth scroll. For instance:

```
<a href="#scrollGoal">Scroll to Goal</a>
```

**_Feel free to customize the id and link text according to your project requirements._**

**You can check how the library works by visiting the [demo page](https://artemproshkovskiy.github.io/scroll-to-elements/).**

