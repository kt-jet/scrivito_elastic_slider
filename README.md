# Scrivito Elastic Slider

This Gem adds an Elastic Slider Widget to [Scrivito](http://scrivito.com).

## Prerequisites

When used with scrivito_sdk version 0.18.1 please make sure you have the following in your App already:
- ObjClass Image (migration, model)
- ObjClass Widget (migration, model)
- at least one ObjClass that has a an attribute with type :widget

Newer versions of the scrivito_sdk already provide some of these things.

Use Bootstrap 3.2 in your Rails App.

## Installation

Add the gem to your Gemfile:

    gem 'scrivito_elastic_slider'

Run bundle

    $ bundle

(Currently you need to download the gem's files from github and install it locally.)

Add this line to your app/assets/stylesheets/application.css:

    *= require scrivito_elastic_slider/application

Run

    $ rake scrivito:migrate:install
    $ rake scrivito:migrate

Switch to your Workspace 'rtc' and follow below Steps for Usage. If you are happy with the outcome run

    $ rake scrivito:migrate:publish


## Steps for Usage

- Insert the Widget 'Elastic Slider' and put several 'Image Panels for Elastic Slider' into it. 
- Edit each Panel's Widget Properties to set Image, Headline, Button Text and Button Link or use inline editing.
- Switch into 'Preview' mode to see the Slider in action.

