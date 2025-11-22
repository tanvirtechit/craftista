## What is Craftista: Celebrating the Art of Origami 

Welcome to Craftista, a unique web platform dedicated to the beautiful and intricate world of origami. Craftista is a place where origami enthusiasts and artists come together to showcase their creations, share their passion, and engage with a like-minded community. Our platform allows users to explore a diverse range of origami art, vote for their favorites, and get inspired by the daily featured origami.

![Simple Design](docs/stage4-02.png)

### Features

**Origami Showcase**: 

Discover a wide array of origami creations, ranging from traditional designs to contemporary art pieces. Each origami has its own story and charm, waiting to be unfolded.

**User Voting System**: 

Participate in the community by voting for your favorite origami pieces. See what creations are trending and show your support for the artists.
Daily Origami Recommendation: Be greeted daily with a new origami masterpiece, handpicked to inspire and ignite your passion for paper folding.

**Origami of the Day**: 

Learn more about origami artists, their work, and their journey into the world of paper art.

---


## The Architecture 

Craftista is not just an origami platform; it's a demonstration of modern web application development and microservices architecture. It leverages multiple backend services, including:

![Craftista Architevture](docs/Craftista-Architecture-SchoolofDevops-CC-BY-NC-SA4.0.jpg "Craftista Architecture")

### Micro Service 01 - Frontend

**Purpose**: 
Serves as the frontend, acts as a router, integrates with all other services renders the  Graphical Interface.  

**Language**: Node.js  

**Framework**: Express.js  

### Micro Service 02 - Catalogue

**Purpose:** 
Manages the origami showcase, including origami details and images.  

**Language:** Python  

**Framework:** Flask  

#### Backing Service 01: catalogue-db  
Phase 1 : JSON File  
Phase 2 : MongoDB  

###  Micro Service 03 - Voting


#### Backing Service 02 : voting-db
Phase 1 : H2  
Phase 2 : PostgreSQL  


###  Micro Service 04 - Recommendation 

**Purpose:** 
Selects and presents the daily origami recommendation.    
**Language:** Golang  

Each service is built using a different technology stack, showcasing polyglot persistence and diverse backend technologies.

---








