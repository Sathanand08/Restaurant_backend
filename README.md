 MERN Stack Multi-Vendor Restaurant Application Documentation

Dependencies

·         express

·         mongoose

·         dotenv

·         body-parser

·         nodemon

·         jsonwebtoken (JW Token)

·         bcryptjs

·         multer

·         cors

Connection to Database

API Creation

                Models

                                Vendor:

Properties:  username, email, password

                                Firm:

Properties:   firmName, area, category, region, offer , image

                                Product:

Properties:   productName, price, category, image, bestseller, description

                Controllers

                                vendorController

                                firmController

                                productController

                Routes  

                                vendorRoutes

                                firmRoutes

                                productRoutes

 

Different JWTokens for evey login

API Routes:

                Vendor:

                            Vendor Register:

  https://backend-nodejs-suby.onrender.com/vendor/register

Vendor Login:

  https://backend-nodejs-suby.onrender.com/ vendor/login

Get All vendor details with relations records:

{API used for React client side frontend}

  https://backend-nodejs-suby.onrender.com/vendor/all-vendors

 https://backend-nodejs-suby.onrender.com/vendor/single-vendor/:vendorId

Image Uploads:


  https://backend-nodejs-suby.onrender.com/uploads/:imageName

Firm:

                Add Firm to Vendor by JW Token:

 https://backend-nodejs-suby.onrender.com/firm/add-firm

Delete Firm by Id:

  https://backend-nodejs-suby.onrender.com/firm/:firmId

Products:

                Add Product to Firm by Id:

  https://backend-nodejs-suby.onrender.com/product/add-product/:firmId

Get Products by FirmId:

 https://backend-nodejs-suby.onrender.com/product/:firmId/products

Delete Product by Id:

  https://backend-nodejs-suby.onrender.com/product/:productId
