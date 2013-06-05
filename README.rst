This is a fork of Carl's form utils.

I Changed ImageWidget to play nicely with Amazon S3.
Please note that it's a hacky solution, which only aimed at making the
fallback thumbnail work, and probably breaks the thumbnail-generating
functions. I didn't bother with tests because I couldn't run the tests,
seeing as they were not backward-compatible to django 1.4.x.
