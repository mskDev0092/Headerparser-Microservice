
# URL Header Parser Microservice

The Header Parser Microservice project by freeCodeCamp is a Node.js API that can parse the request headers of an HTTP request and return the IP address, preferred language, and software of the client. It is a good project for beginners to practice building microservices, as it is relatively straightforward to implement and passes a variety of tests.

## To build the Header Parser Microservice, you will need to:

> Create a new Node.js project and install the Express.js framework.

> Create a new route that handles GET requests to the /api/whoami endpoint.

> Use the req.ip, req.header('accept-language'), and req.header('user-agent') properties to get the IP address, preferred language, and software of the client.

> Return a JSON object with the ipaddress, language, and software properties set to the extracted information.

> Add error handling to handle invalid requests.

> Once you have implemented the Header Parser Microservice, you can test it by making GET requests to the /api/whoami endpoint. 

> For example, you can use the following request to test the Header Parser Microservice:

http://localhost:3000/api/whoami

> The response would be a JSON object with the following properties:

```JSON
{
  "ipaddress": "127.0.0.1",
  "language": "en-US",
  "software": "curl/7.88.0"
}
```

> You can also test the Header Parser Microservice by making GET requests to the /api/whoami endpoint with different HTTP headers.


## Lessons Learned

The Header Parser Microservice project is a good way to practice building microservices and learn how to use the Express.js framework. It is also a good way to learn about how to parse HTTP request headers in JavaScript.



## Screenshots

![App Screenshot](https://github.com/mskDev0092/Headerparser-Microservice/blob/main/Screenshot%202023-09-23%20at%2001-31-14%20Request%20Header%20Parser.png)


## Run Locally

Clone the project

```bash
  git clone https://github.com/mskDev0092/Headerparser-Microservice
```

Go to the project directory

```bash
  cd Headerparser-Microservice
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Tech Stack

**Client:** HTML, CSS

**Server:** Node, Express


## Usage/Examples

The Header Parser Microservice can be used in a variety of ways. For example, you could use it to:

> Get the IP address, preferred language, and software of the client to personalize the user experience.

> Get the IP address of the client to block or allow access to certain parts of your website or API.

> Get the preferred language of the client to translate your website or API into their language.

> Get the software of the client to troubleshoot problems or detect fraud.

> The Header Parser Microservice is a simple but useful tool that can be used to parse HTTP request headers and extract valuable information about the client.


## Authors

- [Shehzad Khan](https://github.com/mskDev0092)


## Feedback

If you have any feedback, please reach out to us at [linkedin](https://www.linkedin.com/in/shehzad-khan-3ab41b235)

