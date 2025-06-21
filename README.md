# HTMX-Django
Learn how to use HTMX with a Django Backend. 

1. What is HTMX?
    -Is a javascript library that allows as to make dynamic and interactive web applications.
    -It requires little to no JavaScript
    -It uses a Hypermedia driven approach to build applications - This means the exchange of Hypermedia between the browser and the server using HTTP
    to control the UI and interactivity of an application.
    -It contains a set of Hypermedia controls like hyperlinks and forms
    -HTMX adds additional attributes to the regular HTML inorder to interact with the server, therefore making it a hypermedia control. 
2. Extends the hypermedia interface to any HTML tag:
    - Dynamically replace content at any tag point based on events
    - Use HTML snippets from the server as inline replacements

3. HTMX & Django
    - HTMX & Django fot very nicely together
    - htmx brings more dynamism to a page without needing heavier frameworks
    - Use the template engine to render parts of pages
    - Headers indicate when a view is involved by HTMX

4. HTMX attributes
    - hx-get = for search requests(HTTP GET)
    - hx-post = for form submission(HTTP POST)
    - hx-delete = for deleting items(HTTP DELETE)
    - hx-trigger = what event/action triggers the HTMX request to the server
    - hx-target = to specify where response content from the server should go
    - hx-swap = how does the reponse content enter the DOM in relation to the target
    - hx-indicator = what should be shown while waiting for a response from the server(in-flight)
    - hx-confirm = for action confirmation(example: deleting items)
    - hx-on = for DOM scripting and reacting to events
    - hx-encoding = to switch the request encoding , for example when uploading files.
    - hx-headers = for adding HTTP headers to the request.
