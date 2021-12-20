# MobileApp
This is information on making your own mobile app using Safex Blockchain data

Since the Safex.org blockchain is accessible via web calls, you can bring the data into a mobile app. 
One challenge is decoding the data and formatting it directly form teh blockchain. 
Here you will get to see and copy a live example so that you can tweak things yourself. 

Tools we can use: 
For the app: 
Thunkable.com to create a mobile app (free version let's you experiment for yourself and use it where as paid version let's you list live on iOS and Android app stores. 
You can clone a sample app here: https://x.thunkable.com/copy/d81745ddc8f416ee640c2a2f33d980bd
Get the "Thunkable Live" app from your phone's apps store. 
PRO TIP: If connecting GSheets to Thunkable app directly, it is best to use a a regular Google account (Not Education or For Business), if needed, make a new Google account to be able to connect GSheet to Thunkable!

For the data: 
GSheets is able to connect, so if you are pulling data in to GSheet, and formatting/filtering it, you can then use that data in your mobile app (and share it with just yourself, a small community, or the world)
We already have a live GSHEET example that you can copy: https://docs.google.com/spreadsheets/d/1JEJ3pdy4cM9ulqBVK2eJKowNtWNCLEy5uNLnYkG2waw/edit?usp=sharing
If you clone this to your Drive, share the sheet as "Anyone with the link", then you should be able to connect to Thunkable app. 

Firestore is another option. This is a Firebase.com product (By Google) and has free tiers, and inexpensive paid tiers. Data from GSheet can populate FireStore and you can pull the data into your mobile app. (Sample to be provided in near future)
Benefits of FireStore is that it is faster than GSheets when connected to a mobile app. This means that one could share with the world, or just a small community. And since you control what data goes into FireStore from your GSheet, you can limit the data users are exposed to giving a faster, more focused experience. 

