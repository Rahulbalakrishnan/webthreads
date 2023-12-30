Features:

🔗 Seamless Connectivity: Join and participate in threaded conversations effortlessly. Connect with friends and discover new discussions seamlessly.

🌟 User-Centric Experience: Tailored with user convenience in mind, ensuring intuitive navigation and interaction.

📝 Threaded Conversations: Engage in threaded discussions, enabling focused conversations on various topics of interest.

🛠️ Next.js Powered: Leveraging the power of Next.js for smooth and responsive web experiences.

🛡️ Clerk for Authentication: Secure user authentication provided by Clerk for a trustworthy environment.

📊 MongoDB Backend: Robust and scalable MongoDB backend ensuring data integrity and performance.

Cloning Instructions:

    Clone the repository: git clone <HTTPS_URL> From the "<>Code" section at the top.

    Install dependencies: npm install
                    Note: Ensure installation of the latest Next.js and Clerk versions.

Configuration Setup:

    Create a file named .env.local in the root directory.

Clerk Account Setup:

    Register an account on Clerk and obtain the following keys:
        NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
        CLERK_SECRET_KEY
    
    Add these keys to .env.local:
        NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
        NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
        NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
        NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding

    MongoDB Setup:
        Create a MongoDB account and fetch the MONGODB_URL, adding it to .env.local.

    UploadThing Account Setup:
        Create an account on UploadThing and fetch UPLOADTHING_APP_ID and UPLOADTHING_SECRET, then add them to .env.local.

    Optional Clerk Webhook Setup:
        If utilizing group functionality in the app, obtain NEXT_CLERK_WEBHOOK_SECRET from Clerk and add it to .env.local.


Ensure all keys are added within the .env.local file as shown below:

    MONGODB_URL=<Your_key>
    UPLOADTHING_SECRET=<Your_key>
    UPLOADTHING_APP_ID=<Your_key>

    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<Your_key>
    CLERK_SECRET_KEY=<Your_key>

    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
    NEXT_CLERK_WEBHOOK_SECRET=<Your_key>

![Alt text](<readme.assets/0.png>)
![Alt text](<readme.assets/0 (2).png>)
![Alt text](<readme.assets/0 (3).png>)
![Alt text](<readme.assets/0 (4).png>)
![Alt text](<readme.assets/0 (5).png>)
![Alt text](<readme.assets/0 (6).png>)
![Alt text](<readme.assets/0 (7).png>)
![Alt text](<readme.assets/0 (8).png>)
![Alt text](<readme.assets/0 (9).png>)
![Alt text](<readme.assets/0 (10).png>)
![Alt text](<readme.assets/0 (11).png>)
![Alt text](<readme.assets/0 (12).png>)
![Alt text](<readme.assets/0 (13).png>)
![Alt text](<readme.assets/0 (14).png>)

Live at : https://webthreads.vercel.app