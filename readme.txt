=== S3 Media Storage ===
Contributors: Cleancoded
Tags: S3, media, images
Requires at least: 3.0
Tested up to: 5.5
Stable tag: 1.0

S3 Media Storage WordPress Plugin

== Description ==

Store media library contents onto S3 without cron jobs. This is more ideal for multiple web server environments. Because of the logic surrounding
WordPress media uploads and the availability/order in which hooks/actions surrounding media uploading, we cannot get away from temporarily storing
the uploaded file in the uploads directory. What this plugin will be able to do is to take that uploaded file, move it to S3, and delete the local
uploaded file all in the same request.

== Features ==
* Store and serve media easily from Amazon S3
* Send files to S3 using SSL
* Serve files from HTTP/HTTPS/according to page requested protocol
* Set far reaching expires for your assets
* Amazon CloudFront support
* Deleting from S3 is optional (price concern for some)
* No additional database tables needed

== Installation ==

Upload the S3 Media Storage plugin to your blog, activate it, then enter your S3 details. Ensure that you have cURL PHP extension installed.

== Changelog ==
= 1.0 =
* Initial Codebase
