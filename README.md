##Twitter
####MassFollow

1. Open any user Follow list like mine [https://twitter.com/pierre_co/followers](https://twitter.com/pierre_co/followers)
2. Copy this javascript ,paste on console box and press enter

```javascript
javascript:var inputs = document.getElementsByClassName('button-text follow-text'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```

####MassUnfavorite

1. Open [https://twitter.com/favorites](https://twitter.com/favorites)
2. Copy this javascript ,paste on console box and press enter
3. Refresh your page and repeat


```javascript
javascript:var inputs = document.getElementsByClassName('ProfileTweet-actionButtonUndo js-actionFavorite'); 
for(var i=0; i<inputs.length;i++) { inputs[i].click(); }
```


##Facebook
####Add all suggested friends

1. Open [https://www.facebook.com/friends/requests/](https://www.facebook.com/friends/requests/)
2. Copy this javascript ,paste on console box and press enter

```javascript
for( i = 1;i<document.getElementsByClassName("_42ft _4jy0 FriendRequestAdd addButton _4jy3 _517h _51sy").length;i++){
    document.getElementsByClassName("_42ft _4jy0 FriendRequestAdd addButton _4jy3 _517h _51sy")[i].click();
    }
void(0);
```

