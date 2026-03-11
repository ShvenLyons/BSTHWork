# Micro-teaching Worksheet

## Topic
**Computer Network Fundamentals: OSI 7-layer model and DNS**

## Intended Learning Outcomes (ILOs)
1. **Students of the Computer Network Course** will be able to **identify the seven layers of the OSI model and briefly explain the basic function of each layer**.
2. **Students of the Computer Network Course** will be able to **explain the basic concept of domain names and DNS, and describe how a domain name is resolved into an IP address**.

## 50-minute Tutorial Lesson Plan
> [Trigger](https://www.douyin.com/video/7029988216426073381)

### Engage (0–6 min)
Start with a real-life question: **“What happens when we type a URL into a browser and press Enter?”**

The lesson begins by connecting students’ everyday online experience with two key concepts in computer networks:
- the **OSI 7-layer model**
- **domain names and DNS**

Students respond to short guided questions such as:
- What is a URL?
- Do computers directly understand domain names?
- What may happen before a webpage is displayed?

This opening is used to gain attention, activate prior knowledge, and show the relevance of the lesson.

### Explore (6–14 min)
Before giving formal explanations, students are asked to brainstorm how network communication may be structured.

The teacher asks questions such as:
- If data is sent from one computer to another, what kinds of functions are needed?
- Do we need rules for transmission, addressing, reliability, and applications?
- If domain names are human-readable, what system is needed to translate them into machine-readable addresses?

Students share brief responses, and the teacher collects their ideas. This stage encourages exploration before formal teaching.

### Explain (14–28 min)

#### Part A: OSI 7-layer model (14–22 min)
The teacher introduces the seven layers of the OSI model and briefly explains the function of each layer:

1. **Physical Layer** – transmits raw bits through physical media  
2. **Data Link Layer** – handles framing and MAC addressing  
3. **Network Layer** – handles logical addressing and routing  
4. **Transport Layer** – provides end-to-end delivery and reliability  
5. **Session Layer** – manages communication sessions  
6. **Presentation Layer** – handles translation, encryption, and compression  
7. **Application Layer** – provides services for user applications  

After the explanation, students complete a small **layer header design** task. They discuss what kind of information may be added at different layers, such as:
- destination IP at the Network Layer
- port number at the Transport Layer
- MAC address at the Data Link Layer

This helps students understand that each layer has its own responsibility and control information.

#### Part B: Domain names and DNS (22–28 min)
The teacher explains:
- what a domain name is
- why domain names are used instead of IP addresses
- the role of DNS in translating domain names into IP addresses

A simple domain name example is introduced:

`www.example.com`

Students learn the hierarchical meaning of each part:
- `com` = top-level domain
- `example` = second-level domain
- `www` = subdomain or host name

### Elaborate (28–42 min)
Students apply what they have learned through two tasks.

#### Task 1: Analyze a domain name or URL (28–35 min)
Students are given a domain name or URL, for example:

`https://mail.cs.example.edu/index.html`

They identify the meaning of each part, such as:
- `https` = protocol
- `mail.cs.example.edu` = domain name
- `edu` = top-level domain
- `example` = second-level domain
- `cs` = subdomain
- `mail` = host or service name
- `/index.html` = path or resource

This task helps students understand the structure of domain names in realistic Internet examples.

#### Task 2: Draw the DNS resolution process (35–42 min)
Students are given:
- one domain name URL
- several DNS servers, such as:
  - local DNS resolver
  - root DNS server
  - TLD DNS server
  - authoritative DNS server

They then draw the DNS resolution process step by step. For example, for `www.example.com`, students show:
1. the client asks the local DNS resolver
2. the resolver asks the root DNS server
3. the root DNS server points to the `.com` TLD DNS server
4. the resolver asks the `.com` TLD DNS server
5. the TLD DNS server points to the authoritative DNS server
6. the resolver asks the authoritative DNS server
7. the authoritative DNS server returns the IP address
8. the resolver returns the result to the client

This task helps students visualize the DNS hierarchy and resolution process.

### Evaluate (42–50 min)
At the end of the lesson, students complete a short exit check.

They answer the following questions:
1. Name the seven layers of the OSI model.  
2. Choose one OSI layer and explain its basic function.  
3. In a domain name such as `www.example.com`, what does each part mean?  
4. Briefly describe how DNS resolves a domain name into an IP address.  

The teacher then gives a short summary:
- the **OSI model** helps us understand network communication in a structured way
- **DNS** helps humans use domain names while computers communicate using IP addresses
- both concepts are fundamental to understanding how the Internet works

## Use of the 5E Model
- **Engage:** Students are introduced to the lesson through a familiar Internet scenario.
- **Explore:** Students brainstorm how communication and name resolution may work.
- **Explain:** The teacher explains the OSI 7-layer model, domain names, and DNS.
- **Elaborate:** Students apply knowledge through URL analysis, layer header design, and DNS process drawing.
- **Evaluate:** Students complete short exit questions to demonstrate understanding.

## Use of the Bookend Model
This lesson also follows the **Bookend Model**:
- it begins with a short instructor-led introduction and framing
- it includes active learning tasks in the middle of the lesson
- it ends with a short recap and formative assessment

Thus, the overall structure is:

**Brief input → active learning tasks → closing assessment and summary**

## Two Active Learning Strategies
1. **Question-and-answer discussion**  
2. **Diagramming / drawing task**
