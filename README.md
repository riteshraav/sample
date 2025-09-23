# This read me file


1) Flutter Errors:
Exception in thread "main" java.util.zip.ZipException: zip END header not found at java.base/java.util.zip.ZipFile$Source.findEND(Unknown Source) at java.base/java.util.zip.ZipFile$Source.initCEN(Unknown Source) at java.base/java.util.zip.ZipFile$Source.<init>(Unknown Source) at java.base/java.util.zip.ZipFile$Source.get(Unknown Source) at java.base/java.util.zip.ZipFile$CleanableResource.<init>(Unknown Source) at java.base/java.util.zip.ZipFile.<init>(Unknown Source) at java.base/java.util.zip.ZipFile.<init>(Unknown Source) at java.base/java.util.zip.ZipFile.<init>(Unknown Source)
 solution => in flutter project open terminal and goto android folder and runt "./gradlew build"
