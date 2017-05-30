# NewRocket's Best Practices

## Table of Contents

  1. [General Best Practices](#general)

## General 

  <a name="general"></a><a name="BP1.1"></a>
  - [BP1.1](#general) **Dynamnic Panels**: Every widget containing a panel should be dynamic via options.color and options.title, make sure that these show up in instance options. 
  - [BP1.2](#general) **Restrict use of CSS**: Use as little CSS as possible. 
  - [BP1.3](#general) **Exporting Widgets**: Never export a widget from a list view. When exporting a widget always do so from the widget record itself. Use the hamburger menu select export from the dropdown menu and then click export xml (this record)
  - [BP1.4](#general) **Embedding Widgets**: When embedding a widget use sp-widget and pass it in scope as opposed to <widget/> with is automatic