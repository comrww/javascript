# NewRocket's Best Practices

## Table of Contents

  1. [General Best Practices](#general)

## General 

  <a name="general"></a><a name="BP1.1"></a>
  - [BP1.1](#general) **Dynamnic Panels**: Every widget containing a panel should be dynamic via options.color and options.title, make sure that these show up in instance options. 
  - [BP1.2](#general) **Restrict use of CSS**: Use as little CSS as possible. 
  - [BP1.3](#general) **Exporting Widgets**: Never export a widget from a list view. When exporting a widget always do so from the widget record itself. Use the hamburger menu select export from the dropdown menu and then click export xml (this record)
  - [BP1.4](#general) **Embedding Widgets**: When embedding a widget use sp-widget and pass it in scope as opposed to using widget which automatically embeds widgets. 
 - [BP1.5](#general) **Creating a Tabbed View**: When creating a tabbed view make sure to use the semantic Bootstrap process as outlined in the example below
 ```HTML
<!-- Nav tabs -->
  <ul class="nav nav-tabs" role="tablist">
    <li role="presentation" class="active"><a href="javascript:void(0)" data-target="#home" aria-controls="home" role="tab" data-toggle="tab">Home</a></li>
    <li role="presentation"><a href="javascript:void(0)" data-target="#profile" aria-controls="profile" role="tab" data-toggle="tab">Profile</a></li>
    <li role="presentation"><a href="javascript:void(0)" data-target="#messages" aria-controls="messages" role="tab" data-toggle="tab">Messages</a></li>
    <li role="presentation"><a href="javascript:void(0)" data-target="#settings" aria-controls="settings" role="tab" data-toggle="tab">Settings</a></li>
  </ul>

  <!-- Tab panes -->
  <div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="home"><sp-widget widget="data.formWidget"></sp-widget></div>
    <div role="tabpanel" class="tab-pane" id="profile">2</div>
    <div role="tabpanel" class="tab-pane" id="messages">3</div>
    <div role="tabpanel" class="tab-pane" id="settings">4</div>
  </div>
```