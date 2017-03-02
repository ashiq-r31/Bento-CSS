# Bento CSS

Bento CSS is a scss based mini CSS framework. It is meant to pair well with Bootstrap's grid system and will be soon integrated as part of scss partial files.

To use the framework use the css file located `stylesheets/style.css`.

## Components 

### Buttons

<img width="1243" alt="screen shot 2017-03-02 at 1 42 58 am" src="https://cloud.githubusercontent.com/assets/7483633/23498087/9b61b160-feeb-11e6-95d2-6c3875dbf84f.png">
```
<button class="btn">Default Button</button>

<button class="btn-outline">Outlined Button</button>

<button class="btn--green">Green Button</button>

<button class="btn--red">Red Button</button>

<button class="btn--yellow">Yellow Button</button>
```

### Forms

<img width="1241" alt="screen shot 2017-03-02 at 1 50 23 am" src="https://cloud.githubusercontent.com/assets/7483633/23497862/a9ccd906-feea-11e6-95a1-a680da94a48c.png">

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
#### Checkbox

```
<div class="input-group col-lg-12 col-sm-12">
    <input class="checkbox" type="checkbox" id="first" name="first"> 
    <label class="label" for="first">Option 1</label>

    <input type="checkbox" class="checkbox" id="second" name="second"> 
    <label class="label" for="second">Option 2</label>
</div>
```

#### Radio Buttons

```
<div class="input-group col-lg-12 col-sm-12">
     <input class="radio" type="radio" name="group" id="third">
     <label for="third" class="label">Option 1</label>

     <input class="radio" type="radio" name="group" id="fourth">
     <label for="fourth" class="label">Option 2</label>
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
<div class="m-top--1">
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

#### Floats 

```
<div class="left"> ... </div>
<div class="right"> ... </div>
```
#### Centering
```
<div class="center"> ... </div>
```
### Work in progress

* Navigation Bar and Dropdown
* Status Feedback
* Tooltips
* Empty State Call to action
* Modals

