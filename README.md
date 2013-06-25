_Fork of Android Volley networking library, supplied by Google._

Original : https://android.googlesource.com/platform/frameworks/volley/

Modifications
=============
* Allow NetworkImageView to specify a target width and height. Scaleup the downloaded image if it is smaller than the target dimensions.
* Don't treat HTTP status codes < 500 as request errors. Assume 4xx status codes will be handled on the client side in the response callback.
