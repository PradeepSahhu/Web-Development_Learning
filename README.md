# Web-Development_Learning


## Navigation Bar.
- ~Trial and Error.~
- using css positioning to adjust the div(containers of the.
- Many div containers on top of each other. 
- unresponsive. 
![unresponsiveNavigationBar](https://user-images.githubusercontent.com/94203408/153798654-1f136834-6e50-4aa9-bcfd-a60b7ee7d936.png)


## Responsive Navigation Bar.
- responsive (adjustable) navigation bar.
- advanced CSS and @imported google fonts.
![navigationBar](https://user-images.githubusercontent.com/94203408/153798345-7dd3cc7d-fc77-4279-9742-3edc5c859c41.png)

## Mongoose DB 
- Mongoose Schema.
- Mongoose Model.
- Mongoose Documentation.

```
const mongoose = require('mongoose');
mongoose.connect('mongodb://localhost:27017/test');

const Cat = mongoose.model('Cat', { name: String });

const kitty = new Cat({ name: 'Zildjian' });
kitty.save().then(() => console.log('meow'));
```
![MongooseDB](https://user-images.githubusercontent.com/94203408/154194872-00e4e18a-7f59-4a30-8afe-d046450d50eb.png)

