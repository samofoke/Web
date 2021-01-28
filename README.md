# Web

### An intro to web development
    
  * The connection between the broswer based when you click and get a 
    request, we have the web page the ISP and the DNS. When we get the
    IP address to access web server of that website which contain HTML,
    CSS and Javascript.
  * The chrome Dev tools help in terms of understanding the functions of
    of the website, we can even use traceroute - print the route packets trace to network host.

### An overview of a Full Stack Dev

  * a summary of full stack
  
    ~~~
    --> front-end                       back-end

        HTML                            Server [Node.js, Express.js]
        CSS                          
        javascript + (Frameworks)       Database [PostgreSQL, MongoDb]
    ~~~

### HTML Structure
  
  * is the standard markup language for documents designed to be displayed 
    in a web browser. Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document. 

    ~~~
    <!DOCTYPE html>
    <html>
      <head>

        <title></title>
      </head>

      <body>
        <a href="">next page</a> "an anchor tag to link page"
        <h1></h1> "The <h1> to <h6> tags are used to define HTML headings.
        <h1> defines the most important heading. <h6> defines the least important heading."
        <p></p> "this is for paragraphs"
        <strong></strong> "this for creating bold in your paragraph"
        <em><em> "this for italics also known as emphasis"
        <ol></ol> "an ordered list tag"
        <ul> "this is a unordered list"
          <li></li> "this is a nested list"
        </ul>
      </body>
    </html>
    
    --> This is the basic of an html page
      --> it is supported by all broswer available today.
    --> A body is a tag and h1 is an element inside  the body tag. 
    ~~~
  * "Semantic HTML is the use of HTML markup to reinforce the semantics,
    or meaning, of the information in webpages and web applications rather than merely to define its presentation or look."
  * we have self closing tags like for example: <br> <img> in this tag we 
    we can have attributes sr="" width="" height="".