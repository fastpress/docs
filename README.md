# fastpress\doc

[![Join the chat at https://gitter.im/fastpress/fastpress](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fastpress/fastpress?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## What is it? 
As the name suggests, it's a *fast* and simple PHP blogging app created mainly for developers. 
You can use fastpress to publish your github pages, or run simple vanilla php blog. 

#### Using Github pages
This solution involves integrating your github pages to publish the content in your site using fastpress. 

##### Using Database 
This is the simple wordpress-esque way to publish your blogs. Just log in to your fastpress app, and start blogging. 

## Features: 
 - Fastpress uses `prism.js` for syntax hightlighting (over 50 languages)
 - Font-awesome and bootstrap for easier front-end customization 
 - Disqus for commenting. (optional vanilla php comment feature)
 - Multipe user accounts for authoring blogs
 - Fetch/order blogs by unique tags, dates and authors
 - *editable* blogs by visitors, edits then are sent as PR to your github account. 
 - log in with github/twitter to comment. 
 - easily embed gists and tweets into your blog post

## Collaboration
Anyone is welcome to contribute.

Use [semantic versioning](http://semver.org/) when tagging releases.

## Code: convensions / standards

- Follow the [PSR-2 coding style guide](http://www.php-fig.org/psr/psr-2/)fPHP/PHP-CS-Fixer) 
- Follow the [PSR-4 autoloader standard](http://www.php-fig.org/psr/psr-4/)
- Use [Composer](https://getcomposer.org/) to manage dependencies and offer our projects as libraries
- Use unit testing
- Write tests for PHPunit, ideally before even writing the functionality
- Use the free [Travis-CI](https://travis-ci.org/) service to report on build/test status
