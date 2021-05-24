
<br>

#### **Hugo Lithium (theme) of R blogdown for Fitbit Visualizations**

<br>

* There were a [few changes](https://stackoverflow.com/a/43505891/8302386) compared to the [initial hugo-lithium-theme](https://github.com/jrutheiser/hugo-lithium-theme)

* I modified the [main.css 'img'](https://github.com/mlampros/fitbitVizBlog/blob/master/themes/hugo-lithium/static/css/main.css#L32-L34) and [main.css 'content'](https://github.com/mlampros/fitbitVizBlog/blob/master/themes/hugo-lithium/static/css/main.css#L97-L98) to increase the wide of the plots in the output website.

* For more details on how to setup a similar website take a look to the [README.md file of the fitbitViz](https://github.com/mlampros/fitbitViz#keep-track-of-your-activities-using-fitbitviz-blogdown-and-github-actions) R package

<br>

##### **Frequent issues when running the [gh_fitbit_blog.yaml](https://github.com/mlampros/fitbitVizBlog/blob/master/.github/workflows/gh_fitbit_blog.yaml) file:**

<br>

* `Fatal error: cannot open file 'R_templates/data_template.R': No such file or directory`
    * *You have to 'Re-run' the github actions workflow*

* `Error in content_list_obj$sleep[[1]] : subscript out of bounds  Calls: <Anonymous> -> sleep_single_day`
    * *You haven't updated the Fitbit data in your account! Connect to the application to upload the recent data for this Date*
    
<br>
