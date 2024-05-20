<p align="center">
  <a href="https://ui-gilob.in">
      <img width="20%" src="http://ui.gilob.in/@asset/logo.svg" alt="ui-gilob" />
      <h1 align="center">UI-Gilob</h1>
  </a>
</p>
</br>

![](http://ui.gilob.in/@asset/Screenshot.png)

# CDN 
```html
<link href="https://cdn.jsdelivr.net/gh/uigilob/UI@main/src/ui-gilob.css" rel="stylesheet" type="text/css">
<script src="https://cdn.jsdelivr.net/gh/uigilob/UI@main/src/ui-gilob.js"></script>
```

```html
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>smaple</title> <!-- defulat  scropts-->
  <link href="https://cdn.jsdelivr.net/gh/uigilob/UI@main/src/ui-gilob.css" rel="stylesheet" type="text/css">
  <script src="https://cdn.jsdelivr.net/gh/uigilob/UI@main/src/ui-gilob.js"></script>
</head>

<body>
  <div class="h1 t-center">Hello World</div>
  <script>
   $alert("Hello World")
 </script>
</body>

</html>
```
## template 
```html
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>smaple</title>
    <link href="https://cdn.jsdelivr.net/gh/uigilob/UI@main/src/ui-gilob.css" rel="stylesheet" type="text/css">
    <script src="https://cdn.jsdelivr.net/gh/uigilob/UI@main/src/ui-gilob.js"></script>
</head>

<body class="theme fixed p0 over-x-adjust center">
    <!-- Sidebar -->
    <nav class="sidebar b-right" s-defind="menu">
        <!-- Sidebar Header -->
        <div class="padding-cnt bar-exp">Sidebar Header</div>

        <!-- Sidebar Content -->
        <div class="sidebar-content flex flex-col gap-l-f padding-cnt">
            Sidebar Content
        </div>

        <!-- Sidebar Footer -->
        <div class="padding-cnt" cnt-tag="footer">Sidebar Footer</div>
    </nav>

    <!-- Main Content Body -->
    <div class="body flex flex-col">
        <!-- Header -->
        <header class=" center-tb b-b p gap" md-fix="true">
            <a href="/" class="h6 bold c-p ">BRAND</a>
            <button class="button m-auto-l" sidebar="trigger" s-defind="menu">Menu</button>
        </header>

        <!-- Content Area -->
        <div class="home padding-cnt d-scroll">
            <h1 class="h1 t-center">Heading of a Blog Post</h1>
            <!-- Add your main content here -->
        </div>
    </div>

    <!-- Add your scripts or other body elements here -->

</body>

</html>

```


# Getting Started

Visit  [https://ui.gilob.in/get-started](https://ui.gilob.in/get-started) to get started with UI-Gilob.



# modules


```html
<!-- Import all modules -->
<link href="/import.css?c=all" rel="stylesheet" type="text/css">
<script src="/import.js?c=all&g=cmd"></script>

<!-- Or import specific modules -->
<link href="/import.css?c=b&c=at" rel="stylesheet" type="text/css">
<script src="/import.js?c=b&c=at"></script>
```

### Multiple Parts Importing

You can import multiple parts using the following syntax:

```html
<!-- Import multiple parts -->
<link href="/import.css?c=tb" rel="stylesheet" type="text/css">
<script src="/import.js?c=tb"></script>

<!-- Import additional modules -->
<link href="/modules.css?c=b&c=at" rel="stylesheet" type="text/css">
<script src="/import.js?c=b&c=at"></script>
```

## Default Imports

Here's a list of default imports in [Your Web UI Framework/Library Name]:

- `functions` Import functions
- `Ajax` Import Ajax-related modules, including
     - `$Http`
     - `$htp`
- `theme` theme


## Global 

The global table consists of various import keys that allow you to import multiple modules or components at once. Here  a breakdown of the available global import keys

| Import Key | Description                                          |
|------------|------------------------------------------------------|
| g=all      | Import all modules globals                |
| g=e        |  Event bind          |
| g=c        | Event cmd     |
| g=t        |  template               |
| g=hl       | dynamic loading (Ajax)     |


## Components 

The components table lists the available components in [Your Web UI Framework/Library Name], along with their corresponding import keys and descriptions:

| Component    | Import Key | Description                                              |
|--------------|------------|----------------------------------------------------------|
| all        | c=all          |  all Component                |
| Alert        | c=a          | Component for displaying alerts/messages                 |
| Avatar       | c=at         | Component for displaying user avatars                    |
| Breadcrumbs  | c=bc         | Navigation trail indicating the current page's location |
| Button       | c=b          | UI button component                                      |
| Clipboard    | c=cb         | Copy to clipboard functionality                          |
| Collapsible  | c=c          | Component for creating collapsible sections              |
| Dialog       | c=dl         | Modal dialog component                                   |
| Dropdown     | c=d          | Dropdown/select component                                |
| Image        | c=i          | Component for displaying images                          |
| Loader       | c=l          | Loading indicator component                              |
| Pagination   | c=p          | Pagination component for navigating through data         |
| Pop Title    | c=pt         | Popup title component                                    |
| Table        | c=t          | Table component for displaying tabular data              |
| Tabs         | c=tb         | Tabs component for organizing content                    |
| Tabstack     | c=tk         | Tabstack component for organizing multiple tabs          |



## Form 



| Component    | Import Key | Description                                |
|--------------|------------|--------------------------------------------|
| all     | f=all        | all input component                   |
| Checkbox     | f=c        | Checkbox input component                   |
| Input        | f=i        | Text input component                       |
| Progress     | f=p        | Progress bar component                     |
| Radio        | f=r        | Radio button input component               |
| Range        | f=rg       | Range/slider input component               |
| Select       | f=s        | Select dropdown input component            |
| Textarea     | f=t        | Textarea input component                   |
