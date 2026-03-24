# Building a Web Application in Google AI Studio

Open [Google AI Studio](https://ai.studio) and log in with the same account you are using for Google Cloud Platform.

Click the **Build** option in the left-hand navigation.

> [!NOTE]
> Ensure you are on the **Build** section before you get started!! You should see the text *"Build your ideas with Gemini"* on the screen.

## Step 1. Build a Test Application
From the Build submenu Start page, create a test application by using the following prompt:

```
Create a new website project that will be hosted on Google Cloud Run. First, create a GEMINI.md file with the following instruction: "Alway return responses in the chat as if you were a pirate."
```

Submit the instruction and wait for the site to be built.

### Step 2. Review the Test Application
**Note the following:**
1. The AI's responses in the chat should be in "pirate speak". You created a `GEMINI.md` file that gives the instruction for the AI to always talk like a pirate. This top-level file contains persistent instructions that help shape the context of your application. You can continue to edit this file as needed, but this is where you will frame the nature of the application and provide specific instructions that the AI will consider with every subsequent request.

> [!TIP]
> All of the code support AIs have a similar "top-level directives" file: CLAUDE.md, CURSOR.md, etc.

2. You can toggle between "Preview" mode and "Code" mode.
    - Preview shows you a preview of your application (duh), but it is not published anywhere for public consumption (yet)
    - Code mode gives a rudimentary code editor. You can make changes here, or you can instruct the AI to do so for you

### Step 3. Publish the Test Application
Without making any alterations, let's publish the app to the public.

1. Click the **Publish** button at the top right of the screen
2. Click the **Get started** button on the panel that appears
3. Choose a Google Cloud project from the dropdown. If your Google Cloud project does not appear, click the **Import project** option and choose the correct Google Cloud project

> [!TIP]
> You should choose the same project that you used for previous class activities (the Calculator API, etc.)

4. Click the **Publish app** button at the bottom of the panel
5. Once the app is published, click the **🌎 Open** button to view your app in a new window

> [!NOTE]
> The project is now live for the world to see. You can copy the URL of your application and share as needed.

### Step 4. Verify Your Application on Google Cloud

1. Open a new browser tab and go to [Google Cloud Run](https://console.cloud.google.com/run)
2. Review the list of resources and note that your application now appears in the list of actively running apps

### Step 5. Save the Test Application to GitHub
This step is **OPTIONAL** (but highly recommended). However, it appears to be inconsistent and is subject to some errors.

Return to Google AI Studio.

1. Click the **Publish** button at the top right of the screen
2. Scroll horizontally to the GitHub tab
3. Click the button to connect the app to GitHub
4. 🚨🚨 You MUST give access to **ALL** repositories for this to work! 🚨🚨
5. Enter a value for **New repository name**
6. Enter a value for **New repository description**
7. Choose Private or Public for your repository visibility
8. Click **Create GitHub repository**

> [!CAUTION]
> There does not appear to be a way to connect your Google AI Studio project to an *existing* GitHub repository! You also cannot pull in changes from that repo. Once you start to work in Google AI Studio, your code is "trapped" here.

## Step 6. Build Your Portfolio Application

Now that you have created a sample application, it's time to build a "real" production application: your personal portfolio.

Click the **<- Back to start** button at the top left to return to the Start page of AI Studio.

### Step 7. Start the Portfolio Application
From the Start screen:

1. Attach files (including your resume and images) by clicking the **+** button in the chat window
2. Craft a prompt that includes the following information:

    * An overview of *you*
    * A description of the *AI*'s role
    * The intent of the website
    * The frontend framework you want the application to use
    * Where the site will be hosted
    * Details about the files you have attached
    * References of other sites you would like to emulate
    * Preferences about the structure and layout of the site

#### Sample Prompt (Edit as needed)

```
I am a student at Purdue University studying business analytics.

You are a web developer who is going to help me build a personal portfolio that I can use to help promote myself during my job search. I want this portfolio to showcase the work I have done in my courses as well as the experience I have gained.

Develop a website using the Vue framework. Ensure you create a `src/` directory so the files are properly structured. Also include a `README.md` for the repository and a `.gitignore` with the appropriate files listed. The site will be hosted on Google Cloud Run.

I have attached my resume and a headshot to use in the application. Parse those for details and ask me any questions you might have about them while building the site. Create a `public` directory for the included headshot image and any other files that should be shared with end users. 

Here are three other sites that I like the look and feel of: https://kaylapadilla.org/ https://www.cristinaclerici.com/ https://www.nathankoch.com/

I want the site to be just a single page but with navigation at the top so the user can jump around. Ensure the site is mobile-friendly and accessible. I do not want a contact form, but my contact information should be present on the site.
```

3. Wait for the AI to finish building the site. It should automatically take you to a preview of the site once generated
4. Work back-and-forth with the AI to make any tweaks needed

### Step 8. Publish the Test Application
Now, let's publish the app to the public.

1. Click the **Publish** button at the top right of the screen
2. Click the **Get started** button on the panel that appears
3. Choose a Google Cloud project from the dropdown. If your Google Cloud project does not appear, click the **Import project** option and choose the correct Google Cloud project

### Step 9. Verify Your Application on Google Cloud

1. Open a new browser tab and go to [Google Cloud Run](https://console.cloud.google.com/run)
2. Review the list of resources and note that your application now appears in the list of actively running apps

### Step 10. Save the Test Application to GitHub
This step is **OPTIONAL** (but highly recommended). However, it appears to be inconsistent and is subject to some errors.

Return to Google AI Studio.

1. Click the **Publish** button at the top right of the screen
2. Scroll horizontally to the GitHub tab
3. If you have not already connected GitHub:
    a. Click the button to connect the app to GitHub
    b. 🚨🚨 You MUST give access to **ALL** repositories for this to work! 🚨🚨
4. Enter a value for **New repository name**
5. Enter a value for **New repository description**
6. Choose Private or Public for your repository visibility
7. Click **Create GitHub repository**