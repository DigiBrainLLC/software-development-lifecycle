# Software Development Lifecycle 

## Stage 1: Planning and Requirement Analysis

“What are the current problems?” This stage of the SDLC means getting input from all stakeholders, including customers, salespeople, industry experts, and programmers. Learn the strengths and weaknesses of the current system with improvement as the goal.

- Collect requirements (including dates) and project ideas from client
- Create a list of the current problems and proposed solutions

## Stage 2: Defining Requirements

Once the requirement analysis is done the next step is to clearly define and document the product requirements and get them approved from the customer or the market analysts. This is done through an SRS (Software Requirement Specification) document which consists of all the product requirements to be designed and developed during the project life cycle.

- Create Software Requirements Specification (SRS): https://www.perforce.com/blog/alm/how-write-software-requirements-specification-srs-document
- Get client approval on SRS

## Stage 3: Designing the Product Architecture

A design approach clearly defines all the architectural modules of the product along with its communication and data flow representation with the external and third party modules (if any). The internal design of all the modules of the proposed architecture should be clearly defined with the minutest of the details in Design Document Specification (DDS).

- Wireframe design / data-flow representation
- API tables and docs
- Have client sign contract

## Stage 4: Development

In this stage of SDLC the actual development starts and the product is built. The programming code is generated as per DDS during this stage. If the design is performed in a detailed and organized manner, code generation can be accomplished without much hassle.

- Write unit and functional tests (TDD)
- Create all functionality 
- Add style to once functionality works properly

## Stage 5: Testing

- Make sure unit tests pass 100%
- Make sure functional tests pass 100%
- Make sure manual testing pass 100% (all user's flow is good)

### Stage 6: Deployment and User Acceptance Testing (UAT): Beta

- Deploy code to production
- UAT begins for allotted time
- Get UAT feedback
- While client does not accept:
    - Make changes and get feedback
- Client signs off on project 

