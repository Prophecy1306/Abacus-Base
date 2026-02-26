<div align="left">

##  **Introduction📜**

I’m building a simple calculator as a mini dApp on Base.  The idea is straightforward. Most people think dApps have to be complex, full of tokens and charts. I wanted to start with something everyone understands. A calculator but instead of running locally, it lives on-chain.

</div>

<div align="center">

#  📱 **Abacus [Base Mini App]** 📱


</div>


##  **Basic-Requirements⚙️**

1.) Create V0 account :- https://v0.app/ref/S4PSH0

2.) Create @farcaster_xyz :- https://farcaster.xyz/~/code/039FJB

3.) Create @baseapp :- https://base.app/invite/friends/S7ZX04QK

* >Must link your farcaster account in base app


<div align="center">
  
##  **Required Steps📔**

</div>

■ Step 1 : 

```
Create the Calculator Application 

- Built a functional calculator with add, subtract, multiply, and divide operations

- Creat /components/calculator.tsx with full calculator logic and UI

- Creat /app/page.tsx as the main entry point

- Use React hooks (useState) for state management

- Designe with a modern dark theme using Tailwind CSS
```

■ Step 2 : 

* >Deploy the project & copy the url & save it .


■ Step 3 :  
```
Create the Farcaster Manifest File

- Created /public/.well-known/farcaster.json - This file tells Base about our app
- Configured app metadata:

My project name : 

My url link : 

{
  "accountAssociation": {
    "header": "",
    "payload": "",
    "signature": ""
  },
  "miniapp": {
    "version": "1",
    "name": "My project name",
    "subtitle": "Fast & Easy Math",
    "description": "A simple calculator for basic arithmetic operations",
    "homeUrl": "https://your-domain.com",
    "iconUrl": "https://your-domain.com/icon.png",
    "splashImageUrl": "https://your-domain.com/splash.png",
    "splashBackgroundColor": "#1a1a1a",
    "screenshotUrls": [
      "https://your-domain.com/screenshot1.png",
      "https://your-domain.com/screenshot2.png"
    ],
    "primaryCategory": "utility",
    "tags": ["calculator", "math", "utility"],
    "tagline": "Calculate Instantly",
    "heroImageUrl": "https://your-domain.com/hero.png",
    "ogTitle": "Calculator",
    "ogDescription": "A simple calculator for basic math",
    "ogImageUrl": "https://your-domain.com/og-image.png",
    "noindex": false
  }
}
```

■ Step 4 : 

Added Required Images

* i attach a image , so convert that image as required ratio and attach the same image in our mini app for all 3 forms .

* >icon.png (300×300px) - A small icon of your app

* >splash.png (200×200px) - A splash screen image

* >screenshot.png (1284×2778px) - A screenshot showing how the app looks


■ Step 5 
```
Added Embed Metadata

- Add fc:miniapp meta tag to layout.tsx metadata

- Configure embed preview with:

- Image URL for the 3:2 aspect ratio preview

- Button configuration ("Open Calculator")

- Launch frame settings

- Splash image and background color
```

■ Step 6: 
```
Added Farcaster Miniapp SDK Integration

- Install @farcaster/miniapp-sdk package (automatically included)

- Update /app/page.tsx to import and use the SDK

- Call sdk.actions.ready() when the app loads

- This is the critical step that tells Base to hide the splash screen and display your calculator
```

■ Step 7: 
```
Update Next.js Configuration

- Update /next.config.mjs to work with Next.js 16's Turbopack

- Add turbopack: {} config to ensure clean builds

- Remove webpack-specific configurations
```

■ Step 8 : [Mini App Ownership]

* >Now for one time , click on deploy & deploy again 

Then Open Farcaster in Pc/Laptop 

* >Enable Developer Mode 

* >go to Developer section then & click on Mini app manifest tools 

* >then paste url ( check vidoe ) 

* >then click on fetch & then click on Genrate account association 

* >scan qr code and verify your farcaster account 

* >Now copy everything and paste in V0 ( add prompt ) 

Add this as account association  

* >then Reverify and Submit .


■ Step 9 : [Register Domain]

Download Base App : https://play.google.com/store/apps/details?id=org.toshi

* >Create Account with email 

* >then connect same farcaster account 


* Then Visit : https://www.base.dev/

* >signin with same base app email . 

* >and follow video process

# Done✔️✔️

<pre>

Stay Connected

👉 Join for more updates and future releases: https://linktr.ee/EarlyCTs

If you run into any issues, You can also reach me directly via DM.

Thanks for checking out this.

</pre>

<div align="center">

#  *❤️‍🔥 Happy vibe coding 👨🏻‍💻*

</div>

