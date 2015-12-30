The goal of the ActionScript 3 mail library is to provide easy access to mail protocols such as SMTP and POP3.

### Progress ###
To keep you informed on the progress being made in the development of this library, I'll try to update this as frequently as possible. Please keep in mind I only have limited time to work on this project.

So far, the following has been done:
  * Stateful SMTP support (EHLO, MAIL, RCPT, DATA, RSET, QUIT)
  * The Internet Message Format ([RFC 2822](http://tools.ietf.org/html/rfc2822)) has been largely implemented
  * Documentation generated for all public classes
  * **Initial import of both the source and documentation has been done, all progress so far is available under [Source](http://code.google.com/p/as3maillib/source/browse/trunk/src/org/oxcode/mail/)**

Next up:
  * Implementation of MIME
  * POP3 support

### Key aspects used in the development of this library ###
  * Standards compliant implementation of the supported protocols ([RFC 1939](http://tools.ietf.org/html/rfc1939), [RFC 2821](http://tools.ietf.org/html/rfc2821) and [RFC 2822](http://tools.ietf.org/html/rfc2822))
  * All code must follow the [ActionScript 3 Coding Conventions](http://opensource.adobe.com/wiki/display/flexsdk/Coding+Conventions) set by Adobe
  * Use of design patterns and OO best practices
  * Documented using the ASDoc tool