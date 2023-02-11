1) const heading = react.createElement("hi",{class:"heading"}, "helloworld")

2) only use render and root once in app

3) props means html attributes
   props=properties

4) react element we ctreated using  react.createElement is an OBJECT

5)       "devDependencies": {
        "parcel": "^2.8.3"
      }

        "parcel": "^2.8.3" => " ^ " here this ^ is called Carrot so that this ensures that the version auto upgrade to latest. if you remove ^ then the mentioned version will be installed.

6) package lock - locks the version for you. it will exactly tell you what version version currently your app is running on

7) important PACKAGE LOCK JSON file
dont git ignore it

in the package.json the code will always be "parcel": "^2.8.3" but it does not mean it is currently working on that version as you have used carrot(^) infront of the version. The details about current version will be kept inside package-lock.json. 
It ensures that the version that is running on the system is same as the version in production. 
 
8) 