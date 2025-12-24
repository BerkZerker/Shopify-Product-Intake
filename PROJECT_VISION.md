# Project Vision

The goal of this is an app that uses the gemini api and the shopify graph ql api to add new products to a shopify store based on an invoice. The user will upload an invoice and the app will use the gemini api to extract the relevant product information from the invoice. The app will then use the shopify graph ql api to add the new products to the user's shopify store. The info needs to include the product name, the cost (wholesale) and the retail price will be based off a database of the product names and their retail prices. So first it will extrac the product info, and then check the database for the retail price, and then add the product to shopify with the wholesale cost from the invoice and the retail price from the database. Each product needs to be a unique product with a unique number in the product name. For example, something like this:

"Velotric Fold 1 Plus Blue - Bike # 524" (wholesale cost $999, retail price $1999)

I have a shopfiy store so we just need to build a demo of the app as a proof of concept to show that it works. The app should have a simple user interface where the user can upload an invoice and see the products that have been added to their shopify store. Focus on getting it working as this is just a tech demo to show the concept to potential investors.
