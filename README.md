# Enfortis Technologies Project-1101

## Mobile App Developmental Test Server

***

This project is a Express/ Node rest api application which will be used by a 
mobile app developer for testing API endpoints during the early development phase.

---

### Build Status
    TBD


### AWS host URL
n/a

### API Reference

    GET /login
        Query Parameters:
            key: awt_key
            value: AWT object
        Successful Response
            Code: 200: 
        Error Response 
            Code: 401    Body: Authentication Failed


    GET /userWord
        Query Parameters:
            key: word
            value: search word
        Successful Response
            Code: 200   Body: word definition
        Error Response 
            Code: 404    Body: not found
            


#### Additional Activities:


#### Usage: 
    TBD once server has been deployed
