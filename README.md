compare-android-string-resources
================================

This tool help you to compare your Android string resources among multiple locales.
Useful if you have many error-prone translators that used to change the resource names (!).

Usage:
./compare-android-string-resources resource_dir

where
"resource_dir" should be the directory where your "values", "values-en", "values-de", "values-fr", ecc... subdirs lives.

The script will make a map of the resource names of the default locale (the one in the values directory) and will calculate the difference among all the other locales.
