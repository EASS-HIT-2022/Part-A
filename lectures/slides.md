---
header-includes:
  - \usepackage{upgreek}
  - \usepackage{txfonts}
  - \usepackage{mathtools}
  - \usepackage{braket}
  - \usepackage{amsmath}
  - \usepackage{multicol}
  - \usepackage{xcolor}
  - \usepackage{gensymb}
  - \usepackage[utf8]{inputenc}

fontsize: 8pt
interlinespace: 4ex
whitespace: small
title: Engineering of Advanced Software Solutions (EASS)
author: Yossi Eliaz
subtitle: HIT, Israel
date: "2022"
---


# EASS 2022 - Lecture 1
:::::::::::::: {.columns}
::: {.column width="50%"}
- Admin
- Technical debt
- Business logic
- Bash and commandline (based on MIT's missing semester)
- Git, GitHub
- Interactive class

:::
::: {.column width="50%"}
<!-- ![](static\\review.png){ height=400px } -->
![](static\eass_logo.PNG){ width=150px }
:::
::::::::::::::

# Admin stuff
:::::::::::::: {.columns}
::: {.column width="50%"}
- Discord
- Github account
- HW on Github
- Creating a Canvas account (https://canvas.instructure.com/)
- Accepted invitation from AWS Academy and GitHub (I have sent links)
- AWS on Cavnvas
- LinkedIn
- Commandline (WSL)
- Docker
- Moodle (minimal interaction over there)
- Volunteer to summarize the lectures
- Stackoverflow
- Engagment on Discord
- Hackernews

:::
::: {.column width="50%"}

:::
::::::::::::::

###### References:
*Missing Semester MIT*

*AWS cloud certificate*


# What is Technical Debt?
- "In software development, there is always a constant need to balance speed and quality. Some quality will always have to be sacrificed to release features within a reasonable timeframe, so any of these shortcuts will often be tasked as future projects. Those unattended tasks become what is called technical debt."

- "There are several reasons why technical debt happens. Product owners may focus more on the need to implement and release new features and less on fixing past problems or create a generic enough infrastructure to support future developments. In some severe cases, product owners completely underestimate the outcomes of dealing with poor infrastructure, bugs and poorly designed software."

- "Ultimately, technical debt can sometimes lead to software users having bad experiences and thereby increasing user churn rates. Together, a lack of developer awareness and task ownership can lead to more technical debt."


###### References:
https://logz.io/blog/technical-debt/



# Business logic

:::::::::::::: {.columns}
::: {.column width="40%"}

- "**Business rules** are what your non-software developers tell you what your software needs to do."


- "**Business logic** is the part of your code that specifically implements business rules."

:::
::: {.column width="60%"}
![](http://www.ritholtz.com/blog/wp-content/uploads/2013/07/2011.06.27_organizational_charts.png){ height=200px }
:::
::::::::::::::



###### References:
https://softwareengineering.stackexchange.com/questions/234251/what-really-is-the-business-logic

http://www.ritholtz.com



# Intro to commandline and tools (interactive)
:::::::::::::: {.columns}
::: {.column width="50%"}
- Vim
- Bash
- Git
- Docker

:::
::: {.column width="50%"}

:::
::::::::::::::

# Bash

## Important tools and commands
- `echo`, `while`, `find`, `vars`, `printenv`, `htop`, shebang, wild cards
- `cp`, `touch`, `mkdir`, `ls`, `uniq`, `awk`, `rm`
- `man man`
- `brew`
- `wget`
- `curl`

## References:
https://missing.csail.mit.edu/2020/shell-tools/


# Sneak peek to docker
- `docker run`
- `docker ps`
- `docker run -ti`


# Stackoverflow good questions usually have

## Must have:
1. Problem statement
2. Sample code and data
3. Spelling, grammar and formatting

## Example:
https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array

## References:
https://codeblog.jonskeet.uk/2010/08/29/writing-the-perfect-question/

https://stackoverflow.com/help/how-to-ask


# First task

- Checkout github classroom and the first task about git and github
https://classroom.github.com/classrooms/99552739-eass-hit-2022-part-a


# AWS course (due a week after Passover == April 30, 2022)

- S3, EC2, RDS, and EBS modules
- must get 100 on all 4 modules
- grading will be 25% per module

# A bit more about EC2 instances and types of hardwares (HW)

## EC2 provides secure, resizable compute cloud services. It makes web-scale cloud computing easier and offers HW such as:
- ARM vs. Intel vs. AMD (x86, x86_64)
- GPUs (Nvidia, Intel)
- TPUs (on Google Computing Platform)
- Metal instacnes on AWS
- FPGA-based nodes

## Instance Types and prices (useful links)
https://aws.amazon.com/ec2/instance-types/

https://instances.vantage.sh/


## Instance Types (summary)
  1. General Purpose
  2. Compute Optimised
  3. Memory Optimised
  4. Accelerated Computing (P instances are for general-purpose GPU applications)

## Pricing
There are four ways to pay for EC2 instances: On-Demand, Reserved Instances, and Spot Instances & Per-Second Billing. You can also pay for Dedicated Hosts which provide you with EC2 instance capacity on physical servers dedicated for your use.


# First task on Git and GitHub

## Checkout github classroom and the first task about git and github
https://classroom.github.com/classrooms/99552739-eass-hit-2022-part-a



# How to test our code/system

## General approaches for testing
- Static vs. Dynamic
- Passive testing
- White-box vs. Black-box testing

## Types of testing coverage metric
- API testing – testing all public and private APIs 
Code coverage – creating tests to satisfy some criteria of code coverage (e.g., the test designer can create tests to cause all statements in the program to be executed at least once)

## Types of tesing systems (CI/CD)
- Unit vs. Integration testing
- System testing
- Compatibility testing
- Installation testing
- Smoke and sanity testing
- Regression testing

## We will use pytest and fastapi testing system
- https://fastapi.tiangolo.com/tutorial/testing/
- https://docs.pytest.org/


# All exercises
1. 4 modules on AWS course (S3, EC2, EBS, RDS) - if you finish all the course you get +10 bonus points to final grade
2. Build full REST/HTTP fastapi backend + Dockerization (due 1/4)
3. UI (react/streamlit) (due 1/5)
4. Docker compose the server with UI and backend plus server and write a clear README with git submodules (due 29/5)
5. Presentation of the system in a demo in a 2-3 minutes video on youtube and clear README (due 29/5)


# Ideas for porjects next semester (based on skills we will learn this semester)
1. AI/ML based predictive system
2. Smart contracts (web3)
3. Any other system with at least 3 microservices


# List of the subjects in our course
- Monolithic vs. Microservices
- Docker
- Client-Server
- REST/HTTP API
- FastAPI
- Pytest
- asyncio
- Frontend (React javascript and Streamlit python)
- Docker compose
- Functional programming
- How to compile a new library


# What Are The Best Software Engineering Principles?
## Measure twice and cut once
![](https://iamluminousmen-media.s3.amazonaws.com/media/what-are-the-best-engineering-principles/what-are-the-best-engineering-principles-3.jpg){ width=300px }

## Based on this nice post
https://luminousmen.com/post/what-are-the-best-engineering-principles


# What Are The Best Software Engineering Principles?
## Don’t Repeat Yourself (DRY)
If any code occurs more than twice in the codebase, you should think of moving it in a separate function. In fact, you should consider creating a separate method even if you encounter repetition a second time.

![](https://memegenerator.net/img/instances/54601893.jpg){ width=300px }

# What Are The Best Software Engineering Principles?
## Keep It Simple -Stupid- (KISS)
Some think that this idea transformed from Occam’s Razor philosophical principle. You can interpret it as follows: one should not create extra entities to the system without a strong necessity. It is always a good idea to first consider the usefulness of adding another method/class/tool/process, etc.

# What Are The Best Software Engineering Principles?
## You Aren’t Gonna Need It (YAGNI)
Don't implement all the "necessary" (most likely unnecessary) functionality at once from the very beginning of the project.
![](https://iamluminousmen-media.s3.amazonaws.com/media/m-motivation/m-motivation-7.JPG){ width=300px }


# What Are The Best Software Engineering Principles?
## Avoid Premature Optimization
"Premature optimization is the root of all evil (or at least most of it) in programming" — Donald Knuth

Watch Knuth on a talk with Lex Friedman https://www.youtube.com/watch?v=EE1R8FYUJm0

## Principle Of Least Astonishment
This principle means that your code should be intuitive and obvious, and not surprise another developer when reviewing the code.

## Law of Demeter (Olympian goddess of the harvest and agriculture)
The basic idea here is to divide the areas of responsibility between classes and encapsulate the logic within a class, method, or structure.

1. **Decoupling** You should try to reduce the number of connections between different classes or entities
2. **Cohesion** The associated classes must be in one module/package/directory

# SOLID - create code that is easy to maintain and extend over time

- Single responsibility states that every module or class should have responsibility for a single part of the functionality and that responsibility should be entirely encapsulated by the class

- Open-closed states that software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification

- Liskov substitution states that any inherited class should complement (substitutable), not replace, the behavior of the base class

- Interface segregation states that no client of the class should be forced to depend on methods it does not use

- Dependency inversion says that programmers should work at the interface level and not at the implementation level



# Monolithic vs. Microservices

:::::::::::::: {.columns}
::: {.column width="30%"}
- Monolithic application is a single unified unit that contains all the logic in one entity

- Microservice architecture breaks the application down into a collection of smaller independent units

:::
::: {.column width="70%"}
<!-- ![](static\\review.png){ height=400px } -->
![](https://d2m6ke2px6quvq.cloudfront.net/uploads/2020/09/11/cda4db94-ac16-43ba-82c4-53632154afc7.jpg){ width=300px }
:::
::::::::::::::

#### Further reading material
https://www.n-ix.com/microservices-vs-monolith-which-architecture-best-choice-your-business



# Monolithic vs. Microservices


![](https://d2m6ke2px6quvq.cloudfront.net/uploads/2020/09/11/3f3de3fc-f3a8-4cd1-81cd-518496f59141.jpg){ width=400px }


# Monolithic vs. Microservices

![](https://d2m6ke2px6quvq.cloudfront.net/uploads/2020/09/11/2381c271-4fde-4cc1-94d9-a2e2d72a81c0.jpg){ width=400px }

# Docker
- Dockerhub/Registry
- Dockerfile
- `docker build`
- `docker run`
- `docker ps`
- `docker network ls `
- `docker volumes`
- `docker expose ports `
- `docker images`
- `docker exec`
- `docker image prune -a`


#### Further training material
https://training.play-with-docker.com/alacart/

https://towardsdatascience.com/twenty-one-techniques-and-five-concepts-for-better-docker-usage-9ee135dccdc9

# Advanced "Setting up a reverse proxy server" (How Docker makes our life easier)

"A very common scenario for developers, is to run their server behind a reverse proxy that sits in front of web servers and forwards client/frontend (e.g., web browser) requests to the web servers ("backend"). There are many reasons why you would want to do this but one of the main reasons is to run your API server on a different network or IP then your front-end application is on. You can then secure this network and only allow traffic from the reverse proxy server. For the sake of simplicity and space, I’ve created a simple frontend application in React.js and a simple backend API written in Node.js. Run the following command to pull the code from GitHub."


## Without docker this is not easy to do.
Soon we will see how Docker simplifies the process of building a server that run a reverse proxy


## Go through (reverse proxy, react, nginx):

https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/


# Using Docker nginx walkthrough an offical tutorial together
## https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/

1. `docker run -it --rm -d -p 8080:80 --name web nginx`
2. `curl http://localhost:8080`
3. `docker stop web`
4. Add `index.html` to local site-content and map it to `/usr/share/nginx/html` (https://gist.github.com/chrisvfritz/bc010e6ed25b802da7eb)
5. `docker run -it --rm -d -p 8080:80 --name web -v ~/site-content:/usr/share/nginx/html nginx`
6. Doing stuff via Dockerfile (`docker build -t webserver`):
```
FROM nginx:latest
COPY ./index.html /usr/share/nginx/html/index.html
```
7. `docker run -it --rm -d -p 8080:80 --name web webserver`



# Recap - linux commands everyone should know

## host/network commands
 - `ip`
 - `ifconfig`
 - `hostname`
 - `whoami`
 - `uname`
 - `ping`

## file-realted commands
 - `mkdir` `rmdir` `cp` `mv`, `rm`
 - `cd` `ls -l`
 - `find`
 - `wc`
 - `xxd`
 - `du -h /`
 - `chown` `chmod`

## archives:
- `zip`, `tar` `gzip`, `unzip`, `gunzip`
- `tar -czvf name-of-archive.tar.gz /path/to/dir-or-file` 
  
  `c` - create, `v` verbose, `f` - allow to chose the name


# Recap - linux commands everyone should know

## more commands
- `cat` `touch` `echo`
- `locate` `whereis` `which` `find`
- `grep`
- `df` `du`
- `awk` `head` `tail`
- `diff`
- `jobs` (to see background jobs `command&`)
- `kill` (sending signals to processes)

`SIGTERM (15)` -- requests the job to stop

`SIGKILL (9)` -- forces programs to stop

- `wget` `curl`
- `top`, `htop`, `brew` (should be installed), `apt-install`




# How microservices talk to each other

## What is API?
API stands for Application Programming Interface. This interface allows users to build upon another application's functionality.

## What is web API?
Web API is when other SW services uses other application's/service's functionbality over the web/network.

## What is HTTP?
HTTP stands for Hypertext Transfer Protocol: an application layer protocol in the Internet protocol suite model for distributed, collaborative, hypermedia information systems.
- http://facebook.com
- https://facebook.com


# How microservices talk to each other

## GET method
```
GET /microservice/v1/function?param1=value1&param=value2
```

## POST method
```
POST /microservice/v1/function HTTP/1.1
Host: localhost

param1=value1&param=value2
```

# How do we perform HTTP requests (postman and cli)

1. Postman
https://web.postman.co/home

2. `curl` or `wget` in the command line

# How do we perform HTTP requests (python)

3. `requests` library in python:
```
>> r = requests.get('https://api.github.com/user', auth=('user', 'pass'))
>> r.status_code
200
>> r.headers['content-type']
'application/json; charset=utf8'
>> r.encoding
'utf-8'
>> r.text
'{"type":"User"...'
>> r.json()
{'private_gists': 419, 'total_private_repos': 77, ...}
```

4. `httpx` library in python
https://www.python-httpx.org/quickstart/


# Demo performing HTTP reqeusts `httpx` vs. `curl`

1. Perform GET https://httpbin.org/get

2. Perform POST `https://httpbin.org/post` with `data={'key': 'value'}`

* Note that POST/GET could be "overloaded" (have the same endpoint)



# How microservices talk to each other
## What is a REST API?
"When a client request is made via a RESTful API, it transfers a representation of the state of the resource to the requester or endpoint. This information, or representation, is delivered in one of several formats via HTTP: JSON (Javascript Object Notation), HTML, XLT, Python, PHP, or plain text. JSON is the most generally popular file format to use because, despite its name, it’s language-agnostic, as well as readable by both humans and machines"

#### Read more about REST and HTTP

https://www.redhat.com/en/topics/api/what-is-a-rest-api

https://www.educative.io/blog/what-are-rest-apis


# In class hands-on session (training for Ex1)
**Please complete due next class (March 7th, 2022) and use Discord for help**

1. Create a remote git repo on our organization GitHub https://github.com/EASS-HIT-2022/ (private/public)

2. Name the repo `http-api-demo-<your github name>`

3. Include a README, Dockerfile, client.py files

4. In client.py include at least two POST/GET requests from httpbin demo HTTP API (http://httpbin.org/):
- POST to any endpoint of your choice (e.g., http://httpbin.org/post)
- GET to any endpoint of your choice (e.g., http://httpbin.org/get)

5. Make a Dockerfile that execute client.py on startup and prints the status and output from the http requests it performs from step 3. Helpful snippet:
```
FROM ubuntu
RUN  apt-get update
RUN  apt-get -y install python
CMD ["echo", "Hello, EASS 2022"]
```

6. Now, create a second Dockerfile in your git repo `localhost.Dockerfile` which call to the local hosted httpbin and call it via http://localhost:
`docker run -p 80:80 kennethreitz/httpbin`
7. build the second docker image. Useful command:
```
docker build -t tab ./ -f localhost.Dockerfile
```

# Hello World, FastAPI

## Install
1. `pip install fastapi`
2. `pip install "uvicorn[standard]"`
Uvicorn is an ASGI (Asynchronous Server Gateway Interface) web server implementation for Python

## code of the server (`main.py`)

```python
from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def get_root():
    return {"message": "Hello World", "method": "GET"}

@app.post("/")
async def post_root():
    return {"message": "Hello World", "method": "POST"}
```

# Hello World, FastAPI
## Running the server

```
uvicorn main:app --reload
```

## read more

https://fastapi.tiangolo.com/tutorial/

# Ex 1 (Due April 10, 2022)

1. Build only the backend (using FastAPI)
2. Include a Dockerfile, README and the source code of the app
3. Be OOP-friendly (recall the SOLID principle) and use `pydantic`
4. Include both integartion and unit tests inside using `pytest`, `httpx`, or `pip install docker` (you may use some bash scripting as well). The idea is to be robust, simple and test the whole system wisely and efficently.

Suggested layout of the repo:

```
.
|- app
|             |- main.py
|             |- unit_tests.py
|             |- requirements.txt
|
|- integration_test.py
|- Dockerfile
|- README.md
```

## List of ideas ideas for projects
- Building the backend of a voting app 
- Personal wallet (keep expenses, images)
- Weather application
- The backend of a US/IL stock viewer analyzer webapp
- The backend of a twitter summarizer webapp (focus on one field e.g., stock symbols)

# Handling Data/Models over the wire
We want to send data (JSONs) over the wire, but in the code we would like to work with objects.

- DTO (Data Transfer Object)

- ORM (Object Relational Mapping)

- MVC (Model View Controller)

# The MVC design pattern (mostly related to UI)

- Model
The model manages the data, logic and rules of the application.
- View
Any representation of information such as a chart, diagram or table.
- Controller
Accepts input and converts it to commands for the model or view.

![](https://developer.mozilla.org/en-US/docs/Glossary/MVC/model-view-controller-light-blue.png){ width=200px }


ref (Mozilla is great for web resources)
https://developer.mozilla.org/en-US/docs/Glossary/MVC/model-view-controller-light-blue.png


# Pydantic 
`pydantic` helps us to define what type of JSONs are valid and what are their interperation. With Pydantic's Model classes we can define the input/outputs of each API endpoint. It helps fastapi with validation, serialization, and documentation.

1. Between microservices (`request` vs. `response`)
2. Between Databases microservices
3. Or between any two entities or the user and the application

```python
from pydantic import BaseModel

class User(BaseModel):
    id: int
    name = 'Jane Doe'
```

# Pydantic
```python
from pydantic import BaseModel

class Client(BaseModel):
    id: int
    balance: float

class Transaction(BaseModel):
    from_client: Client
    to_client: Client
    amount: float

class Request(BaseModel):
    id: int
    transaction: Transaction

class Response(Request):
    approved: bool
    executed: bool
```

# Accesing the data
```python
@app.post("/v1/handle")
def handle(req: Request):
  if req.from_client.balance > req.transaction.amount:
    pass # do something
  
  res = Response()

  res.id = req.id
  return res
```

# Using dataclasses, understanding what's pydantic is doing
```python
from pydantic.dataclasses import dataclass
import json

@dataclass
class User:
  id: int
  name: str

user = User(id=123, name="James")
d = asdict(user)  # {'id': 123, 'name': 'James'
user_json = json.dumps(d)
print(user_json)  # '{"id": 123, "name": "James"}'

# Or directly with pydantic_encoder
json.dumps(user, default=pydantic_encoder)

json_raw = '{"id": 123, "name": "James"}'
user_dict = json.loads(json_raw)
user = User(**user_dict)

user = User.__pydantic_model__.parse_raw('{"id": 123, "name": "James"}')
print(user)
```

### ref:
https://stackoverflow.com/questions/67621046/initializing-a-pydantic-dataclass-from-json

# How to design a project ()
- architecture
- draw.io

![](https://raw.githubusercontent.com/donnemartin/system-design-primer/master/images/jrUBAF7.png){width=250px}


# Step 1: Outline use cases, constraints, and assumptions
Gather requirements and scope the problem. Ask questions to clarify use cases and constraints. Discuss assumptions.

- Who is going to use it?
- How are they going to use it?
- How many users are there?
- What does the system do?
- What are the inputs and outputs of the system?
- How much data do we expect to handle?
- How many requests per second do we expect?
- What is the expected read to write ratio?

## ref
https://github.com/donnemartin/system-design-primer


# Step 2: Create a high level design

- Outline a high level design with all important components.
- Sketch the main components and connections
- Justify your ideas

How to use draw.io: https://reneelin2019.medium.com/drawing-cloud-architectures-neural-network-diagrams-and-more-with-draw-io-4f7128ee1aea


# Step 3: Design core components
Dive into details for each core component. For example, if you were asked to design a url shortening service, discuss:

- Generating and storing a hash of the full url
    - MD5 and Base62
    - Hash collisions
    - SQL or NoSQL
    - Database schema
- Translating a hashed url to the full url
    - Database lookup
- API and object-oriented design between the microservices

## ref
https://github.com/donnemartin/system-design-primer



# Step 4: Scale the design
Identify and address bottlenecks, given the constraints. For example, do you need the following to address scalability issues?

- Load balancer
- Horizontal scaling
- Caching
- Database sharding
- Blue-green deployment to reduce downtime and risk
- Discuss potential solutions and trade-offs. Everything is a trade-off. Address bottlenecks using principles of scalable system design.

# Tips
- Use back of the envelope calculations
- Powers of two table
```
Power           Exact Value         Approx Value        Bytes
---------------------------------------------------------------
7                             128
8                             256
10                           1024   1 thousand           1 KB
16                         65,536                       64 KB
20                      1,048,576   1 million            1 MB
30                  1,073,741,824   1 billion            1 GB
32                  4,294,967,296                        4 GB
40              1,099,511,627,776   1 trillion           1 TB
```

# Tips
- Latency numbers every programmer should know
```
Latency Comparison Numbers
--------------------------
L1 cache reference                    0.5 ns
Branch mispredict                       5 ns
L2 cache reference                      7 ns   14x L1 cache
Mutex lock/unlock                      25 ns
Main memory reference               100   ns   20x L2 cache, 200x L1 cache
Compress 1K bytes with Zippy           10 us
Send 1 KB bytes over 1 Gbps network    10 us
Read 4 KB randomly from SSD*          150 us  ~1GB/sec SSD
Read 1 MB sequentially from memory    250 us
Round trip within same datacenter     500 us
Read 1 MB sequentially from SSD*        1 ms  ~1GB/sec SSD, 4X memory
HDD seek                               10 ms   20x datacenter roundtrip
Read 1 MB sequentially from 1 Gbps     10 ms   40x memory, 10X SSD
Read 1 MB sequentially from HDD        30 ms   120x memory, 30X SSD
Send packet CA->Israel->CA            200 ms
```

## ref
https://github.com/donnemartin/system-design-primer

# How would you implement google search engine (discussion)
https://softwareengineering.stackexchange.com/questions/38324/how-would-you-implement-google-search


# Good luck to all of us

:::::::::::::: {.columns}
::: {.column width="50%"}
![](static\eass_logo.PNG){ width=150px }

:::
::: {.column width="50%"}
Be active on EASS discord and try to learn and help each other as much as you can.
:::
::::::::::::::


# Triage 
https://docs.microsoft.com/en-us/visualstudio/docker/tutorials/docker-tutorial
https://github.com/docker/awesome-compose/tree/master/fastapi
https://luminousmen.com/post/what-are-the-best-engineering-principles
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Concepts