# Home

## SSE Order Tracker
The bookmarklet linked below is an easy way to track your open SSE orders. Just drag it to you bookmark menu or bookmark bar in your preferred web browser. 

<style>
	.bookmarklet {
		display: block;
		width: 200px;
		line-height: 2em;
		font-weight: bold;
		background: rgb(243, 122, 31);
		border-radius: 4px;
		color: #ffffff;
		text-decoration: none;
		margin-left: auto;
		margin-right: auto;
		text-align: center;
	}
</style>

<a class="bookmarklet" href="javascript:(function(){var jsCode=document.createElement('script');jsCode.setAttribute('src','https://rawgit.com/ccgthree/SSEOrderCheck/master/SSEOrderCheck.js');document.body.appendChild(jsCode);setTimeout(function(){doStuff();},500)})();">SSE Tracking</a>

## Using the Bookmarklet
Once you have the bookmarklet saved in your browser's bookmarks, click it. When it runs, it will:
- Ask you for your dealer number: Enter it and click OK.
- Ask you for your ZIP code[1]: Enter it and click OK again.
- Display a link on the screen to the FedEx tracking system. Clicking this link will open the FedEx tracking in a new tab or window.

After you click the link, it will fade from the screen to move itself out of your way.

## Known Bugs and Issues
- Canceling the prompts does not currently work. The script just continues on like you entered some information. This will be fixed in a future update.
- Prompts suck. The window prompts are ugly. Later, I will remove those in favor of a nice, single form. It'll be done at a later date, when I have time.
