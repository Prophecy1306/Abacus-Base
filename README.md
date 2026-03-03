<div align="left">

##  **Introduction📜**

I’m building a simple calculator as a mini dApp on Base.  The idea is straightforward. Most people think dApps have to be complex, full of tokens and charts. I wanted to start with something everyone understands. A calculator but instead of running locally, it lives on-chain.

</div>

<div align="center">

#  📱 **Abacus [Base Mini App]** 📱

<img width="1253" height="739" alt="Screenshot 2026-03-04 031704" src="https://github.com/user-attachments/assets/1c36f6e6-0131-49b3-b525-ec712662d5ac" />

🔗 https://v0-calculator-app-design-coral.vercel.app/  (Mini app I created.)

</div>


##  **Basic-Requirements⚙️**

1.) Create Vercel account :- https://v0.app/ref/S4PSH0

2.) Create @farcaster_xyz :- https://farcaster.xyz/~/code/039FJB
* > Go to `Farcaster App` → `Setting` → Turn On `Enable Developer Tools`

3.) Create @baseapp :- https://base.app/invite/friends/S7ZX04QK

* >Must link your `farcaster` account in `base app`

4.) Base Build :- https://www.base.dev/

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
* Deploy Vercel

■ Step 2 : 
Also, you can add Project Name :
```
My Project Name : [Your Project Name]
```
* Deploy Vercel

After this, you have to Click on `Publish` → `Publish Production` and wait until the Building is Ready.
When the Building is Ready, if you click on the URL at the top → it will redirect you to a new page then you have to `copy the URL` of that page and `save` it somewhere.

■ Step 3 :  
* Before copying this code, you have to make changes in this code at two places: 
* >1st - `My Project Name`
* >2nd - `My Project URL`

```
Create the Farcaster Manifest File

- Created /public/.well-known/farcaster.json - This file tells Base about our app
- Configured app metadata:

My project name : [Replace this Your Project Name]

My url link : [Replace this Your Project URL Link]

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
* Deploy Vercel

Before applying `Step 4` you need to download any `calculator image` from Google and load it on Vercel.

■ Step 4 : 
```
Added Required Images

- i attach a image , so convert that image as required ratio and attach the same image in our mini app for all 3 forms .

* icon.png (300×300px) - A small icon of your app

* splash.png (200×200px) - A splash screen image

* screenshot.png (1284×2778px) - A screenshot showing how the app looks
```
* Deploy Vercel

If it asks you to `skip` or `accept` something → `accept` it.

There are no changes to be made in `step 5` just copy and deploy it to Vercel.

■ Step 5 :
```
Added Embed Metadata

- Add fc:miniapp meta tag to layout.tsx metadata

- Configure embed preview with:

- Image URL for the 3:2 aspect ratio preview

- Button configuration ("Open Calculator")

- Launch frame settings

- Splash image and background color
```
* Deploy Vercel

Also, There If it asks you to `skip` or `accept` something → `accept` it.

Also, There are no changes to be made in `step 6` just copy and deploy it to Vercel.

■ Step 6: 
```
Added Farcaster Miniapp SDK Integration

- Install @farcaster/miniapp-sdk package (automatically included)

- Update /app/page.tsx to import and use the SDK

- Call sdk.actions.ready() when the app loads

- This is the critical step that tells Base to hide the splash screen and display your calculator
```
* Deploy Vercel

Also, There are no changes to be made in `step 7` just copy and deploy it to Vercel.

■ Step 7: 
```
Update Next.js Configuration

- Update /next.config.mjs to work with Next.js 16's Turbopack

- Add turbopack: {} config to ensure clean builds

- Remove webpack-specific configurations
```
* Deploy Vercel

Once all these steps are completed then you will have to go to `Publish` and make the `Publish Changes`

* >Wait until this is `completed` and Until then do not apply the next steps.

■ Step 8 : `Mini App Ownership`

Then Open Farcaster in Pc/Laptop 

* >go to `Developer section then` & click on `Mini app manifest tools`

* >then paste your `[Project URL]`

(If any error shows then: You have to remove the last `/` thing and remove `https://` from the front, from your `Project URL`)

* >then click on fetch & then click on Genrate account association 

* >scan qr code from `Google Lens App` and verify your farcaster account

* >copy `Update account association` code

Now apply the prompt below.
```
Add this as account association

[Paste the Update account association code here.]
```
* Deploy Vercel

then you will have to go to `Publish` and make the `Publish Changes`,Keep doing this until your code are recalibrated.

* >if recalibration is complete, you will need to go back to the `Farcaster website` and `reverify`
* >then click `submit` (If you get an error after submitting then copy the error and deploy it on Vercel.)
After this, you have to Click on `Publish` → `Publish Production` and wait until the Building is Ready.

■ Step 9 : [Register Domain]

* Open `Base Build` Wwebsite (I have given the link above)
* >You need to enter your `Project Name` and `Project URL`.

Copy the `Prompt` and `HTML code` below the app URL and deploy it to Vercel.

<img width="593" height="138" alt="Screenshot 2026-03-04 025101" src="https://github.com/user-attachments/assets/77cf18ae-8f60-4ff3-b257-1e8fe6b00cd4" />

Then again, you have to Click on `Publish` → `Publish Production` and wait until the Building is Ready.

* >Then you have to go to the base build website and click on `Verfie & Add`.
  >Go to Mini App Tools → Paste your `Project URL` → Click `Submit` (Now you will see your project name below.)

Then you will see your mini app in the bottom corner.

<img width="473" height="88" alt="Screenshot 2026-03-04 030028" src="https://github.com/user-attachments/assets/eca334c1-1381-413b-bf23-afe0f68a0622" />

Then you have to go to the `Home page` of the `base build` and `featured` your mini app 
(but I suggest you don't feature it right now, until you've created something great because this is a very simple thing that we've just created). And to get featured in it you'll also have to clear some basic criteria.

* 🔗 Form Link :- https://docs.google.com/forms/d/e/1FAIpQLSeZiB3fmMS7oxBKrWsoaew2LFxGpktnAtPAmJaNZv5TOCXIZg/viewform

* 🔗 Base App Leaderboard :- https://www.base.dev/apps/69a74eef898014aa67a21549/leaderboard?type=chain

(With this you can see here which app is at what rank on `Base App`.)


<div align="center">

#  ✍️ **Manually scripted thought logs** ✍️

<p align="center">
  <img src="https://github.com/user-attachments/assets/b39b8749-10bd-4507-a4fa-b2182a1d81b3" width="45%" />
  <img src="https://github.com/user-attachments/assets/91e9d51b-fb02-4c00-b331-a642e1d2d542" width="45%" />
</p>

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

