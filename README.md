# Otago University Posters  

Reproducible Poster within R Markdown and R-Stuido  
Using Brent Thornes Base Posters and converting to Otago University fonts, logos and formats

https://github.com/brentthorne/posterdown

pdf version
https://github.com/Shedimus/EACR_posterdown

ggplot colours
https://github.com/thoughtfulbloke/theme_otago

## Install
To install the package and template for the posters use 

```r

devtools::install_github("brentthorne/posterdown")

```  

Full instructions are at [Brent's github](https://github.com/brentthorne/posterdown) repo including all the options for changing font size and other settings.

Use the **File / New File / R Markdown.. / From Template / Posterdown HTML**  or **Posterdown BetterLand** or **Posterdown BetterPort** dialog pathway to create the template poster.

in the console
**rmarkdown::draft(file = "mydraft.Rmd", template = "posterdown_betterland", package = "posterdown", create_dir=FALSE)**

*As of February 2020 settings need to be changed in the header of the .Rmd Document that is created. The goal will be to create a full Otago University Template to install and run with the appropriate colours and logos embeded.*

## Otago Settings

Fonts:
https://www.otago.ac.nz/webservices/guides/designers/styles/otago049670.html

font-family: 'Open sans', Helvetica, Arial, Geneva, sans-serif;

University logo: http://www.otago.ac.nz/ou-logo.png

Colours:
https://www.otago.ac.nz/webservices/guides/designers/styles/otago049840.html

Otago Blue: #00508F  
Links: #416EBF  
Light blue: #F1F4F8  
Body text: #333333  
Grey: #DDDDDD  
Light grey: #F5F5F5  
Otago Yellow: #F9C000  


