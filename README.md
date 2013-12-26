Launcher3
=========

Launcher3 from Android Open Source Project, corresponding to Android 4.4 KitKat. Eclipse project. 

https://android.googlesource.com/platform/packages/apps/Launcher3/
Last sync'd at daa9dfcbd5865bd25d729f313159f8f8adfd2fcd
On December 25 2013

Eclipse project. BackupProtos.java generated on December 25 2013 using protobuf: 
https://android.googlesource.com/platform/external/protobuf.git
Last sync'd at e7741c064ee4cdc5fa41e6444ed45131672fed97
On December 25 2013

Command to generate your own: 
*protoc --javanano_out=src/ -I protos protos/backup.proto*

Building the protocol buffers project binary and JAR requires GCC and Maven. The one on Google Code doesn't match the one in AOSP. 
