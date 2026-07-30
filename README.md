# bv-reel-media

A public mirror of rendered reels, and nothing else.

Instagram's Content Publishing API does not accept a file upload — you hand it a `video_url` and
Meta's own servers download the video, sending no credentials. So each mp4 has to be publicly
reachable for the couple of minutes Instagram spends fetching and transcoding it. That is the only
reason this repo exists.

Pushed from `BV reels/` alongside `ig-post.js`. Every file here is a reel being posted publicly to
Instagram anyway, so nothing is exposed that was not already going out.

Safe to delete once the queue is posted. Deleting it does not affect anything already live —
Instagram keeps its own copy after the fetch.
