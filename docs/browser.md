# Integrate GO Links into your Browser search bar
You could integation GO Link search directly into your browsers's search bar

## See it in action
Watch [this video](https://drive.google.com/open?id=1fGbVet3kzHQEfQ4gCEfJoGv1VX9xHgz4&authuser=ttam%40splunk.com&usp=drive_fs) on how it works. 

## Configure your browsers
1. Open your browser preference (this example is for Chrome)
1. Find the preference for 'Manage search engines' and open the preference
1. Click on **Add**
1. In the Add search engine dialog
   1. Enter `Go Links` into **Search engine** 
   1. Enter `go` into **Keyword** 
   1. Enter `https://beta.go.splunk.com/?q=%s` into **URL with %s in place of query** 
1. Save   
![](golinks-search-setting.png)

## Testing that it works
1. Go into your browser's search bar
1. Type `go` follow by **TAB**
1. You should see **Search GO Links**
1. Type the keyword `okr` and **RETURN**
1. Your browser should be searching GO links at `https://beta.go.splunk.com/?q=okr`

## A demo video for your reference
<iframe src="https://drive.google.com/file/d/1fGbVet3kzHQEfQ4gCEfJoGv1VX9xHgz4/preview" width="960" height="540"></iframe>