# CP3402-Learning-Journal-Week_7

## Learning Activities & Resources

* [Free Code Camp Youtube Video For Creating Custom WordPress Themes](https://itatjcu.slack.com/archives/G0WDN6M4H/p1742104985641549)
* [WPZOOM Custom WordPress Theme Tutorial](https://www.wpzoom.com/blog/how-to-create-wordpress-theme/)
* [W3 Schools PHP Tutorial](https://www.w3schools.com/php/default.asp)
* [BrowserStack PHP Tutorial](https://www.browserstack.com/guide/php-web-development)

## Estimated Hours
I spent approximately 3 hours completing various learning activities for CP3402 this week. 

## Content Insights
This week I had two main areas of focus for content including creating custom WordPress themes and using PHP to enhance websites. When beginning to develop custom themes in WordPress I learnt that starter themes such as underscores allow for complete customisation of the site whilst providing a basic structure and key components of the site. This allows the focus to be placed on designing the site to reflect the clients' needs rather than spending the majority of the development timeframe preparing the basic structure. 

Alternately, when working with PHP I learnt that the construct include ` <?php include( "inc_header.php" ); ?> ` can be used in order to add sections of code to multiple files. For example, adding the same header and footer to all pages of the site without including the code on every page. This increases the efficiency of the site and allows for more dynamic development as changes made can be easily tested across the site from a single file. Additionally, the construct echo can be used in order to seamlessly integrated PHP and html into the same line. This allows dynamic PHP performance, such as if statements to be used within html content. Overall, this increases the flexibility of standard html programming with the incorporation of more data control and dynamic site behaviour that is otherwise not able to be achieved. 

## Career/Employability/Learning Insights
This week rather than trying to learn the overall structure and details of the PHP language I reviewed the types of changes that PHP can make to a website and began designing a basic site. This allowed me to apply my general programming knowledge and understanding to the language and research specific terms or techniques as required to learn project-specific skills rather than the language as a whole. I found this technique more closely reflected industry behaviour where I am not guaranteed to be working in a position only using languages I have extensively used and therefore will need to apply a basic understanding to quickly learn and apply new skills. This practice also allowed me to reflect on my previous learnings on program structure that allowed me to adjust and integrate PHP comfortably.

## Documentation example from Seminar
### Adding a new page to the header.
* Clone the [advice shop repository](https://github.com/lindsaymarkward/theadviceshop) to your prefered development platform. See *other documentation* for setting this up.
* Create a new branch named *New  Feature Description* 
* Navigate to the inc_nav.php file
* Add a new list element with the details of the new page
     *   ` <li <?php if ($name == "index") echo 'class="current"'; ?>><a href="page file name"><span class="glyphicon glyphicon-home"></span> Home</a></li> `
* Commit the changes to the new branch
* Test this version of the program in a local development environment 
* Publish the branch
* Open a pull request to merge changes of this branch into main