# Clarify
JSON parser for Spotify userdata interpretation, written in Python. This was written a few years back, and was originally intended to be a more ambitious project that had a website, Deezer/Spotify API integration, and essentially served as a third-party "wrapped" that is accessible all year round! I never got around to it, unfortunately...


# How to Use
You can get the JSONs this script parses from Spotify by requesting your user data on the Spotify website. I believe both past-year and lifetime data requests are compatible! You will find the array target_jsons at the bottom of the script. By default, it contains one target, ./StreamingHistory0.py. This script was designed with scalability in mind, if you have more jsons (you likely will), feel free to add them to the array. It is recommended to order the array chronologically.
