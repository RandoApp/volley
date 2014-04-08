Volley
----------

###About

This is a patched version of google android volley framework.
Patch includes custom priority for ImageLoader. For example:

```
new ImageLoader(mRequestQueue, mCache).get("your image", Request.Priority.HIGH, ImageLoader.getImageListener(view, defaultImageResId, errorImageResId); 
```

