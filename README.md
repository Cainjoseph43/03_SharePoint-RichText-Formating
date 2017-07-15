# 03_SharePoint-RichText-Formating
## Demo and M code function for dealing with Rich Text results from a direct SharePoint connection with PowerQuery and PowerBI<br>
<br>
Have you ever had to connect to a SharePoint list or library which has a Rich Text comment field? <br>
<img 
	alt="RichText as seen in SP" 
	src="https://github.com/TheDataMinersUnion/03_SharePoint-RichText-Formating/blob/master/SP%20RichText%20Snap.jpg" 
	style="width:128px;height:128px;"
/>
Then I am sure you have noticed how the direct PQ/PBI Queries maintain the HTML tags in the results: <br>
<img 
	alt="RichText as in PQ/PBI" 
	src="https://github.com/TheDataMinersUnion/03_SharePoint-RichText-Formating/blob/master/PQ-PBI%20Rich%20Text%20Snap.jpg" 
	style="width:128px;height:128px;"
/>
and I also assume you have exported that same list/library to Excel and noticed that the same rich text fields are much easier to read: <br>
<img 
	alt="RichText as see in Excel Export" 
	src="https://github.com/TheDataMinersUnion/03_SharePoint-RichText-Formating/blob/master/Excel%20RichText%20Snap.jpg" 
	style="width:128px;height:128px;"
/>

If you are like me there must be times when you would LOVE to strip out the HTML tags from the direct Query results and display the text in a simpler way (Similar to how an excel export does) for use in some of your PowerQuery/PowerBI reports.<br>
<br>
<h1>Well great news!</h1> this is exactly what we accomplish with a "simple" custom M function included in the sample files.<br>
Feel free to check out my <a href="https://www.youtube.com/channel/UCxZ-mXY87mHC08QgVbezWEw">YouTube Video</a> for tips.
