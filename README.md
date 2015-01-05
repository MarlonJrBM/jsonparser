jsonparser
==========

Helpful methods for dealing with JSON requests in Android

-  JSONArray getJSONArrayFromUrl(String url)
-  JSONObject getJSONObjectFromUrl(String url)
-  String getJSONStringFromUrl(String url)

Names are pretty self-explanatory. Use first method if you're expecting a JSONArray (more than one json entry), the second
one if you're expecting just one object, and the third one if you just want a string representation (be it a JSONArray or JSONObject)
