# &int; created
> Integration created

# Idempiere Angular WebStore 
> 

Idempiere Angular WebStore is a frontend application created as responsive angular / bootstrap seed for your projects. 
This applications shows standard web sites features:
* product catalog
* product search
* user authentication
* basket management synchronized with server
* order checkout
* private customer area
* order list
* password update
* account information update

Project structure has been inspired from Tom Cowley blog post:

[Angular Folder Structure](https://medium.com/@motcowley/angular-folder-structure-d1809be95542).
Thank's Tom.

![WebStore Architecture](/src/assets/images/screen_architecture.png?raw=true "Webstore Architecture")

Server side Idempiere REST services project:

[https://github.com/icreated/webstore-api](https://github.com/icreated/webstore-api)

## Some snapshots:

### Home page

![WebStore Home](/src/assets/images/screen_home.png?raw=true "Webstore Home")

### Basket page

![WebStore Basket](/src/assets/images/screen_basket.png?raw=true "Webstore Basket")

### Checkout page

![WebStore Checkout](/src/assets/images/screen_checkout.png?raw=true "Webstore Checkout")

### Order page

![WebStore Order](/src/assets/images/screen_order.png?raw=true "Webstore Order")



## Installing / Getting started

By default, Idempiere Webstore API REST endpoints are installed here:

(http://localhost:8080/services/api/)[http://localhost:8080/services/api/]

Change constant `API_ENDPOINT` in `app/core/library.ts` if different


### Deploying / Publishing / Testing

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. 

Pull requests are warmly welcome


## Licensing

GNU General Public License


