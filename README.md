# Bento CSS

Bento CSS is a scss based mini CSS framework. It is meant to pair well with Bootstrap's grid system and will be soon integrated as part of scss partial files.

To use the framework use the css file located `stylesheets/style.css`.

## Components 

### Buttons

```
<button class="btn">Default Button</button>

<button class="btn-outline">Outlined Button</button>

<button class="btn--green">Green Button</button>

<button class="btn--red">Red Button</button>

<button class="btn--yellow">Yellow Button</button>

```

### Forms

#### Regular Text Input

```
<div class="input-group col-lg-6 col-sm-6">
    <label class="label">Label</label>
    <input class="input" type="text" placeholder="Example">
</div>

```
#### Dropdown Select 

```
<div class="input-group col-lg-6 col-sm-6">
    <label class="label">Label</label>
    <select class="select">
         <option>Option 1</option>
         <option>Option 2</option>
         <option>Option 3</option>
         <option>Option 4</option>
    </select>
    <span class="select-arrow"></span>
</div>

```
### Helper Classes

#### Clearfix

```
<div class="clearfix">
... FLoating elements
</div>

```

#### Margin Top

Margin top is great for spacing between components vertically.

```
<div class="pad-top--1">
... 1 representing 1rem (goes up to 5)
</div>

```


#### Padding Top

Padding top is better used only in rare occasions i.e. Pushing content down hidden by a fixed navigation bar.

```
<div class="pad-top--1">
... 1 representing 1rem (goes up to 5)
</div>

```
#### Text Alignment 

```
<p class="align-left">Text</p>
<p class="align-right">Text</p>
<p class="align-center">Text</p>

```

#### Text Alignment 

```
<div class="left">Text</div>
<div class="right">Text</div>
<div class="center">Text</div>

```
### Work in progress

* Checkbox
* Radio Button
* Navigation Bar and Dropdown
* Status Feedback
* Tooltips
* Empty State Call to action
* Modals

