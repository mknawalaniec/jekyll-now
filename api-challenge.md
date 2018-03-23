---
layout: api-page
title: API Challenge
permalink: /api-challenge/
---

Use the Spotify API to complete the next challenge!

### How does the Spotify API work?
A website address usually looks something like: 
<a href="https://www.spotify.com/us/"></a>

You can use the Spotify API to get information about songs, albumbs, artists, and more. 

For example:

I want to search Spotify for the song called *Run the World*. So, know I have to figure out what my URL should be to request the right information from Spotify. 

This is the URL every search request will start with:
https://api.spotify.com/v1/search

Let's tell Spotify the title of the song we're looking for:
https://api.spotify.com/v1/search **?q=Run%20the%20World**

Let's tell Spotify that we are searching for a track:
https://api.spotify.com/v1/search?q=Run%20the%20World **&type=track**

*each time we want to add detail to our search, we use **"&"***

Let's tell Spotify that we only want songs from the United States:
https://api.spotify.com/v1/search?q=Run%20the%20World&type=track **&market=US**

Our final URL that we will use for our search is:
https://api.spotify.com/v1/search?q=Run%20the%20World&type=track&market=US

Click the button below to see what information you get from the search:



### Let's Get To Work!

Click the link below to begin. 

<a href="http://localhost:8888/" target="_blank">Start Challenge</a>

### What is the popularity number of the song you just found?
