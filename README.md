#Twitter
####MassFollow

1. Open any user Follow list like mine [https://twitter.com/pierre_co/followers](https://twitter.com/pierre_co/followers)
2. Copy this javascript, paste on console box CMD + ALT + J (Mac) and press enter 

```javascript
javascript:var inputs = document.getElementsByClassName('button-text follow-text'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

####MassUnfavorite

1. Open [https://twitter.com/favorites](https://twitter.com/favorites)
2. Copy this javascript, paste on console box CMD + ALT + J (Mac) and press enter 
3. Refresh your page and repeat


```javascript
javascript:var inputs = document.getElementsByClassName('ProfileTweet-actionButtonUndo js-actionFavorite'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

####MassFavorite

1. Open [https://twitter.com/search-home](https://twitter.com/search-home)
2. Write your hashtag keywords and press Enter
3. Click to "Direct" and scrol down
4. Copy this javascript, paste on console box CMD + ALT + J (Mac) and press enter 

```javascript
javascript:var inputs = document.getElementsByClassName('ProfileTweet-actionButton js-actionButton js-actionFavorite'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

###Tools

#####Unfollow users not following you with interface
[https://toolset.co/twitter/unfollow/](https://toolset.co/twitter/unfollow/)


#####Copy follower of a user with interface
[https://toolset.co/twitter/follow/copy-follow/](https://toolset.co/twitter/follow/copy-follow/)

#Facebook
####Add all suggested friends

1. Open [https://www.facebook.com/friends/requests/](https://www.facebook.com/friends/requests/)
2. Copy this javascript, paste on console box CMD + ALT + J (Mac) and press enter 

```javascript
for( i = 1;i<document.getElementsByClassName("_42ft _4jy0 FriendRequestAdd addButton _4jy3 _517h _51sy").length;i++){
    document.getElementsByClassName("_42ft _4jy0 FriendRequestAdd addButton _4jy3 _517h _51sy")[i].click();
    }
void(0);
```

####Invite All People to Event Page

1. Open event page and select
2. Select the show more friends in the invite friends box
3. Click on the Choose From Your Friends options
4. In the box that opens, click on All Friends
5. Scroll down till all the freinds get loaded
6. Copy this javascript, paste on console box CMD + ALT + J (Mac) and press enter 

```javascript
a = document.getElementsByClassName("_1v32 _1v34");
arr = []
for (var i = 0;i<a.length;i++){
	arr.push(a[i].getAttribute("aria-labelledby").split("-")[0]);}
string = "{";
for (var k = 0;k<arr.length;k++){
	string+="\"";
	string+=arr[k];
	string+="\":1,";}
string = string.slice(0,string.length-1);
string+="}"
document.getElementsByName("profileChooserItems")[0].setAttribute("value",string);
document.getElementsByClassName("_42ft _4jy0 layerConfirm uiOverlayButton _4jy3 _4jy1 selected _51sy")[0].click();
```

