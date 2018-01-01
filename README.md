[![Build Status](https://travis-ci.org/RandoApp/volley.svg?branch=master)](https://travis-ci.org/RandoApp/volley)

### Volley

Volley is an HTTP library that makes networking for Android apps easier and, most
importantly, faster.

For more information about Volley and how to use it, visit the [Android developer training
page](https://developer.android.com/training/volley/index.html).

###About this fork

This is a patched version of google android volley framework.
Patch includes custom priority for ImageLoader. For example:

```
new ImageLoader(mRequestQueue, mCache).get("your image", Request.Priority.HIGH, ImageLoader.getImageListener(view, defaultImageResId, errorImageResId); 
```

Also all dependencies on HttpClient has been removed.