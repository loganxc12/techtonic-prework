Basic Internet Terminology And Understanding
============================================

Internet
------------
    * A very large network of computers connected to each other. 
    * Like a road network - no actual center:
        * Cables = "roads", computers = "houses", information = "cars"
    * Invented in 1969.

    * Usually, a connection on the internet takes place between 2 computers only:
        1. Server - HAS the information; where info is stored, sole purpose is to DELIVER CONTENT.
        2. Client - WANTS the information; program that can take many forms: web browser, email, client, messenger app, video streaming service... 

IP Address 
------------
    * A combination of numbers (like 91.198.174.192) which acts like a UNIQIUE IDETIFIER for a computer connected to the Internet.
    * Hard to read for humans, so domains were created...

Domains 
------------
    * Text which acts as a unique identifier for a computer connected to the Internet. 
    * Associate an IP address with a string of text, interchangable: 
        * https://91.198.174.192 === https://wikipedia.com
    * Made of 3 parts, read right to left: 
        1. Top Level Domain (TLD) - .com, .net, .org, .us, .fr etc.
        2. Domain Name - wikipedia, facebook etc. Can include letters and numbers but no space or dot.
        3. Subdomain - Optional, most websites use www.
    * Can't buy domains, only rent them from domain registrars. 

Protocol
------------
    * A set of rules, like a language, in which computers communicate with each other:
        * FTP - file transfer.
        * SMTP - sending emails.
        * IMAP - receiving emails.
        * IRC - chat.
        * HTTP - browsing HTML documents (webpages); protocol with which computers share webpages between each other.

URLS
------------
    * Uniform Resource Locator - web address for an online resource; unique and defines where to find something on the internet and how the computer is supposed to read it, made of 3 basic parts: 
        1. Protocol (https://) - declares how web browser should communicate with a web server when sending or fetching a web page. 
        2. Domain - wikipedia.com
        3. Path (/cheese.html) - typically refers to a file or directory on the web server.
    // More Parts - from "Anatomy of a URL" //
        4. Port (:80) - rarely visible in URLS but always required, when declare in URL it comes right after the TLD, seperated by a colon.
        5. Query (?) - commonly found in the URL of dynamic pages; represented by a question mark followed by one or more parameters.
        6. Parameters - snippets of information found in the query string of a URL, follow question mark and are seperated by &
        7. Fragment - Internal page reference/named anchor, usually appears at the end of a URL and begins with a hash(#) followed by an identifier that refers to a section within a web page. 

    * Example URL: https://video.google.com:80/videoplay?docid=73543#00h02m30s

THE WEB
------------
    * WEB - One part of the internet, the part where web pages are shared useing the HTTP protocol.
    * WEBPAGE - A document written in HTML, shared accross the web.
    * WEBSITE - A collection of web pages located on the same domain.
    * WEB BROWSER - A program that can OPEN web pages (html documents) in order to display them; interprets source code. 
    * TEXT EDITOR - A program that can CREATE web pages (html documents); sees source code.
