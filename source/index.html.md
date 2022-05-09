---
title: DrinVET

language_tabs: # must be one of https://git.io/vQNgJ
  - producers
  - teaching
  - best practices
  - I dont know yet

toc_footers:
  - <a href='#'>nem mutat sehova</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true

code_clipboard: true

meta:
  - name: description
    content: Documentation for Digital Reality in VET
---

![Temporary Banner](/images/Banner_VR_temporary.png)
# Introduction
This Handbook is dedicated to teachers, trainers and decision makers in vocational education systems, to help to get familiar with digital reality tools and systems when you plan to implement them. Last but not at least the book is dedicated to the young generation breaking new ways in teaching and learning. 

We assume that you have at least a passing familiarity with Virtual Reality and Augmented Reality. You may have heard the terms or seen someone trying out a VR experience at a mall or retailer. No more prerequsites are needed.

The book will be divided into five parts as seen on the contents to the left. The right sidebar will add more details broken down to tabs: "producers", "teaching", "best practices" *(still dont know the fourth)*

# Getting started

# Digital Reality in Education
## 1. Tools and Solutions
  **foreword**

    In this foreword we define Digital Reality. Define AR, VR, XR, Mixed Realities. Then briefly introduce the chapter: organizing principles.

  **ABC classification**

    The classification is form Reality Bytes - helps to organise the different solutions. A for Absorb, B for Blend, C for Create. The tags on the right sidebar can probably be exploited by the classification. 

  **The simplest ways**

    We will list here simple but clever solutions to gamify entertain and teach students with help of Digital Reality. 
    some examples:
    LMS Systems -> how to use them, 
    Video tutorials -> practical solutions or links where to get them.
    Escape rooms
    Online physical workouts. (videózd le, hogy veszed fel a zoknidat kéz nélkül...)
  
  **AR Solutions**

    There are plenty of them. Should make a decent list with descriptions, links, and technical infos on the sidebars. WE HAVE TO KEEP ON A GENERAL WAY. Providing tools only with a few words
  
  **VR Solutions**
    here Our stuff will come 
  
  **Tools to make your AR solutions**

    A list with recent sofwares available (free and priced) short descriptions, and an estimate on the learning curve.

## 2. Digital Reality in VET
  
  **Foreword**
    
    Praesent in gravida sem. Sed leo justo, malesuada eu placerat ut, molestie vehicula lacus. Integer eu accumsan leo. Curabitur scelerisque, nibh id ornare bibendum, velit eros faucibus lorem, quis tincidunt odio enim a nulla. Mauris luctus semper molestie. Vivamus hendrerit tortor a lacus tempor vestibulum. Suspendisse varius gravida dui quis placerat. Q

## 3. How to choose
  
  **Important Aspects**
      Typical users - with goals and conditions.
      Benefits (Cost reduction, effectivity in teaching, )
      Challenges in reorganization of classrooms, methods, skills attitudes.
  
  **Approaches in development** 
      Introduce approaches in welding, then transfer the conclusions to other skills. 
  
  **Producers** 
      Key players and their strategies
    
## 4. Prospects
      Technological prospects: I NEED INFO FROM VIRSABI 
      and pedagogical prospects (based on success stories and results) 


# Pedagogical Guidelines

## Approaches

      Here we will describe all the Approaches (connected) and say a few words of their implementation. Gamification to be mentioned with examples and reference to the gamification handbook.

## Best Practices

      Purely implementations and Success stories EACH must end with a conlusion
      Links, demos, short notes on the right sidebar!!! (not only IO3 stuff...)

## Challenges

  **Differences between approaches**

      Different products represent different approaches. Level of simulation, realistic tools or not.  
  
  **Health and safety**
      Here the important aspects will come

  **Organizing Tips and tricks**

     for Grouping and keeping interactivity in online blended and offline situations.

  **Odd case scenarios**
      All the challenges such as strong resitance of a senior expert - or buying a simulator and not using it.



# Instructor 4.0
  
  **foreword**

  Why this new role emerges
  
  **body text**


  dont know yet what comes here Specifications, examples, producers who has traings and gives you certificates... who are these people where yo 


# Glossary
  
  All the neccessary expressions. 
  (for exeplaBlended learning now has at least three meanings: 1. in ABC classification in this book, 2. Online and offline classroom together, 3. Rotated use of simulators and other tools at the same time in Sorin presentation in IO3 )
  


> To authorize, use this code:

```ruby

require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here" \
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
```

> Make sure to replace `meowmeowmeow` with your API key.

Kittn uses API keys to allow access to the API. You can register a new Kittn API key at our [developer portal](http://example.com/developers).

Kittn expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: meowmeowmeow`

<aside class="notice">
You must replace <code>meowmeowmeow</code> with your personal API key.
</aside>

# Kittens

## Get All Kittens

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get()
```

```shell
curl "http://example.com/api/kittens" \
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let kittens = api.kittens.get();
```

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Max",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

This endpoint retrieves all kittens.

### HTTP Request

`GET http://example.com/api/kittens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

## Get a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get(2)
```

```shell
curl "http://example.com/api/kittens/2" \
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.get(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Max",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

## Delete a Specific Kitten

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.delete(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.delete(2)
```

```shell
curl "http://example.com/api/kittens/2" \
  -X DELETE \
  -H "Authorization: meowmeowmeow"
```

```javascript
const kittn = require('kittn');

let api = kittn.authorize('meowmeowmeow');
let max = api.kittens.delete(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "deleted" : ":("
}
```

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

