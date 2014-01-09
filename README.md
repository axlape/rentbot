# Rentbot #

A simple static page for figuring out optimal rent and checking the sanity of rent proposals in my area and present them in a nice webapp.

**Probably not useful for anyone else**

## What?!

This is something I slapped together because we needed to find out what a reasonable rent for Brändö, Vasa, Finland is. We gathered a dataset of about 40 appartments of various sizes and with various features and calculated a simple multivariate regression model based on these. This model is represented in the application as a very suspicious looking array called b full of magic numbers (the regression parameters for: `y=BX+a`)
