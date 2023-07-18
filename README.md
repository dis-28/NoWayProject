
# NoWay

A brief description of what this project does and who it's for


## Demo

- [demoLink1](https://drive.google.com/file/d/1pSaGIDEtcM-XmPJak_nZ6Mssc4cG5uYW/view?usp=drive_link)
- [demoLink2](https://drive.google.com/file/d/1x2HZc2gG3Tu4LInNPUDaE8FMJ9c68KOH/view?usp=sharing)



## Features

- displays the shortest distance between source and destination.
- displays shortest path one must take to reach destintion with minimum distance

## API Reference

#### Get shortest distance between node A and node B 

```http
  GET /shortd/<int:A>/<int:B>
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `source` | `integer` | **Required**|
| `destination` | `integer` |     **Required**      |




## Tech Stack

**Client:** React

**Server:** Flask, Python


## Used By

This project is used by the following:

- Students of IIT Guwahati


## FAQ

#### How will obtain my shortest path from source to destination?

Every possible source and destination is mapped with a number ranging from (1 to 64). Path in the application will display the nodes in order to reach the destination. 



## Authors

- [@siddharthKashyap](https://github.com/dis-28)

