# Reading Assignment 13

>## Local Storage
>
>Native clients can store information in a registry, INI files, XML, or if more storage is needed, you can embed the database or invent a new file format. Web applications don't have that ability so cookies were invented early on to store small amounts of information. The negative part about them is they slow down your application, the information sent is repetitive, and unencrypted. 
>
>When Microsoft invente IE they included something called *DHTML Behaviors*, one of which was called `userData`. This particular one could hold 64 KB of data per domain, stored as an XML-based structure. 
>
>Adobe created what was unfortunately known as flash cookies, which could store 100 KB of data. Then Brad Nueberg created AMASS (Ajax Massive Stoage System), a flash-js bridge. The design limited its capabilities, so in 2006 he rewrote AMASS integrating a Dojo Toolkit known as `dojox.storage`. This new AMASS gave each domain 100 KB of storage FREE.
>
>Google released Gears in 2007 as an open source plugin that was intended to provide more capabilities to the browser after getting permission from the user, once.
>
>HTML 5 storage allows users to storage local data in the client web browser. Even if you navigate away from the web page, close the browser, the datat remains stored and is not transmitted to a remote server. The data is stored as named key/value pairs, a string, and accessed the same way. You can store up to 5 MB for each origin, once you exceed the space allowed you will get a `quota_exceeded_err`. Unlike AMASS, you cannot ask for more storage.

<br/>

## Things I want to know more about...

>SQL. I see and yet I don't see its purpose and capabilities.