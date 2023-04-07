# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
You can use a computed effect paired with an onmounted when the page loads. Otherwise you can use a watch effect.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
With a SPA application you do not have to load a seperate file to the page for the user every time they navigate to a different page. Instead you can use "page" navigation while staying on the same page.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
OnMounted runs whatever is within the instructions when the page is loaded. It is typically used to run functions that go and get data.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
The v-model attribute is used to fill in different information by copying whatever is written into different inputs and then compiling them into one object with a value that we can reference when sending a body to the server. For instance, forms are a good example of a time where hte v-model can be helpful to get input from the user.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
These directives can be used for onclick or onsubmit functions where we want the application to run something if the user clicks a button or a form is submitted.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if and the other v-if-else...etc conditional statements.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key helps vue to understand what we are referencing when we say each one or if we make a change to an array and we want those changes to be reflected in the list of objects.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The <slot> element is used for when we want to insert the "guts" or different versions of data into another element such as a form or a section of code where we might have multiple different forms but they all have the same general outline.
```