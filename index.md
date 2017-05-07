# SSE Order Tracker

The bookmarklet linked below is an easy way to track your open SSE orders. Just drag it to you bookmark menu or bookmark bar in your preferred web browser. When you click it, it will ask you for your dealer number. Enter it and then click OK. Then, it will ask for your ZIP code. Enter it also and then click OK.

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

<a class="bookmarklet" href="javascript:(function(){var jsCode=document.createElement('script');jsCode.setAttribute('src','https://rawgit.com/ccgthree/SSEOrderCheck/master/SSEOrderCheckLinkTest.js');document.body.appendChild(jsCode);setTimeout(function(){doStuff();},500)})();">SSE Tracking</a>
