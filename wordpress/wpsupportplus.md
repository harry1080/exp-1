sql inject in wordpress plugin wp-support-plus-responsive-ticket-system.
https://wordpress.org/plugins/wp-support-plus-responsive-ticket-system/



there are two sql injects,one in the cookie value email and another in the post parameter "filter[order_by]".

there is a picture for the test of the official website of responsive-ticket-system.
![Aaron Swartz](wp.png)

the cookie is base64 encoded,a php serialized object.
and the parameter email in cookie was inject.

the post parameter "filter[order_by]" was inject too but is blind.

the issuse fixed in the version 9.0.3 and after.

00theway from 360sglab(360观星实验室)
