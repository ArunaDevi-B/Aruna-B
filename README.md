Write a blog on Difference between HTTP1.1 vs HTTP2                                                                                                                    Answer: HTTP stands for HyperText Transfer Protocol which is a set of rules that runs on top of the TCP/IP suite of protocols and defines how files are to be transferred between clients and servers on the world wide web.                                                                                                                      i) HTTP1 loads a single request for every TCP connection, while HTTP2 avoids network delay by using multiplexing.                                                      ii) HTTP2 is much faster and more reliable than HTTP1                                                                                                                 iii) In HTTP/1, for every TCP connection there is only one request and one response, whereas HTTP/2 uses multiplexing, where over a single TCP connection resources to be delivered are interleaved and arrive at the client almost at the same time. It is done using streams which can be prioritized, can have dependencies and individual flow control. It also provides a feature called server push that allows the server to send data that the client will need but has not yet requested.                        iv) HTTP/1 can define 16 status codes; the error prompt is not specific enough, whereas underlying semantics of HTTP such as headers, status codes remains the same in HTTP/2. 
Write a blog about objects and its internal representation in Javascript.                                                                                           Answer: Objects are having enormous applications. Objects in JS may be defined as an unordered collection of data which is of primitive or reference type in a form of key:value pair. Example:Objects can be represented as ------> {"name":"Aruna", "dob":"DDMMYYYY", "gender":"Female"}------->For example: To print the value of the key, 1st we have to assign the variable----->let student={"name":"Aruna", "dob":"DDMMYYYY", "gender":"Female"} To access the value of the key we have two methods----i)(DOT Method) console.log(student.name); -which is console.log(objectname.keyname)----ii) console.log(student["name"]); -- which is console.log(objectname["keyname"]). 
