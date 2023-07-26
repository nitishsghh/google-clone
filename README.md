This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/pages/api-reference/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


### GOOGLE CLONE 
PROJECT ON YOUR GCP ACCOUNT
1. Create new project in Google Cloud Platform Console https://console.cloud.google.com
/.
2. Enable billing if not already done so (required before creating any resource )
3. Go to APIs & Services -> Library search "Cloud Run" enable it . This will 
allow us create cloud functions using next js framework.
4. Inside of console go to Navigation menu > Kubernetes Engine > Clusters click 'Create 
Cluster' button 
5. Choose region , cluster name etc.. then Click CREATE button
. Wait until Cluster is created successfully. Once its ready we need to connect kubectl command line tool to 
this kubernetes engine from local machine which has gcp cli installed.(if not install first).
To do this follow below steps :
* Install google sdk tools
(gcloud components install kuberntes-engine)
* Authenticate user account via gloud auth login <your_account>   # replace <> 
with actual email id used during signup process
. It should open web based authentication window where one needs to enter OTP generated through mobile number registered 
.
This should generate credentials required to access kube api server inside that cluster. Now let's deploy app .
